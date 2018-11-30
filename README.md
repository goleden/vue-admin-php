# 前言

**项目前端地址：** <a href="https://github.com/goleden/vue-admin-html" target="_blank">https://github.com/goleden/vue-admin-html</a>

**项目后端地址：** <a href="https://github.com/goleden/vue-admin-php" target="_blank">https://github.com/goleden/vue-admin-php</a>

# 欢迎 star

# vue-admin-php

> Vue-cli3.0 + Element UI + ThinkPHP5.1 + RBAC权限 + 响应式的后台管理系统

# 一键操作包 

1. 环境搭建，略
2. 把两个文件放到网站根目录
3. 把MySQL的root密码改为 root, 再新建数据库 vue-admin ,再把vue-admin.sql 文件导入到MySQL
4. 打开浏览器 输入 http://localhost/vue-admin-html/dist/index.html

## 功能 ##
- [x] 管理员登录
- [x] 登录
- [x] 修改密码
- [x] 角色管理
- [x] 权限管理
- [x] 401/404错误页面
- [x] 动态面包屑
- [x] 动态侧边栏
- [x] 广告管理


## 安装步骤 ##

	git clone https://github.com/goleden/vue-admin-php.git      // 把模板下载到本地
	cd vue-admin-php    // 进入模板目录
	composer install         // 安装项目依赖，等待安装完成之后

## 一些注意点 ##
1. 用的是 tp5.1 版本，具体文档 <a href="https://www.kancloud.cn/manual/thinkphp5_1/353946">点击查看</a>
2. 安装好后请把 composer.json 里面的 "topthink/framework": "5.1.*"  * 号 改成具体的某个版本


