# Tule论坛系统
第二次开发重构了一些功能:

用`gem 'devise'`重构了用户注册系统

用`gem 'cancan'`重构了权限管理功能

添加了`管理员后台管理`页面，`admin/index`

可以增加删除更新`节点`和`帖子`

# 实现的功能：

1、注册、登录、登出：

`gem 'devise'`

2、权限控制：

`gem 'cancan'`

3、图片上传：

`gem 'paperclip'`

4、用户回复：

`controller/reverts`

5、帖子相关操作：

`controller/posts`

6、节点控制：

`controller/nodes`

