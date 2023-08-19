# 爬虫项目实战

## 说明

所有项目均为作者**练手分享项目**，如遇**侵权请联系删除**，仅作**学习分享**，**不能进行任何商业活动**。

由于程序完成的**时间问题**，部分项目可能**无法复用**。

练习笔记见**note.txt**

_此项目将持续更新_

**下面是个人对于网站爬取难度评级**

| 难度等级 | 表示 | 补充         |
| -------- | ---- | ------------ |
| 骑士侍从 | 0    | 入门         |
| 准骑士   | 00   | 踏过门槛了   |
| 骑士     | *    | 初级         |
| 大骑士   | **   | 比初级高一点 |
| 大地骑士 | ***  | 中等难度     |
| 辉耀骑士 | +    | 中上难度     |
| 圣殿骑士 | ++   | 比较难       |
| 圣骑士   | +++  | 难           |
| 神印骑士 | KING | 地狱         |

### 项目目录

``` mermaid
graph TD;
	C(crawlProject)-->基础篇;
	C(crawlProject)-->自动化篇;
	C(crawlProject)-->进阶篇;
    基础篇-->request篇;
    基础篇-->解析html以及正则篇;
    基础篇-->scrapy篇;
    基础篇 -->高性能异步爬虫;
    自动化篇-->selenium
    自动化篇-->playwright;
    进阶篇-->综合案例;
    进阶篇-->js逆向专题;
    js逆向专题-->请求头或响应数据加密;
    js逆向专题-->浏览器指纹检测;
    js逆向专题-->webPack篇;
    js逆向专题-->环境检测篇;
    js逆向专题-->wasm篇;
```



## 基础篇

### request篇

| 难度标识 | 项目名         | 补充           |
| -------- | -------------- | -------------- |
| 骑士侍从 | 百度网页       | 第一个爬虫程序 |
| 骑士侍从 | ua识别         | 初始反爬       |
| 骑士侍从 | 百度翻译       | 认识post请求   |
| 骑士侍从 | 豆瓣电影       | 基础           |
| 骑士侍从 | 肯德基位置查询 | json练习       |

### 解析html以及正则篇

| 难度标识 | 项目名     | 补充                     |
| -------- | ---------- | ------------------------ |
| 准骑士   | 获取fakeua | lxml解析                 |
| 准骑士   | 4k图片爬取 | lxml以及解决编码错误问题 |
| 准骑士   | 58         | lxml以及分页爬取         |
| 准骑士   | bs基础     | 初始bs                   |
| 准骑士   | bs案例     | 实战bs                   |
| 准骑士   | xpath基础  | 初始xpath                |
| 准骑士   | xpath解析  | 练习xpath                |
| 准骑士   | 正则基础   | 初始正则                 |
| 准骑士   | 正则练习   | 实战正则                 |
| 准骑士   | 简历爬取   | 以上的小综合             |

### scrapy篇

| 难度标识 | 项目名       | 补充                                             |
| -------- | ------------ | ------------------------------------------------ |
| 大骑士   | bossjob      | 一级页面爬取，可能不可用                         |
| 大骑士   | 双色球       | 都是基本scrapy操作                               |
| 大骑士   | 图片         | 都是基本scrapy操作                               |
| 大骑士   | 阳光政策     | 都是基本scrapy操作                               |
| 大骑士   | yi车数据爬取 | 带有js逆向，不过是入门级，以及大批量json数据解析 |
| 大骑士   | 校花网       | 都是基本scrapy操作                               |
| 大骑士   | 网易新闻     | 都是基本scrapy操作                               |
| 大骑士   | 17k小说爬取  | 都是基本scrapy操作                               |

### 高性能异步爬虫

| 难度标识 | 项目名            | 补充     |
| -------- | ----------------- | -------- |
| 骑士侍从 | 认识flask         | 基础知识 |
| 骑士     | 线程池基础        | 基础知识 |
| 大骑士   | meinv图片批量爬取 | 基础     |
| 大骑士   | 明星图片爬取      | 基础     |
| 大骑士   | 多任务协程        | 基础     |
| 大骑士   | 线程池应用        | 基础     |

## 自动化篇

### selenium

| 难度标识 | 项目名             | 补充           |
| -------- | ------------------ | -------------- |
| 骑士侍从 | 基础自动操作       | 基本自动化操作 |
| 骑士侍从 | 模拟登陆           | 练习自动化     |
| 骑士侍从 | 动作链和ifream处理 | 练习自动化     |
| 骑士侍从 | 无头浏览器和反检测 | 练习           |
| 骑士     | 12306模拟登录      | 多半不可用     |
| 骑士     | damai网            | 多半不可用     |

### playwright

| 难度标识 | 项目名   | 补充                                                         |
| -------- | -------- | ------------------------------------------------------------ |
| 骑士     | 邮政编码 | 通过地址查询邮政编码，使用同步方式，包含等待操作以及根据情况选择不同的表格，同时使用pandas对excel文件进行操作 |
| 大地骑士 | 采集资料 | 通过网站名采集网站的邮箱电话地址社交媒体链接，难点在于每个网站风格完全不一，所有数据也不一并且数量很大，写正则很不好写，处理异步也比较麻烦，仓库只列举了其中10个页面，需要编写者对正则以及异步playwright有一定的了解 |

## 进阶篇

### 综合案例

***

| 难度标识 | 项目名             | 补充                                                         |
| -------- | ------------------ | ------------------------------------------------------------ |
| 骑士     | 某诗文网           | 验证码相关，登录以及图片验证码解决 --- ddddocr               |
| 大骑士   | 语言爬虫           | 利用网络将文本转为语言，支持中英韩三国语言                   |
| 大骑士   | b站综合            | 检查用户是否给你点赞，拉去消息列表，拉取点赞列表             |
| 大地骑士 | 某视频网站         | m3u8视频下载，解决带密钥以及不带密钥情况，m3u8入门级别以及多线程下载 |
| 大地骑士 | ins爬虫            | 对于页面参数提取以及解析json文件                             |
| 大地骑士 | douyin全站数据爬取 | 包括视频图片下载，评论爬取，用户信息爬取...                  |
| 大地骑士 | weibo全站数据爬取  | 包括搜索用户，搜索帖子，下载评论，下载用户相册，用户主页，用户信息... |

### js逆向专题

***

#### 请求头或响应数据加密

| 难度标识 | 项目名        | 补充                            |
| -------- | ------------- | ------------------------------- |
| 骑士     | 烯牛数据      | 请求头加密，响应体加密          |
| 骑士     | 娱乐指数      | 基础入门                        |
| 骑士     | 艺恩数据      | 响应体加密                      |
| 骑士     | 行行查        | 响应体加密                      |
| 大骑士   | fjs公共交易   | 混淆参数加密                    |
| 大骑士   | 唯一艺术      | 动态js运行代码                  |
| 大地骑士 | 某天气网站    | 动态js 动态key 动态参数 反debug |
| 大地骑士 | 某足球网站    | 请求体多重加密，加密位置难定位  |
| 大地骑士 | wangyiyun音乐 | 实现全站数据爬取                |
| 大地骑士 | gds公共交易   | 混淆参数，需要找定位            |

#### webPack
| 难度标识 | 项目名 | 补充                                               |
| -------- |-------------|--------------------------------------------------|
| 大地骑士     | china五矿 | 基础webpack，标准版加密算法，简单，可用多种方式实现（nodejs,python和扣代码） |


#### 环境检测

| 难度标识 | 项目名  | 补充                                                  |
| -------- | ------- | ----------------------------------------------------- |
| 辉耀骑士 | redBook | x-s环境检测，需要自己把cookie和localstorage放到文件中 |
| 辉耀骑士 | bossjob | __zp_s...__环境检测，每天js都不同，需要补一些环境，并且修改js，有一个module检测等...|
| 辉耀骑士 | 猿人学2023第一题 | 魔改md5和aes 删除部分蜜罐，补充浏览器环境即可 |
| 大地骑士 | 饿了么参数 | 通过playwright获取bx_et参数 |

#### wasm加密

| 难度标识 | 项目名 | 补充                                                         |
| -------- | ------ | ------------------------------------------------------------ |
| 辉耀骑士 | 某航空 | wasm操作内容实现加密解密 请求头参数加密更新 阿里系v2检测 阿里系v3检测(手动滑获取参数) |

#### 浏览器指纹检测

| 难度标识 | 项目名 | 补充                                                         |
| -------- | ------ | ------------------------------------------------------------ |
| 大地骑士 | 易九批 | 首先是加密请求体，其次是tls指纹检测，目前使用第三方库过了主页请求 |

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=xishandong/crawlProject&Date)](https://star-history.com/#xishandong/crawlProject&Date)

## 赞助

如果你认为本仓库对你学习爬虫和逆向有所帮助，欢迎赞助作者，请作者喝一杯奶茶~！！

（你的支持可以让作者开心一整天😊）

<div style='display:flex'>
    <img src="./README_img/wechatPay.JPG" alt="微信支付" style="width: 250px;height: 250px;objec-fit:contain" />
    <img src="./README_img/alipay.JPG" alt="支付宝支付" style="width: 250px;height: 250px;objec-fit:contain" />
</div>


​    

