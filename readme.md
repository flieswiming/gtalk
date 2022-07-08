Gitalk
Gitalk，一个基于 Github Issue 和 Preact 开发的评论插件。

详情查看：

https://github.com/gitalk/gitalk
https://gitalk.github.io/
在 Keep 中如何使用：

新建 GitHub OAuth App
注册或登录 GitHub (opens new window)，创建新的 OAuth App (opens new window)，其中 Homepage URL 和 Authorization callback URL 均填写自己的域名即可。

OAuth App 创建成功后，把 Client ID 和 Client Secret 保存起来，下面要用到。

image

新建 GitHub 仓库 注册或登录 GitHub (opens new window)，创建一个新的仓库（repository） (opens new window)，并打开 Issues（自己手动增加一个 Issue，内容随便填写，即可打开），用于存储评论内容。

把自己的 GitHub 用户名、仓库名 、OAuth App 的 Client ID 、Client Secret 分别填写在主题配置文件里，如下示例。

gitalk:
  github_id: XPoet
  repository: hexo-site-comments
  client_id: cdfffffffffffffffffffff
  client_secret: f4b55555555555555555555555555555
  [配置参考](https://keep-docs.xpoet.cn/usage-tutorial/configuration-guide.html#comment)
