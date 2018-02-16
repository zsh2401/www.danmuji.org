---
# hide: true
title: 礼物统计
auther: Executor丶
plugin_author: Executor丶
plugin_name: 礼物统计
plugin_desc: 统计收到的礼物,可存为文本供直播软件使用
plugin_version: 1.0.0
plugin_update_datetime: 2018-02-11 12:50:02 +0800
plugin_update_desc: |-

plugin_dllink: /resource/GiftStatistics/GiftStatistics.zip
plugin_dlnote: 只在弹幕姬官网及论坛提供下载,请勿转载
---

若插件有任何问题，亦或对插件有建议，请发邮件至 847529602@qq.com

**※本插件依赖.NET Framework 4.6.2框架,若你的计算机中缺少此框架,可能会导致插件无法正常工作※**

插件界面
---
<img class="shadow" src="https://www.danmuji.org/resource/GiftStatistics/preview.png" alt="插件界面" />

插件功能
---
- 统计收到的礼物
- 输出文本到插件目录下
- 支持从当前弹幕姬连接的直播间的许愿瓶导入礼物

安装方法
---
下载文件，解压后直接放进 `我的文档\弹幕姬\plugins\` 重启弹幕姬即可。

使用说明
---
第一次运行时会创建目录 `我的文档\弹幕姬\plugins\礼物统计\` 。

本插件所有功能均在管理页面中，移步至 **插件** 选项卡并右键本插件，点击 **管理** 即可。

在“礼物配置”窗口中，“显示的字符串”即插件向文本输出的内容。支持以下变量
-%name% 礼物名称(如果填了“自定义显示名称”则显示“自定义显示名称”)
-%count% 已统计的个数
-%tcount% 目标个数

举个例子：“显示的字符串”中填写“我的小目标:%name%:%count%/%tcount%”
插件会输出为“我的小目标:辣条:1/100”

在主界面中的“全局输出”，使用“%礼物名称%”来表示指定礼物的输出（适用于多个礼物输出在一个文件中的情况）
举个例子: “我的所有小目标:%辣条%;%亿圆%”
插件会输出为“我的所有小目标:辣条:1/100亿圆:1/100”

**支持换行**; 如果还有不懂，可以在弹幕姬群内找847529602

更新日志
---
- 2018-02-11 12:50:02 初版发布