# wedroit
## Python crawler of wexin group.
If you are beset by too many weixin article to archive just like me, this python crawler will help you out of this trap.

I will write the project below in chinese, forgive me about my lack of lexical.

## 工作流程
1. 建立一个登陆python微信的web界面，并配有登陆后的爬虫定位功能，选定需要抓取消息文章的微信群。
1. 设定爬虫工作的周期，并按周期保存消息记录，并转换为url以备爬取。
1. 将url转化为html文档，此时去掉不应有的广告，并将格式统一化处理。
1. 开发文档管理界面，配以下载、阅读等功能。

## 项目内容
1. 一个包含微信登陆、爬虫定位和文档管理的前端。
1. 运行python微信爬取url，并实现url转html的后端。
1. 存放微信文章，并方便用户文档管理和收费下载的云端。

## 项目计划
1. 初期实现微信python登陆、定位微信群和保存微信文章。
1. 中期搭建后端，实现微信文章转url和url转html，并保存多媒体文件。
1. 后期搭建前端，整合微信登陆、爬虫定位和文档管理。
1. 未来实现云端文档管理和收费下载，并丰富前端内容推荐等功能。

## 项目预期
1. 将微信群中自己喜爱的微信文章保存起来是每个微信用户的权利（droit），而微信群却没有qq群那样方便的文档管理方案，因此wedroit能够让微信文章管理起来更加方便。
1. 有些微信号收到媒体大佬压力，微信文章存在过期或删除情况。实时保存有助于保存要闻或八卦，给广大群众一个公平的网络环境。
1. 微信爬虫由于其软件权限问题，一直是一片空白，因此wedroit（微抓）能够帮助用户自由抓取自己需要的聊天记录或文章，有效管理自己的个人信息。
