---
description: 'null'
keywords: debugger;experience cloud debugger extension;chrome;extension;summary;clear;requests;summary screen;solution;information;analytics;target;dtm;audience manager;launch;id service
seo-description: 'null'
seo-title: 摘要屏幕
title: 摘要屏幕
uuid: 46b17eaa-b611-43cf-8c6a-67b2e9b9d940
translation-type: tm+mt
source-git-commit: f35d87473f9e1e26f9a27272d7930472cc01c188
workflow-type: tm+mt
source-wordcount: '940'
ht-degree: 100%

---


# 摘要屏幕{#summary-screen}

>[!IMPORTANT]
>
>Adobe Experience Cloud Debugger 2.0 目前为 Beta 版。文档和功能可能会发生变化。

要运行 Adobe Experience Platform Debugger，请单击浏览器栏上的图标，然后打开要在浏览器中检查的页面。

![](assets/start-icon.jpg)

此时将显示 Adobe Experience Platform Debugger 的“摘要”屏幕。

![](assets/summary.jpg)

这个屏幕可显示有关每个 Adobe Experience Cloud 解决方案的信息。所显示的信息因解决方案而异，但通常包括的信息有：解决方案库和版本（例如“AppMeasurement v2.9”），以及帐户标识符（例如 Analytics 报表包 ID、Target 客户端代码、Audience Manager 合作伙伴 ID 等）

## Debugger 中显示的信息

Debugger 将显示每个解决方案的以下信息：

**Adobe Analytics**

<table id="table_BEB9CC58E59D4D86BC895A8A51D84A2C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>报表包 </p> </td> 
   <td colname="col2"> <p><a href="https://experiencecloud.adobe.com/resources/help/zh_CN/reference/report_suites_admin.html" format="html" scope="external">报表包</a>可以针对选定的一个网站、一组网站或网页的子集，定义完整、独立的报表 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p>为页面定义的 <a href="https://experiencecloud.adobe.com/resources/help/zh_CN/sc/implement/appmeasure_mjs.html" format="html" scope="external">AppMeasurement</a> 版本 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>访客版本 </p> </td> 
   <td colname="col2"> <p><a href="https://experiencecloud.adobe.com/resources/help/zh_CN/sc/implement/visid_analytics.html" format="html" scope="external">访客 ID</a> 库的版本。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>页面名称 </p> </td> 
   <td colname="col2"> <p>发送到 Analytics 的包含网站用户友好名称的 <a href="https://experiencecloud.adobe.com/resources/help/zh_CN/sc/implement/pageName.html" format="html" scope="external"> pageName</a> 变量。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>模块 </p> </td> 
   <td colname="col2"> <p>Adobe Analytics 加载的模块 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Audience Manager**

<table id="table_784AEABADBDA4D14BB9A7A9CB9EF07C3"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>合作伙伴 </p> </td> 
   <td colname="col2"> <p>DIL 实例的<a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_dil_get_partner.html" format="html" scope="external">合作伙伴名称</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p>DIL 实例的<a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_api_return_versions_dil.html" format="html" scope="external">版本号</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>UUID </p> </td> 
   <td colname="col2"> <p>与 DIL 实例关联的<a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/ids-in-aam.html" format="html" scope="external">唯一用户 ID</a> </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Launch**

<table id="table_E9574975444A407887E26514D1BB1601"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>名称 </p> </td> 
   <td colname="col2"> <p>Adobe Launch <a href="https://docs.adobe.com/content/help/zh-Hans/launch/using/reference/admin/companies-and-properties.html" format="https" scope="external">属性</a>的名称 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p>Turbine 的版本</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>内部版本发布日期 </p> </td> 
   <td colname="col2"> <p>Launch <a href="https://docs.adobe.com/content/help/zh-Hans/launch/using/reference/publish/libraries.html" format="https" scope="external">库</a>的内部版本发布日期 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>环境 </p> </td> 
   <td colname="col2"> <p>Launch 库使用的<a href="https://docs.adobe.com/content/help/zh-Hans/launch/using/reference/publish/environments.html" format="https" scope="external">环境</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>扩展 </p> </td> 
   <td colname="col2"> <p>页面上使用的扩展 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Web SDK**

<table id="table_DC76D63FA6EF4891906B9E1D3E4A8A6C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>库版本 </p> </td> 
   <td colname="col2"> <p>AEB Web SDK <a href="https://docs.adobe.com/content/help/zh-Hans/launch/using/extensions-ref/adobe-extension/aep-extension/overview.html" format="html" scope="external">库版本</a>的编号 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>命名空间</p> </td> 
   <td colname="col2"> <p>扩展中标识的名称</p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>属性 ID </p> </td> 
   <td colname="col2"> <p>扩展中指定的 Launch 属性的名称 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>边缘域 </p> </td> 
   <td colname="col2"> <p>Adobe Experience Platform 扩展发送和接收数据的域 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>IMS 组织 ID </p> </td> 
   <td colname="col2"> <p>您希望将数据发送到的 Adobe 组织（在扩展中指定） </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>已启用日志记录 </p> </td> 
   <td colname="col2"> <p>指定是否已为此属性启用日志记录</p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Experience Cloud ID 服务**

<table id="table_274CFCEFA8F34D16BB546B4669EC0209"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Experience Cloud 组织 ID </p> </td> 
   <td colname="col2"> <p>您的<a href="https://experiencecloud.adobe.com/resources/help/zh_CN/mcvid/" format="https" scope="external">组织 ID</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p><a href="https://experiencecloud.adobe.com/resources/help/zh_CN/sc/implement/visid_analytics.html" format="html" scope="external">访客 ID</a> 库的版本 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Target**

<table id="table_D30E0CD20FB04E41862B22655136E043"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>客户端代码 </p> </td> 
   <td colname="col2"> <p>您的 Target <a href="https://docs.adobe.com/content/help/zh-Hans/target/using/implement-target/client-side/deploy-at-js/implementing-target-without-a-tag-manager.html" format="html" scope="external">客户端代码</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p>您当前的 <a href="https://docs.adobe.com/content/help/zh-Hans/target/using/implement-target/client-side/target-atjs-versions.html" format="html" scope="external">at.js</a> 或 mbox.js 版本 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>全局请求名称 </p> </td> 
   <td colname="col2"> <p><a href="https://docs.adobe.com/help/zh-Hans/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external">全局 Mbox</a> 是指在您实施的 Target 中，每个网页顶部发出的单个服务器调用 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>页面加载事件 </p> </td> 
   <td colname="col2"> <p>页面加载时触发的<a href="https://docs.adobe.com/content/help/zh-Hans/launch/using/extensions-ref/adobe-extension/target-extension/overview.html" format="html" scope="external">事件</a>类型 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>请求名称 </p> </td> 
   <td colname="col2"> <p>页面上某个<a href="https://docs.adobe.com/content/help/zh-Hans/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external">位置</a>周围的请求名称。仅当您在代码或标签管理器中实施调试事件侦听器，并在 Target UI 中打开必要的<a href="https://docs.adobe.com/content/help/zh-Hans/target/using/administer/response-tokens.html" format="html" scope="external">响应令牌</a>时，才能在无需进行身份验证的情况下可用。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>活动名称 </p> </td> 
   <td colname="col2"> <p>Target <a href="https://docs.adobe.com/content/help/zh-Hans/target/using/activities/activities.html" format="html" scope="external">营销活动或活动</a>的名称。仅当您在代码或标签管理器中实施调试事件侦听器，并在 Target UI 中打开必要的<a href="https://docs.adobe.com/content/help/zh-Hans/target/using/administer/response-tokens.html" format="html" scope="external">响应令牌</a>时，才能在无需进行身份验证的情况下可用。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>活动 ID </p> </td> 
   <td colname="col2"> <p>Target 活动的 ID。仅当您在代码或标签管理器中实施调试事件侦听器，并在 Target UI 中打开必要的<a href="https://docs.adobe.com/content/help/zh-Hans/target/using/administer/response-tokens.html" format="html" scope="external">响应令牌</a>时，才能在无需进行身份验证的情况下可用。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>体验名称 </p> </td> 
   <td colname="col2"> <p>Target <a href="https://docs.adobe.com/content/help/zh-Hans/target/using/experiences/experiences.html" format="html" scope="external">体验</a>的名称。仅当您在代码或标签管理器中实施调试事件侦听器，并在 Target UI 中打开必要的<a href="https://docs.adobe.com/content/help/zh-Hans/target/using/administer/response-tokens.html" format="html" scope="external">响应令牌</a>时，才能在无需进行身份验证的情况下可用。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>体验 ID </p> </td> 
   <td colname="col2"> <p>Target 体验的 ID。仅当您在代码或标签管理器中实施调试事件侦听器，并在 Target UI 中打开必要的<a href="https://docs.adobe.com/content/help/zh-Hans/target/using/administer/response-tokens.html" format="html" scope="external">响应令牌</a>时，才能在无需进行身份验证的情况下可用。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>选件名称</p> </td> 
   <td colname="col2"> <p>Target <a href="https://docs.adobe.com/content/help/zh-Hans/target/using/experiences/offers/manage-content.html" format="html" scope="external">选件</a>的名称。仅当您在代码或标签管理器中实施调试事件侦听器，并在 Target UI 中打开必要的<a href="https://docs.adobe.com/content/help/zh-Hans/target/using/administer/response-tokens.html" format="html" scope="external">响应令牌</a>时，才能在无需进行身份验证的情况下可用。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>选件 ID </p> </td> 
   <td colname="col2"> <p>Target 选件的 ID。仅当您在代码或标签管理器中实施调试事件侦听器，并在 Target UI 中打开必要的<a href="https://docs.adobe.com/content/help/zh-Hans/target/using/administer/response-tokens.html" format="html" scope="external">响应令牌</a>时，才能在无需进行身份验证的情况下可用。 </p> </td> 
  </tr> 
 </tbody> 
</table>

