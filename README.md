<p align="center">
   <img src="https://img.shields.io/github/v/release/IvanHanloth/php-installer">
<img src="https://img.shields.io/badge/License-MIT-green">
</p>


## 简介
一个用于网站一键安装的程序。
## 环境依赖
PHP 5.6+
## 功能
- 一键保存数据库配置、导入sql文件
- 检查必备运行环境
- 防止重复安装
## 使用方法
- 开发网站前将程序置于网站根目录
- 修改install/index.php中$check、$php_version、$sql_version的值（$check－必需要检查的环境的数量,$php_version－php最低版本限制,$sql_version－sql最低版本限制）
- 修改可能用得到的环境变量并检查
- 修改license.html为用户须知内容、end.html为安装完成后显示的页面内容
## 联系作者
- QQ:1580272392
- Email:ivan@hanloth.com
- Blog:https://ivan.hanloth.cn/
## 更新日志
#### V1.0（更新于2022/5/1）
- php-installer正式上线
