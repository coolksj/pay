#  pay第三方支付系统，自带监控软件和后台管理系统+商户后台管理系统
## 全新开发的第三方支付系统源码，自带软件监控。对接支付宝，后续将会陆续添加更多特性。
## 下载:
* 蓝奏云下载: [点我下载](https://fusong.lanzous.com/b01c5m8aj
)密码:felk 
## 介绍:
* 前端利用vue开发，
* 后端利用thinkphp开发
## 文档说明:
### 体验:http://103.152.170.170:8088/demo/counter1.php
## 系统搭建使用方法:
* 解压放入网站目录下访问域名即可(如果需要全新安装只需要删除/public/install 目录下的install.lock和config.db.php文件即可)
## 商户对接方法:
* 下载监控软件
* 到官网注册申请商户信息
* 填写商户信息到软件启动运行
* 下载集成SDK包集成到自己的网站(看开发文档)
## 注意事项:
* 软件一定要给予通知栏权限！！(否则无法监控)，自启动，以防被杀死
* 支付宝语音一定要打开，保证能正常播报,授予微信消息通知权限
* 软件监控订单日志文件在sd卡目录下的payLog.txt文件
## 项目目录结构:

### 核心后端源码接口:
* api.php:网页端请求接口
* corn.php:监控软件端请求接口
* db.sql:创建数据库文件(导入即可)
* payCorn.php:网页端付款状态循环请求状态接口
* notifaction.php 支付成功支付回调处理文件
### 支付界面截图:
[![DkpxF1.jpg](https://s3.ax1x.com/2020/11/16/DkpxF1.jpg)](https://imgchr.com/i/DkpxF1)
### 后台管理系统截图:
[![69C2DK.jpg](https://s3.ax1x.com/2021/02/27/69C2DK.jpg)](https://imgtu.com/i/69C2DK)
### 商户后台系统截图:
[![69C2DK.jpg](https://s3.ax1x.com/2021/02/27/69C2DK.jpg)](https://imgtu.com/i/69C2DK)
## 对接开发文档:
* 开发中
# 日志:
## 2020-12-14 全新改版！功能全部实现。
## 2020-12-15 修复监控bug，添加跳转到支付宝app，修复监控安全问题，强制更新！
## 2021-1-11  添加支付成功提示
## 2021-1-13  添加监听微信支付和qq支付(暂时监听功能不可用)
## 2020-1-14  添加集成SDK包，全新SDK版支付系统重构
## 捐赠:
[捐赠](http://103.152.170.170:8088/demo/counter1.php)
