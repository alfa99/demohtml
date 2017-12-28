但是这种个人展示页，或网站展示页只能建一个，地址为 http://jsonshare.github.io

 

总结引用：

两种pages模式
1. User/Organization Pages 个人或公司站点
1) 使用自己的用户名，每个用户名下面只能建立一个
2) 资源命名必须符合这样的规则username/username.github.io或者username/username.github.com
3) 主干上内容被用来构建和发布页面
2. Project Pages 项目站点
1) gh-pages分支用于构建和发布；
2) 如果user/org pages使用了独立域名，那么托管在账户下的所有project pages将使用相同的域名进行重定向，除非project pages使用了自己的独立域名；
3) 如果没有使用独立域名，project pages将通过子路径的形式提供服务username.github.io/projectname；
4) 自定义404页面只能在独立域名下使用，否则会使用User Pages 404；
