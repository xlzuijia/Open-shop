# Open-shop是一套完全开源的微信小程序商场系统
当前版本:1.0.1 <br/>
官方网站：http://www.51app.ink/<br/>
QQ交流群号：877611106 <br/>
很多人想找一套真正完全开源的微信小程序商城而找不到，现在我们团队经过整合码云开源代码后重磅对出此套完全开源程序。希望大家可以支持我们，我们会不断完善代码和推出新功能来让大家更好的使用。

# 特点 
* 免费完整开源：基于MIT协议，源代码完全开源，无商业限制,51工作室开发团队承诺将系统永久完整开源；<br/>
* 无BUG：经过严格测试，开箱即用；<br/>
* 编码优雅：代码结构清晰,注解非常详细，方便小伙伴们学习和使用。；<br/>
* 持久更新：会定期公布开发计划。并按计划提交新的功能；<br/>
* 活跃的社群：官方QQ群有专人回复，及时耐心的解答问题；<br/>

# 面向对象
* Open-Shop是企业在创立初期很好的技术基础框架，加快公司项目开发进度，当然也可以对现有的系统进行升级；
* 个人开发者也可以使用Open-Shop承接外包项目；
* 初学JAVA的同学可以下载源代码来进行学习交流；

# 技术框架
* 核心框架：Spring Framework 4
* 安全框架：Apache Shiro 1.2
* 视图框架：Spring MVC 4
* 持久层框架：MyBatis 3
* 数据库连接池：Alibaba Druid 1.0
* 日志管理：SLF4J 1.7、Log4j
* JS框架：Vue 2.5.1，iview，layer 3.0.3，jquery 2.2.4，jqgrid 5.1.1 
* CSS框架：Twitter bootstrap3.3.7。
* 富文本：froala_editor1.2.2

# 开发环境
建议开发者使用以下环境，这样避免版本带来的问题
* IDE:eclipse
* DB:Mysql5.8
* JDK:JAVA8
* WEB:Tomcat8

# 运行环境
* WEB服务器：Weblogic、Tomcat、WebSphere、JBoss、Jetty 等
* 数据库服务器：Mysql5.8
* 操作系统：Windows、Linux、Unix 等


# 快速体验
* 将Open-Shop项目源码通过maven形式导入eclipse；
* 导入Open-Shop.sql数据文件,注意：数据库使用utf-8编码； 
* 修改platform-admin/platform.properties文件中的数据库设置参数；
* tomcat中加载platform-framework项目
* 访问后台地址：http://ip|域名/项目发布名/
* 管理员账号，用户名：默认 密码：默认

# 小程序部署：
* 打开小程序工具；
* 选择你下载的源代码wx-mall小程序项目；
* 输入你的AppID；
* 填写你的项目名称；
* 进入之后修改config文件夹里的api.js文件，把NewApiRootUrl改为你后台接口地址即刻运行。

# 小程序演示效果
![](http://pgf1db9j6.bkt.clouddn.com/6.jpg "前段演示")

# 后端登录界面
![登录界面](http://pgf1db9j6.bkt.clouddn.com/login.jpeg "登录，小程序商城")
# 主界面
![主界面](http://pgf1db9j6.bkt.clouddn.com/main.jpeg "主界面，插件商城")
# 菜单
![菜单](http://pgf1db9j6.bkt.clouddn.com/menu.png "菜单1")