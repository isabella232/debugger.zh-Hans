---
description: 'null'
keywords: 调试器；Experience Cloud调试器扩展；chrome；扩展；工具；dtm；目标
seo-description: 'null'
seo-title: 工具
title: 工具
uuid: ea3fe1ea-e936-4c5a-8a43-b830d1b75038
translation-type: tm+mt
source-git-commit: 3fd50cde86f0dfc5f66d8faf63112adf24beeac0

---


# 工具{#tools}

在“工具”屏幕上，您可以为已安装的解决方案启用或禁用各种工具。 例如，您可以打开Target的控制台调试语句或使用DTM暂存库。 这些工具仅在页面上安装了Target和DTM时可用。

![](assets/tools.jpg)

您可以在任何页面上动态插入启动项或DTM，以在未安装启动项或DTM的页面上测试某些内容。 单击“嵌 **[!UICONTROL 入代码]** ”图标，然后键入嵌 [入代码](https://experiencecloud.adobe.com/resources/help/en_US/dtm/deployment.html) ，然后单击“ **[!UICONTROL 保存]**”。

![](assets/tools-embedcode.jpg)

## DTM信息 {#section-c3d43040440449e5a050170843a600b7}

<table id="table_04625C3319134E169A35DB74C1D1FB31"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 工具 </th> 
   <th colname="col2" class="entry"> 描述 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p> DTM控制台日志记录 </p> </td> 
   <td colname="col2"> <p>此工具向浏览器控制台公开特定于DTM的调试语句。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>使用暂存库 </p> </td> 
   <td colname="col2"> <p>此工具使用暂存库获取DTM调试信息。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>禁用DTM </p> </td> 
   <td colname="col2"> <p>此工具阻止检查DTM信息。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> 动态插入DTM </p> </td> 
   <td colname="col2"> <p> 此工具可在页面上插入DTM代码。 使用嵌入代码编辑器编辑已插入的代码。 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 目标信息 {#section-31090d95f50e455692b672c26e6a2051}

<table id="table_A71D269B49F4417599EBACA44D5CCF4F"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 工具 </th> 
   <th colname="col2" class="entry"> 描述 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>目标控制台日志记录 </p> </td> 
   <td colname="col2"> <p><span class="codeph"> 此工具向浏览器控制台显示特定于Target的调试语句，所有语句都以 </span> AT开头：前缀，方法是将名为mboxDebug=true的 <span class="codeph"> cookie添加到您的浏览器</span> 。 此时，控制台语句不显示在“调试器日志”屏幕中，但在浏览器的本机调试控制台中可见。 </p> <p> 此工具需要at.js 0.9.6+。 如果您使用的是旧版at.js，则可以向URL添加 <span class="codeph"> ?mboxDebug=true</span> query字符串参数以打开控制台日志记录。 如果您使用mbox.js，则可以添加 <span class="codeph"> ?_AT_Debug=console</span> 参数，以打开仅限于Visual Experience Composer活动的控制台日志记录。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> 启用Mbox跟踪 </p> </td> 
   <td colname="col2"> <p>此工具向Target响应添加详细信息，可在调试器的“ <span class="uicontrol"> Target”&gt;“Mbox跟踪</span> ”屏幕中查看。 </p> <p> 您必须登录到Chrome选项卡之一的Experience Cloud才能启用此工具。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>禁用目标 </p> </td> 
   <td colname="col2"> <p>此工具通过向浏览器添加一个名为mboxDisable=true的 <span class="codeph"> cookie来禁用所有Target请求</span> 。 </p> <p> 此工具需要at.js 0.9.6+。 如果您使用的是旧版本，则可以将？mboxDisable=true <span class="codeph"> 查询字符串 </span>参数添加到您的URL以禁用mbox。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Mbox高亮显示 </p> </td> 
   <td colname="col2"> <p> 此工具在旧式包装样式的mbox周围绘制一个红色框。 </p> </td> 
  </tr> 
 </tbody> 
</table>

以下视频介绍如何将调试器扩展与Adobe Target结合使用。

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/?captions=chi_hans)
