# 友链交换

**非常欢迎前来申请友链的小伙伴，在交换友链之前请仔细阅读以下内容。**

## 交换方式

1. Fork 本仓库。
2. 按照格式添加你的站点信息到 `links.yml`。
3. 创建一个 Pull Request 请求合并到本仓库。
4. 等待回复。

## 原则

+ 请按照指定格式申请友链
+ 最好是使用 HTTPS 协议的站点。
+ 不能是无效的链接。
+ 观感良好。比如不能有大量的广告去影响阅读。
+ 至少要有五篇原创文章。
+ 站点不能存在如下内容：
  + 政治敏感的内容
  + 钓鱼链接等恶意链接
  + 病毒木马、挖矿脚本等恶意程序
  + 暴力、恐怖，反动、迷信、恶意攻击他人等内容
  + 在博客分享虐待他人、包养情人、遗弃家庭成员等严重违背社会道德的内容。

申请后可以先不添加本站友链，但必须在申请通过后 15 日内添加本站的友链，否则将取消本次申请，如有特殊情况可以适当延长期限。

## 格式

```
blog: ADD-SP's blog
name: ADD-SP
url: https://www.addesp.com
avatar: https://www.addesp.com/avatar
email: xxx@yyyy.zz
color: "#007bbb"
desc: Hello World!
```

+ `blog`：博客名称（可选，但是`blog`和`name`至少选一个）
+ `name`：怎么称呼（可选，但是`blog`和`name`至少选一个）
+ `url`：博客链接
+ `avatar`：头像图片链接，最好使用 HTTPS（须为正方形或圆形），在保证清晰度的前提下，越小越利于迅速加载展示哦～
+ `color`：喜欢的颜色，将用作友链文字，友链边框以及头像边框的颜色（可选）
+ `email`：联系邮箱，请提供你可以公开的邮箱便于联系（可选）
+ `desc`：简短描述你的站点，太长会被截断（可选）

## 注意事项

+ 本站会不定期检查友链指向的网站，若发现不符合要求则会视情况做出下列三种处理中的一种：
  + 删除友链、不通知站长。
  + 暂时删除友链，如果有站长的联系方式则通知站长，之后是否恢复视情况而定。典型情况是友链指向的网站被挂马。
  + 在本站友链界面进行特殊标记，如果有站长的联系方式则通知站长，之后是否移除标记视情况而定。典型情况是友链暂时无法访问。

## 暂时移除的友链

## 已经移除的友链

+ 博客名：魏巍
+ 博客链接：`https://paperbox.xyz/`
+ 移除时间：2021-01-20
+ 处理日志：
  + 2021-01-20 暂时移除，如果 15 日内没有收到来自被移除站点的消息，将彻底删除此友链。
  + 2021-02-09 因 15 日内未收到来自被移除站点的消息，故彻底移除此友链。
+ 移除原因：链接指向发生改变。

## Commit 格式

本格式在您创建 Pull Request 时无需遵守，只是如果您想阅读本仓库的 Commit 记录，了解一下格式可以帮助理解。

如果友链对增加，修改，标记，暂时移除，彻底移除这几个操作，Commit 的格式见下面。

Commit 格式为：emoji 博客名

+ emoji：emoji 表情，可以是下列取值。
  + :white_check_mark:：表示新增了一个友链。
  + :arrow_up:：表示更新了一个友链的信息。
  + :triangular_flag_on_post:：表示标记或暂时移除了一个友链。
  + :heavy_minus_sign:：表示彻底移除了一个友链。
