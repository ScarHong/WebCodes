# ver1.0 #
## 完成所有功能 ##

1. 服务器动态生成并发送html，根据浏览器请求发送css文件

2. 根据url中的用户名进入注册/详情页面

3. 注册界面提供`重置/提交`功能

4. 加入包括用户名冲突、数据格式错误等错误信息提醒

5. 扩展功能：

 > · url包含未注册的用户名时注册页面的`用户名`栏固定不可更改，不包含用户名时可以更改
 >
 > · 提供数据库功能，自动读取和保存用户配置到`statics/database.json`

# ver1.1 #
## 一些修复 ##

1. 修复了<del>因为理解错误出现的</del>表单数据检查的报错信息问题

2. 端口号改为8000