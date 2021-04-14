---
description: 运行 Experience Cloud Debugger
keywords: debugger;experience cloud debugger 扩展程序;chrome;扩展程序;摘要;清除;请求;摘要屏幕;解决方案;信息;analytics;target;dtm;audience manager;launch;id 服务
seo-description: 运行 Experience Cloud Debugger
seo-title: 摘要屏幕
title: 摘要屏幕
uuid: 46b17eaa-b611-43cf-8c6a-67b2e9b9d940
exl-id: 0ee0314b-1611-4581-ae54-2c784e0e56ff
translation-type: ht
source-git-commit: 8672a623442e5a0daa10597a4a93631131221fec
workflow-type: ht
source-wordcount: '1069'
ht-degree: 100%

---

# 摘要屏幕{#summary-screen}

要运行 Adobe Experience Cloud Debugger，请单击扩展栏中的扩展图标，然后在 Chrome 中打开要检查的页面。

![](assets/start-icon.jpg)

此时将显示 Experience Cloud Debugger 的“摘要”屏幕。

![](assets/summary.jpg)

此屏幕中显示该页面的缩略图，以及页面的 URL 和标题。还显示有关每个 Adobe Experience Cloud 解决方案的信息。所显示的信息因解决方案而异，但通常包括的信息有：解决方案库和版本（例如“AppMeasurement v2.9”），以及帐户标识符（例如 Analytics 报表包 ID、Target 客户端代码、Audience Manager 合作伙伴 ID 等）

窗口顶部选项卡旁边的蓝色数字显示已发出的服务器调用数。您可以通过单击相应选项卡中的 **[!UICONTROL Clear All Requests]**，将这些调用重置为零。

例如，下图显示了有关 Adobe Target 的信息。请注意，要在不进行身份验证的情况下显示下图中的活动详细信息，您必须在代码或标签管理器中实施调试事件侦听器，并在 Target UI 中打开必要的[响应令牌](https://docs.adobe.com/content/help/zh-Hans/target/using/administer/response-tokens.html)。

![](assets/summary-target2.jpg)

## 在 Adobe Experience Platform Auditor 中运行审核 {#section-82bc57440406461ebf27a16855b71655}

您可以使用 Plaform Auditor 在页面上运行一系列审核。要运行 Platform Auditor，请单击顶部菜单中的 **[!UICONTROL Auditor]**，然后单击 **[!UICONTROL Audit Page Now]**。要打开 Platform Auditor，请单击 **[!UICONTROL Run Multi-Page Audit Now]**。

## Experience Cloud Debugger 中显示的信息 {#section-88a95ba53dca43d9b96a585e75e5f5cf}

Experience Cloud Debugger 将显示每个解决方案的以下信息：

**页面信息**

<table id="table_FF3B9083524244D29AF350978A0AC236"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>页面屏幕截图 </p> </td> 
   <td colname="col2"> <p>页面缩略图 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>URL </p> </td> 
   <td colname="col2"> <p>页面的 URL </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>标题 </p> </td> 
   <td colname="col2"> <p>在 <span class="codeph">&lt;TITLE&gt;</span> 标记中指定的名称 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Analytics**

<table id="table_BEB9CC58E59D4D86BC895A8A51D84A2C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>报表包 </p> </td> 
   <td colname="col2"> <p><a href="https://docs.adobe.com/content/help/zh-Hans/analytics/admin/manage-report-suites/report-suites-admin.html" format="html" scope="external">报表包</a>可以针对选定的一个网站、一组网站或网页的子集，定义完整、独立的报表 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p>为页面定义的 <a href="https://docs.adobe.com/content/help/zh-Hans/analytics/implementation/js/overview.html" format="html" scope="external">AppMeasurement</a> 版本 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>访客版本 </p> </td> 
   <td colname="col2"> <p><a href="https://docs.adobe.com/content/help/zh-Hans/analytics/technotes/visitor-identification.html" format="html" scope="external">访客 ID</a> 库的版本。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>页面名称 </p> </td> 
   <td colname="col2"> <p>发送到 Analytics 的包含网站用户友好名称的 <a href="https://docs.adobe.com/content/help/zh-Hans/analytics/implementation/vars/page-vars/page-variables.html" format="html" scope="external"> pageName</a> 变量。 </p> </td> 
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
   <td colname="col2"> <p>DIL 实例的<a href="https://docs.adobe.com/content/help/zh-Hans/audience-manager/user-guide/dil-api/dil-instance-methods.html#getpartner" format="html" scope="external">合作伙伴名称</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p>DIL 实例的<a href="https://docs.adobe.com/content/help/zh-Hans/audience-manager/user-guide/api-and-sdk-code/rest-apis/aam-api-dil-methods.html#return-version-dil" format="html" scope="external">版本号</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>UUID </p> </td> 
   <td colname="col2"> <p>与 DIL 实例关联的<a href="https://docs.adobe.com/content/help/zh-Hans/audience-manager/user-guide/reference/ids-in-aam.html" format="html" scope="external">唯一用户 ID</a> </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Experience Platform Launch**

<table id="table_E9574975444A407887E26514D1BB1601"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>名称 </p> </td> 
   <td colname="col2"> <p>Platform Launch <a href="https://docs.adobe.com/content/help/zh-Hans/launch/using/reference/admin/companies-and-properties.html" format="https" scope="external">资产</a>的名称 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p><a href="https://developer.adobelaunch.com/extensions/reference/turbine-free-variable/" format="https" scope="external">Turbine</a> 的版本 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>内部版本发布日期 </p> </td> 
   <td colname="col2"> <p>Platform Launch <a href="https://docs.adobe.com/content/help/zh-Hans/launch/using/reference/publish/libraries.html" format="https" scope="external">库</a>内部版本发布日期 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>环境 </p> </td> 
   <td colname="col2"> <p>Platform Launch 库使用的<a href="https://docs.adobe.com/content/help/zh-Hans/launch/using/reference/publish/environments.html" format="https" scope="external">环境</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>脚本目录 </p> </td> 
   <td colname="col2"> <p>存储 Platform Launch 脚本的目录 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe DTM**

<table id="table_DC76D63FA6EF4891906B9E1D3E4A8A6C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>库名称 </p> </td> 
   <td colname="col2"> <p>Adobe DTM <a href="https://docs.adobe.com/content/help/zh-Hans/dtm/using/library-management.html" format="html" scope="external">库</a>的名称 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p>Turbine 的版本 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>内部版本发布日期 </p> </td> 
   <td colname="col2"> <p>Platform Launch <a href="https://docs.adobe.com/content/help/zh-Hans/dtm/using/library-management.html" format="html" scope="external">库</a>内部版本发布日期 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>环境 </p> </td> 
   <td colname="col2"> <p>DTM 库使用的环境 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>脚本目录 </p> </td> 
   <td colname="col2"> <p>存储 DTM 脚本的目录 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Experience Cloud ID 服务**

<table id="table_274CFCEFA8F34D16BB546B4669EC0209"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Experience Cloud 组织 ID </p> </td> 
   <td colname="col2"> <p>您的<a href="https://docs.adobe.com/content/help/zh-Hans/id-service/using/home.html" format="https" scope="external">组织 ID</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p><a href="https://docs.adobe.com/content/help/zh-Hans/analytics/technotes/visitor-identification.html" format="html" scope="external">访客 ID</a> 库的版本 </p> </td> 
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
   <td colname="col1"> <p>全局 Mbox 名称 </p> </td> 
   <td colname="col2"> <p><a href="https://docs.adobe.com/help/zh-Hans/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external">全局 Mbox</a> 是指在您实施的 Target 中，每个网页顶部发出的单个服务器调用 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Mbox 名称 </p> </td> 
   <td colname="col2"> <p>页面上某个<a href="https://docs.adobe.com/content/help/zh-Hans/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external">位置</a>周围的 mbox 的名称。仅当您在代码或标签管理器中实施调试事件侦听器，并在 Target UI 中打开必要的<a href="https://docs.adobe.com/content/help/zh-Hans/target/using/administer/response-tokens.html" format="html" scope="external">响应令牌</a>时，才能在无需进行身份验证的情况下可用。 </p> </td> 
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
   <td colname="col1"> <p>方法名称 </p> </td> 
   <td colname="col2"> <p>Target <a href="https://docs.adobe.com/content/help/zh-Hans/target/using/experiences/experiences.html" format="html" scope="external">体验</a>的名称。仅当您在代码或标签管理器中实施调试事件侦听器，并在 Target UI 中打开必要的<a href="https://docs.adobe.com/content/help/zh-Hans/target/using/administer/response-tokens.html" format="html" scope="external">响应令牌</a>时，才能在无需进行身份验证的情况下可用。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>方法 ID </p> </td> 
   <td colname="col2"> <p>Target 方法的 ID。仅当您在代码或标签管理器中实施调试事件侦听器，并在 Target UI 中打开必要的<a href="https://docs.adobe.com/content/help/zh-Hans/target/using/administer/response-tokens.html" format="html" scope="external">响应令牌</a>时，才能在无需进行身份验证的情况下可用。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>选件 </p> </td> 
   <td colname="col2"> <p>Target <a href="https://docs.adobe.com/content/help/zh-Hans/target/using/experiences/offers/manage-content.html" format="html" scope="external">选件</a>的名称。仅当您在代码或标签管理器中实施调试事件侦听器，并在 Target UI 中打开必要的<a href="https://docs.adobe.com/content/help/zh-Hans/target/using/administer/response-tokens.html" format="html" scope="external">响应令牌</a>时，才能在无需进行身份验证的情况下可用。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>选件 ID </p> </td> 
   <td colname="col2"> <p>Target 选件的 ID。仅当您在代码或标签管理器中实施调试事件侦听器，并在 Target UI 中打开必要的<a href="https://docs.adobe.com/content/help/zh-Hans/target/using/administer/response-tokens.html" format="html" scope="external">响应令牌</a>时，才能在无需进行身份验证的情况下可用。 </p> </td> 
  </tr> 
 </tbody> 
</table>
