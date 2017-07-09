# Drupal 相关资料

### PHP 运行环境的搭建

#### windows平台

下载安装 [wamp](http://www.wampserver.com)，包含了需要的 apache, mysql, php 的一个快速安装包，请自行查阅教程并安装

#### Ubuntu平台：

安装 `lamp`, 参考：http://blog.csdn.net/hanshileiai/article/details/54575176

### Drupal 的安装

**注意!! 项目使用的是 Drupal 7!! 请安装正确的 Drupal 版本**

* [Drupal 官网](https://www.drupal.org/)
* [官方安装教程](https://www.drupal.org/docs/7/install)

具体步骤：

1. 在官网下载 Drupal 7 的安装包，解压到 wamp/lamp server 的 `www/` 文件夹下
2. 开启 wamp/lamp 后浏览器访问 `localhost:80` 即可访问到 Drupal
3. 参考 Drupal 安装教程，首先创建数据库，再访问 `localhost:80` 进行 Drupal 的安装（安装时需要填写数据库名字，填写你创建的数据库名）

### Drupal 基本概念的学习

请先浏览 [官方文档](https://www.drupal.org/docs/7) 理解 Drupal 的运作过程, 如 `node`, `permission` 的概念

建议一边阅读一边尝试操作

#### 要掌握的内容

1. 基本操作的学习
    * 添加删除 `menu`
    * 添加删除 `block`
    * 添加删除 `content type`
    * 添加删除 `node`
    * 将一个 `block` 显示在主界面上
    * 添加删除模块 `module`
2. `views` 模块
    * 安装 `views` 模块
    * 添加一个 view，类型是 `page`（思考：page 和 block 的区别？），专门显示某个 `content type` 的内容（用你自己创建的 `content type` 试试）
    * 添加显示的 field，自己决定显示什么 field
    * 了解 `filter` 的作用
    * 控制排序顺序 - 根据 field 进行排序
