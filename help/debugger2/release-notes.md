---
description: Experience Platform Debugger 发行说明
keywords: debugger;experience Platform Debugger 扩展程序;chrome;扩展程序;发行说明
seo-description: Experience Platform Debugger release notes
seo-title: Release Notes
title: 发行说明
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
exl-id: 3eed44da-5f85-413e-a783-3a0df03a2baf
source-git-commit: 026ce852ded530e89f36bb01274d7481e07731c0
workflow-type: tm+mt
source-wordcount: '234'
ht-degree: 14%

---

# 发行说明{#release-notes}

## 发行说明 {#topic-a92c3eb799b74e7fa404af8af5efb215}

## 1.2.0版 — 2021年10月26日

## 新增功能

<table id="table">
 <thead>
  <tr>
   <th colname="col1" class="entry"> 功能 </th>
   <th colname="col2" class="entry"> 描述 </th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td colname="col1"> <p> 在“网络”视图中，所有浏览器选项卡中的事件都可见 </p> </td>
   <td colname="col2"> <p> 在“网络”视图中显示所有浏览器选项卡中的事件。 要仅查看当前选项卡中的事件，请单击Debugger右下角的锁图标。</p> </td>
  </tr>
  <tr>
   <td colname="col1"> <p> 品牌变更 </p> </td>
   <td colname="col2"> <p> AEP Web SDK将变为Adobe Experience Platform Web SDK，而Launch将变为Adobe Experience Platform标记。</p> </td>
  </tr>
 </tbody>
</table>

## 1.1.0版 — 2021年10月5日

## 新增功能

<table id="table">
 <thead>
  <tr>
   <th colname="col1" class="entry"> 功能 </th>
   <th colname="col2" class="entry"> 描述 </th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td colname="col1"> <p> 远程调试可视化 </p> </td>
   <td colname="col2"> <p> 在Adobe Experience Platform Web SDK &gt;边缘事务部分中，将远程调试事件组织到可视流程图中。 此外，在启动新的远程调试会话时，还需要在页面上使用Adobe Experience Platform Web SDK IMS组织来匹配已登录的组织。 通过连接的选项卡过滤边缘事务。</p> <p> <b>注意：</b> Target跟踪日志仍在“日志”&gt;“Edge”部分中可用。</p> </td>
  </tr>
  <tr>
   <td colname="col1"> <p> Adobe Experience Platform Web SDK配置部分改进 </p> </td>
   <td colname="col2"> <p> 允许为页面上的每个实例分别进行单独的数据流ID配置覆盖。 添加已启用调试的切换开关。</p> </td>
  </tr>
 </tbody>
</table>

## 错误修复

* 修复了Adobe Target跟踪令牌并非总是随Adobe Experience Platform Web SDK的远程调试会话一起发送的问题。

## 1.0.0版 — 2021年5月5日

## 新增功能

<table id="table_7EFCAF456B14404FAF3715FC56519AAF">
 <thead>
  <tr>
   <th colname="col1" class="entry"> 功能 </th>
   <th colname="col2" class="entry"> 描述 </th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td colname="col1"> <p> 初始版本 </p> </td>
   <td colname="col2"> <p> Debugger的第一个主要版本。 用于替换Experience Cloud Debugger。 </p> </td>
  </tr>
 </tbody>
</table>
