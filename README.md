# 简介

种子数据来源：[Pirate Library Mirror](http://pilimi.org/zlib-downloads.html)

教程相关文件：https://wwk.lanzoue.com/b04j92b8j 密码：h4l3

# 教程

## 安装 MySQL

下载`MySQL 8.0.29 x64 for Windows 精简便携版`（Linux、Mac 略）并解压，右键`install.bat`以管理员身份运行。

下次启动、停止在服务中操作。

![](https://user-images.githubusercontent.com/14957667/200196770-3f2e5453-baa7-4208-9679-f9c3df906f82.png)

## 创建数据库导入数据

下载 Navicat、DBeaver 等数据库工具，此处以 [Navicat](http://www.navicat.com.cn/download/navicat-for-mysql) 为例。

我的连接右键，新建连接 - MySQL。

![](https://user-images.githubusercontent.com/14957667/200216038-81e352a3-9ab9-4e7c-8e9b-023f1f32a92c.png)

按照图示填写，测试连接显示“连接成功”后确定保存连接。

![](https://user-images.githubusercontent.com/14957667/200216285-6a69d899-3d69-4d08-8522-886c559e0392.png)

双击新建的连接后，右键“新建数据库”。

![](https://user-images.githubusercontent.com/14957667/200227474-a19fd8af-d110-4b45-b792-5ee97ae00c75.png)

需要导入的数据分别在`pilimi-zlib-index-2022-06-28.torrent`、`pilimi-zlib2-index-2022-08-24-fixed.torrent`中，下载解压得到`pilimi-zlib-index-2022-06-28.sql`、`pilimi-zlib2-index-2022-08-24-fixed.sql`。

双击新建的数据库后，右键运行 SQL 文件等待完成（大概半小时），将以上两个 SQL 文件都导入到数据库。需要注意要**取消勾选**“在每个运行中运行多个查询”的选项，否则会报错。

![](https://user-images.githubusercontent.com/14957667/200219686-f47444a1-b1f5-4fbd-926f-7f8e8e3a00a5.png)

## 安装 qBittorrent 设置 Web UI

下载地址：[qBittorrent download latest version](https://www.fosshub.com/qBittorrent.html)，

安装后设置打开 Web UI，并设置密码：

![](https://user-images.githubusercontent.com/14957667/200759344-52c9315e-4c0d-454b-bd83-05f77446e227.png)

下载安装`qbittorrent-cli-……-x64.msi`，Linux、Mac 用户从这下载：[Releases・fedarovich/qbittorrent-cli](https://github.com/fedarovich/qbittorrent-cli/releases)

## 下载本程序运行



……
