# blog
### 本blog使用hexo平台，next主题，依托github pages

使用说明：
* checkout该项目
* 安装Node.js
* 执行"npm install"安装相关模块

部署说明：
* 在github中开启github pages
* 在该项目中配置github pages地址

绑定域名：
* 申请域名并将cname指向github pages
* 配置该项目中/source/CNAME，内容为域名地址

本地域名：http://localhost:4000  
github域名：https://jairliu.github.io

hexo常用命令：
* 新建blog：hexo new "new blog"(然后在source/_posts中编辑新文章)
* 清缓存：hexo clean
* 启动服务：hexo s
* 生成静态文件：hexo g
* 部署到github：hexo g -d