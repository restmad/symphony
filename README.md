# [Symphony](https://github.com/b3log/symphony) [![Build Status](https://img.shields.io/travis/b3log/symphony.svg?style=flat)](https://travis-ci.org/b3log/symphony)

* [简介](#%E7%AE%80%E4%BB%8B)
  * [动机](#%E5%8A%A8%E6%9C%BA)
  * [案例](#%E6%A1%88%E4%BE%8B)
* [功能特性](#%E5%8A%9F%E8%83%BD%E7%89%B9%E6%80%A7)
  * [好用的编辑器](#%E5%A5%BD%E7%94%A8%E7%9A%84%E7%BC%96%E8%BE%91%E5%99%A8)
  * [智能、灵活的信息架构](#%E6%99%BA%E8%83%BD%E7%81%B5%E6%B4%BB%E7%9A%84%E4%BF%A1%E6%81%AF%E6%9E%B6%E6%9E%84)
  * [满足多样化的发帖需求](#%E6%BB%A1%E8%B6%B3%E5%A4%9A%E6%A0%B7%E5%8C%96%E7%9A%84%E5%8F%91%E5%B8%96%E9%9C%80%E6%B1%82)
  * [人性化的回帖交互](#%E4%BA%BA%E6%80%A7%E5%8C%96%E7%9A%84%E5%9B%9E%E5%B8%96%E4%BA%A4%E4%BA%92)
  * [用户个性化设置](#%E7%94%A8%E6%88%B7%E4%B8%AA%E6%80%A7%E5%8C%96%E8%AE%BE%E7%BD%AE)
  * [编辑历史与匿名发布](#%E7%BC%96%E8%BE%91%E5%8E%86%E5%8F%B2%E4%B8%8E%E5%8C%BF%E5%90%8D%E5%8F%91%E5%B8%83)
  * [对搜索引擎友好](#%E5%AF%B9%E6%90%9C%E7%B4%A2%E5%BC%95%E6%93%8E%E5%8F%8B%E5%A5%BD)
  * [实时的消息通知](#%E5%AE%9E%E6%97%B6%E7%9A%84%E6%B6%88%E6%81%AF%E9%80%9A%E7%9F%A5)
  * [好玩的活动](#%E5%A5%BD%E7%8E%A9%E7%9A%84%E6%B4%BB%E5%8A%A8)
  * [强大的后台管理](#%E5%BC%BA%E5%A4%A7%E7%9A%84%E5%90%8E%E5%8F%B0%E7%AE%A1%E7%90%86)
  * [开放的内容 API](#%E5%BC%80%E6%94%BE%E7%9A%84%E5%86%85%E5%AE%B9-api)
  * [集成云邮件服务](#%E9%9B%86%E6%88%90%E4%BA%91%E9%82%AE%E4%BB%B6%E6%9C%8D%E5%8A%A1)
  * [集成云搜索服务](#%E9%9B%86%E6%88%90%E4%BA%91%E6%90%9C%E7%B4%A2%E6%9C%8D%E5%8A%A1)
* [计划中的特性](#%E8%AE%A1%E5%88%92%E4%B8%AD%E7%9A%84%E7%89%B9%E6%80%A7)
* [安装](#%E5%AE%89%E8%A3%85)
  * [需求](#%E9%9C%80%E6%B1%82)
  * [步骤](#%E6%AD%A5%E9%AA%A4)
  * [配置](#%E9%85%8D%E7%BD%AE)
* [使用授权](#%E4%BD%BF%E7%94%A8%E6%8E%88%E6%9D%83)
  * [开源授权](#%E5%BC%80%E6%BA%90%E6%8E%88%E6%9D%83)
  * [商用授权](#%E5%95%86%E7%94%A8%E6%8E%88%E6%9D%83)
* [贡献](#%E8%B4%A1%E7%8C%AE)
  * [作者](#%E4%BD%9C%E8%80%85)
  * [讨论区](#%E8%AE%A8%E8%AE%BA%E5%8C%BA)
* [感悟](#%E6%84%9F%E6%82%9F)
* [鸣谢](#%E9%B8%A3%E8%B0%A2)
    
## 简介

[Symphony](https://github.com/b3log/symphony)（[ˈsɪmfəni]，n.交响乐）是一个现代化的社区平台，因为它：

* 实现了面向内容讨论的论坛
* 包含了面向用户分享、交友、游戏的社交网络
* 集成了聚合独立博客的能力，共建共享优质资源
* 并且 `100%` 开源

欢迎到 [Sym 官方讨论区](https://hacpai.com)了解更多。另外，如果你需要搭建一个企业内网论坛，请使用 [SymX](https://github.com/FangStarNet/symphonyx)。

### 动机

Sym 的诞生是有如下几点原因：

（正版）

* 很多系统界面上仍然保持着老式风格，远远没有跟上时代发展的脚步，它们没有创新、好玩的特性，缺少现代化的交互元素和用户体验
* 大部分系统是从程序员的角度进行设计的，没有考虑实际的产品、运营需求，这类系统功能过于简陋、细节不够精致、缺乏长期维护 
* 另外，我们正在探索新的社区模式，实现独奏（[Solo](https://github.com/b3log/solo)）与协奏（[Symphony](https://github.com/b3log/symphony)）相结合的[社区新体验](https://hacpai.com/b3log)

（野版）

* 万能的 GitHub 上连个能用的 Java 社区系统都找不到，Sym 填补了这个宇宙级空白
* 做最 NB 的开源社区系统，预计几年以后 82% 的社区都将是 Sym 搭建的
* 作者技痒，炫技之作，Ruby/Python/Node.js/（特别是）PHP 怎么能比得过 Java

### 案例

个人维护：

* [黑客派](https://hacpai.com)
* [宽客网](http://www.cnq.net)
* [贵州IT](http://www.gzit.info)
* [超级产品经理](https://imspm.com)
* [Titandb 学习主站](https://titandb.cn)

公司维护：

* [四方环视](http://bbs.ivrpano.com)

如果你也搭建好了，欢迎通过 Pull Request 将你的站点加到这个列表中 :-p

## 功能特性

具体功能点细节可浏览 [Sym 功能点脑图](http://naotu.baidu.com/file/cd31354ac9abc047569c73c560a5a913?token=b9750ae13f39ef9a)，下面列出了 Sym 的主要特性，说明 **现代化** 的由来。

### 好用的编辑器

* Markdown：支持 GFM 语法以及一些扩展语法
* 格式调整：粗体、斜体、超链接、引用、列表等可以通过工具栏按钮，同时也支持快捷键
* 文件上传：支持复制粘贴或者拖拽上传图片；支持上传普通文件；对 MP3 会使用在线播放器进行渲染
* 剪贴板处理：自动将复制的内容转换为 Markdown 格式；外链的图片自动上传站内
* @用户：根据用户名自动补全，支持快捷键
* Emoji：支持大部分主流 Emoji 表情，快捷键自动补全
* 数学公式：支持  LaTex 数学公式渲染
* 数据暂存：支持本地浏览器暂存数据，避免意外情况导致编辑内容丢失

### 智能、灵活的信息架构

传统的节点式社区要求帖子必须 **分类** 到某一个节点下，信息架构方式属于自上而下。Sym 不是自上而下的节点式信息架构，帖子不需要固定分类，通过标签 **聚合** 到某个领域下。

* 标签：根据帖子内容智能抽取关键字进行标签自动补全，一篇帖子关联多个标签。标签和标签之间以带边权重的图结构进行描述，方便进行相关计算
* 领域：一个领域下包含了多个标签，通过标签将帖子自动聚合到具体领域，随时可以通过增减关联标签从而达到调整领域范围，最终聚合出适合的帖子列表

### 满足多样化的发帖需求

目前支持 4 中帖子类型，满足不同用户的偏好：

* 普通帖子：提问或分享对别人有帮助的经验与见解
* 思绪：写作过程的记录与重放，文字版的沙画表演 [(?)](https://hacpai.com/article/1441942422856)
* 小黑屋：邀请好友在私密空间中进行交流
* 同城广播：发起你所在城市的招聘、Meetup 等

另外，所有帖子都可以设置 **打赏区** ，打赏区可以放置一些“珍藏”内容，只有打赏后的用户才能浏览。打赏区编辑器同样支持 Markdown、Emoji 和文件上传等特性。打赏区支持内容更新，并可以随时调整打赏积分值。

对于测试帖，可以使用 Sandbox 机制：带有 Sandbox 标签的帖子将视为测试帖，不会显示在首页或是某领域内，只会展现在发帖者自己的帖子列表中。

### 人性化的回帖交互

* 实时呈现：回帖提交后其他浏览者可以不刷新页面就实时看到你的回帖
* 随时滚动：浮出式回帖编辑器方便回帖者随时滚动屏幕查看其他内容，不必担心焦点丢失
* 真正的回复：回复是针对回帖而言的，而 @ 是针对用户而言的，@ 是提及不是回复，很多系统都没有考虑到这一点。回复/引用可以在当前位置进行展开浏览，也可以跳转到回帖处，并支持跨分页跳转
* 智能机器人：回帖时可以让机器人也参与到讨论中来，活跃气氛的同时说不定机器人真的能解决一些问题呢

### 用户个性化设置

用户可以自己设置很多参数以满足个性化需求：

* 帖子列表浏览分页每页条目数
* 回帖浏览模式：传统（按发布时间升序，无实时推送刷新）；实时（按发布时间降序，实时推送新回帖）
* 头像浏览模式：原图（支持 gif 动图）；静态图
* Chrome 通知/邮件订阅/键盘快捷键开关
* 设置常用 Emoji，方便发布内容时快速插入表情

除了功能个性化配置项，还有很多隐私项开关：

* 是否公开帖子/回帖列表
* 是否公开关注用户/标签/粉丝、收藏帖子、积分列表
* 是否公开在线状态
* 是否公开 UA 信息
* 是否公开地理位置
* 是否参与财富/消费排行

另外，用户还可以完整导出数据，包括帖子和回帖。

### 编辑历史与匿名发布

发帖者可以进行该帖更新，但是每次更新都会产生编辑历史，浏览者可以看到并对比其内容变更。目前还不支持回帖更新，后续会加入，敬请期待。

帖子和回帖都可以使用匿名身份进行发布，你懂的。

### 对搜索引擎友好

* 标签、领域可以自定义链接，并且可以单独配置 meta title/keywords/description
* 后端 Markdown 渲染，输出爬虫可读的 HTML 
* 管理员设置的浏览权限不影响爬虫抓取内容
* 通过一些 HTML 细节属性（比如 canonical）进行 SEO

### 实时的消息通知

* 可按类别展示消息，标记已读
* 详细的消息类别：收到的回帖、收到的回复、@我的、我关注的人、积分相关、同城、系统消息等
* 友好的 Chrome 桌面提醒

### 好玩的活动

* 领取签到奖励、领取昨日活跃奖励
* 上证博彩
* 字 [(?)](https://hacpai.com/article/1465995560698)
* 贪吃蛇

后续还会继续加入一些好玩的在线小游戏。

### 强大的后台管理

* 后台首页：数据统计、版本检查
* 用户管理：搜索用户、添加用户、用户数据维护（状态设置、积分等）
* 帖子管理：搜索帖子、添加新帖、帖子数据维护（置顶、重建索引等）
* 回帖管理：状态设置、内容更新
* 领域管理：添加领域、领域数据维护（关联标签、图标、URI、CSS、描述等）
* 标签管理：添加标签、标签数据维护（图片、URI、CSS、描述等）
* 保留词管理：添加保留词、保留词数据维护
* 邀请码管理：生成邀请码、邀请码数据维护
* 广告管理：侧边栏独占展位维护
* 其他管理：发帖/回帖开关；用户开放/关闭/邀请码注册开关

### 开放的内容 API

Sym 提供了 [API](https://hacpai.com/article/1457158841475) 进行帖子、回帖的同步（[B3log 构思](https://hacpai.com/b3log)），目前 [Solo](https://github.com/b3log/solo)、[Typecho](https://github.com/DT27/B3logForHacPai)、[Z-BlogPHP](https://github.com/zblogapp/hacpai)、[WordPress](https://github.com/zh-h/hacpai-sync-wordpress) 均已经提供插件来进行内容同步，欢迎大家进行接入！

以后也会陆续加入新的接口，方便大家制作 APP 客户端或是一些有价值的应用。

### 集成云邮件服务

通过配置即可集成 [SendCloud](http://sendcloud.sohu.com) 云邮件服务，送达率较为自己搭建邮件服务更为可靠。

* 用户注册验证、密码重置通过触发类型发送
* 每周优选订阅推送通过批量类型发送

### 集成云搜索服务

* 通过配置即可集成 [Algolia](https://www.algolia.com/referrals/1faf0d17/join) 云搜索服务，可自定义搜索字段，并进行权重、排序调优
* 也可以自己搭建 Elasticsearch 并通过配置进行集成

后续会对搜索功能进行加强，实现条件过滤，结果高亮等，敬请期待。

## 计划中的特性

### 信任系统

通过历史数据对用户进行分级提权，让用户从浏览者逐步变为参与者、组织者、管理者，实现自治的社区生态系统。

### 徽章系统

记录下用户达成的成就以及对社区的贡献。

## 安装

### 需求

Maven3+、MySQL5.5+、Jetty9+/Tomcat9+

### 步骤

1. [下载](https://github.com/b3log/symphony/archive/master.zip)源码
2. 解压后修改 `src/main/resources/local.properties` 中的数据库配置，并创建数据库
3. _可能需要_修改 `latke.properties` 中的端口为容器端口
4. _可能需要_修改 `init.properties` 中的管理员账号
3. 使用 `mvn install` 进行构建
4. 将构建好的 war 包部署到容器中，数据库表会在第一次启动时自动建立

注意：

* 没有数据库建表 SQL 脚本，手动建库后，表会在第一次启动时自动生成
* 生产环境建议使用反向代理，并需要配置好 WebSocket 代理
* Tomcat 用 9 以上版本，最好是使用最新版本
* 参考 [Latke 配置剖析](https://hacpai.com/article/1474087427032)

### 配置

* 图片上传默认是上传服务器本地，要使用[七牛](https://portal.qiniu.com/signup?code=3lewbghpvrqky)可配置 `symphony.properties` 中的 `qiniu.*` 属性
* 将 WEB-INF/cron.xml 中注释掉的部分打开
* 邮件发送使用的是 [SendCloud](http://sendcloud.sohu.com)，需要配置 `symphony.properties` 中的 `sendcloud.*` 属性
* 用户注册时需要验证邮箱的，所以必须先配置好 SendCloud

如果遇到问题，可以参考一下这篇[帖子](https://hacpai.com/article/1468824093225)。

## 使用授权

商用授权和开源授权在功能上没有任何区别，但商用授权后可以去除页脚版权部分。如果在未获得商用授权前私自去除版权部分，必将追究法律责任。

### 开源授权

请仔细查看并遵循以下使用条款，尊重我们的劳动成果。

* This software is open sourced under the Apache License 2.0 
* You can not get rid of the "Powered by [B3log 开源](http://b3log.org) • [Sym](https://github.com/b3log/symphony)" from any page, even which you made
* If you want to use this software for commercial purpose, please mail to support@liuyun.io for a commercial license request
* Copyright &copy; b3log.org, all rights reserved

### 商用授权

如果需要将 Sym 用于商用（比如公司搭建社区）则必须付费，价格为 ￥10000，请联系 QQ 845765 进行细节咨询。

## 贡献

### 作者

Sym 的主要作者是 [Daniel](https://github.com/88250) 与 [Vanessa](https://github.com/Vanessa219)，所有贡献者可以在[这里](https://github.com/b3log/symphony/graphs/contributors)看到。

我们非常期待你加入到这个项目中，无论是使用反馈还是代码补丁，都是对 Sym 一份满满的爱 :heart:

### 讨论区

* 到 Sym 官方[讨论区](https://hacpai.com/tag/Sym)发帖（推荐做法）
* 来一发 [issue](https://github.com/b3log/symphony/issues/new)
* 加入 Sym 开发支持 Q 群 17370164

## 感悟

在实现 [B3log 构思](https://hacpai.com/b3log)的这几年：

* 我们见证了 xAE（GAE/BAE/SAE/etc）的兴起与没落。2009 年选择了 GAE 作为服务器，并开始实现 [Latke](https://github.com/b3log/latke) 框架来解决跨云平台，直到[告别 GAE](https://hacpai.com/article/1443685401909)，不得不感叹技术更迭之快
* 感受到了自造轮子的优缺点，并且可以肯定一点：对于一个想要长久的产品来说，自制技术框架优势远大于劣势
* 一个好玩的产品或说是细节特性然并卵，需要做的是一个能够持续提供用户价值的产品/特性
* 虽然直到目前 B3log 系产品用户不多，但我们已经初步证明了：Java 用来实现博客、论坛没有什么不好的
* 使用开源软件，了解开源思想，融入开源生态
* [如果你想做个程序员相关的论坛，请三思](https://hacpai.com/article/1471007706462)
* [你怎么看待社群、社区这两个词？](https://hacpai.com/article/1465652829809)
* [UGC 社区价值生态](https://hacpai.com/article/1462028669762)

## 鸣谢

Sym 的诞生离不开以下开源项目：

* [jQuery](https://github.com/jquery/jquery)：前端 JavaScript 工具库
* [CodeMirror](https://github.com/codemirror/CodeMirror)：前端 Markdown 编辑器内核
* [Highlight.js](https://github.com/isagalaev/highlight.js)：前端代码高亮库
* [emojify.js](https://github.com/Ranks/emojify.js)：前端 Emoji 处理库
* [APlayer](https://github.com/DIYgod/APlayer)：前端 HTML5 音乐播放器
* [ECharts](https://github.com/ecomfe/echarts)：前端 JavaScript 交互式图表库
* [MathJax](https://github.com/mathjax/MathJax)：前端数学公式渲染引擎
* [SoundRecorder](https://github.com/rderveloy/JavaScript-Sound-Recorder)：前端 HTML5 录音库
* [ZeroClipboard](https://github.com/zeroclipboard/zeroclipboard)：前端剪贴板支持
* [JavaScript MD5](http://pajhome.org.uk/crypt/md5/index.html)：前端 JavaScript MD5 库
* [ReconnectingWebSocket](https://github.com/joewalnes/reconnecting-websocket)：前端 WebSocket 重连库
* [to-markdown](https://github.com/domchristie/to-markdown)：前端 HTML 转换 Markdown
* [UAParser.js](https://github.com/faisalman/ua-parser-js)：前端 User-Agent 解析库
* [Sass](http://sass-lang.com)：前端 CSS 处理工具
* [jsoup](https://github.com/jhy/jsoup)：Java HTML 解析器
* [pegdown](https://github.com/sirthias/pegdown)：Java Markdown 处理库
* [Apache Commons](http://commons.apache.org)：Java 工具库集
* [Jodd](https://github.com/oblac/jodd)：Java 工具库集
* [emoji-java](https://github.com/vdurmont/emoji-java)：Java Emoji 处理库
* [User-Agent-Utils](https://github.com/HaraldWalker/user-agent-utils)：Java User-Agent 解析库
* [Druid](https://github.com/alibaba/druid)：Java 数据库连接池
* [FreeMarker](http://freemarker.org)：好用的 Java 模版引擎
* [Latke](https://github.com/b3log/latke)：Java Web 框架 
* [NetBeans](https://netbeans.org)：全宇宙暂时排名第三的 IDE

----

Logo 征集中....
