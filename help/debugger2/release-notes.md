---
title: 发行说明
description: Adobe Experience Platform Debugger 的最新发行说明。
keywords: debugger;experience Platform Debugger 扩展程序;chrome;扩展程序;发行说明
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
exl-id: 3eed44da-5f85-413e-a783-3a0df03a2baf
source-git-commit: a442fa56589003dad4ca9896ef601349fb93d280
workflow-type: tm+mt
source-wordcount: '287'
ht-degree: 7%

---

# 发行说明

## 1.3.0版 — 2022年1月28日

* 添加了显示当前发行版本和说明的“关于”链接。
* 添加了用于查看Analytics请求的后处理点击的切换功能。 Analytics部分中提供了切换开关。
* 修复了会话在调试器外关闭时的远程调试会话问题。
* 修复了Web SDK Edge Transactions选项卡中显示的错误通知。
* 修复了Debugger访问_satellite对象时页面上的Adobe标记弃用警告。
* 修复了在页面上找不到AppMeasurement实例的一些情况。
* 修复了首次打开调试器窗口时发生的页面连接问题。

## 版本1.2.0 - 2021年10月26日

* 在网络视图中显示所有浏览器选项卡中的事件。 要仅查看当前选项卡中的事件，请选择Debugger右下角的锁图标。
* 更新了品牌。

## 版本1.1.0 - 2021年10月5日

* 远程调试可视化图表 — 在Adobe Experience Platform Web SDK > Edge Transactions部分将远程调试事件组织为可视化流程图。
* 在启动新的远程调试会话时，需要页面上使用的Adobe Experience Platform Web SDK IMS组织匹配登录组织。
* 仅显示已连接选项卡的边缘事务。 Target跟踪日志仍在“日志”>“边缘”部分中可用。
* 允许为页面上的每个Adobe Experience Platform Web SDK实例覆盖单独的数据流ID配置。 “添加调试已启用”切换开关。
* 修复了Adobe Target跟踪令牌未始终随Adobe Experience Platform Web SDK的远程调试会话一起发送的问题。

## 1.0.0版 — 2021年5月5日

* Experience PlatformDebugger的第一个主要版本。 旨在更换Experience Cloud Debugger。
