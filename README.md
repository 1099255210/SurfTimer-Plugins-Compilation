# SurfTimer 插件合集

## 简介

本文档整理了搭建一个滑翔服务器所需要的插件，仅供学习与参考。其中的插件本人并未参与开发。

## 插件列表

- SurfTimer (滑翔主插件)
- discord_api (滑翔附属插件)
- MovementHUD (更专业地显示速度与按键的插件)
- csgo_movement_unlocker (允许prestrafe的插件)
- nightvision (夜视插件)

## 必要依赖

- DHooks
- SMJansson
- SteamWorks

## 安装方法

1. 将文件粘贴到服务器中

2. 配置`addons/sourcemod/configs/databases.cfg`在其中加入：

   ```
   "surftimer"
   {
   	"driver"			"mysql"
   	"host"				"127.0.0.1"
   	"database"			"surftimer"
   	"user"				""              //填入用户名
   	"pass"				""              //填入对应的密码
   	//"timeout"			"0"
   	//"port"			"0"
   }
   ```

3. 在mysql中创建一个名为`surftimer`的数据库即可
