---
description: 'null'
keywords: 调试器；Experience Cloud调试器扩展；chrome；扩展；摘要；清除；请求；摘要屏幕；解决方案；信息；分析；目标；dtm;audience Manager；启动；id服务
seo-description: 'null'
seo-title: 摘要屏幕
title: 摘要屏幕
uuid: 46b17eaa-b611-43cf-8c6a-67b2e9b9d940
translation-type: tm+mt
source-git-commit: 3fd50cde86f0dfc5f66d8faf63112adf24beeac0

---


# 摘要屏幕{#summary-screen}

要运行Experience cloud调试器，请单击扩展栏中的扩展图标，然后在Chrome中打开要检查的页面。

![](assets/start-icon.jpg)

出现Adobe Experience cloud调试器摘要屏幕。

![](assets/summary.jpg)

此屏幕显示页面的缩略图，以及页面的URL和标题。 它还显示有关每个Adobe Experience cloud解决方案的信息。 显示的信息因解决方案而异，但通常包括解决方案库和版本（例如，“AppMeasurement v2.9”）以及帐户标识符（如Analytics报告套件ID、Target客户端代码、Audience manager合作伙伴ID等）等信息

窗口顶部选项卡旁边的蓝色数字显示已发出的服务器调用数。 您可以通过单击相应选项卡中的 **[!UICONTROL Clear All Requests]** 选项卡将这些值重置为零。

例如，下图显示了有关Adobe Target的信息。 请注意，要显示下面所示的活动详细信息而不进行身份验证，您必须在代码或标签管理器中实现调试事件监听器，并在目标UI中打开必 [要的响应令牌](https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html) 。

![](assets/summary-target2.jpg)

## 在Auditor中运行审核 {#section-82bc57440406461ebf27a16855b71655}

您可以使用Adobe Auditor在您的页面上运行一系列审核。 要运行Auditor，请单击顶 **[!UICONTROL Auditor]** 部菜单中的，然后单击 **[!UICONTROL Audit Page Now]**。 要打开Adobe Auditor，请单击 **[!UICONTROL Run Multi-Page Audit Now]**。

## 调试器中显示的信息 {#section-88a95ba53dca43d9b96a585e75e5f5cf}

调试器显示每个解决方案的以下信息：

**页面信息**

<table id="table_FF3B9083524244D29AF350978A0AC236"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>页面屏幕截图 </p> </td> 
   <td colname="col2"> <p>页面缩略图 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>URL </p> </td> 
   <td colname="col2"> <p>页面的URL </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>标题 </p> </td> 
   <td colname="col2"> <p>在&lt;TITLE&gt;标记中指 <span class="codeph"> 定的名称</span> </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Analytics**

<table id="table_BEB9CC58E59D4D86BC895A8A51D84A2C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>报告套件 </p> </td> 
   <td colname="col2"> <p>A <a href="https://experiencecloud.adobe.com/resources/help/en_US/reference/report_suites_admin.html" format="html" scope="external"> report suite</a> defines the complete, independent reporting on a chosen website, set of websites, or subset of web pages </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p>为页 <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/appmeasure_mjs.html" format="html" scope="external"> 面定义的AppMeasurement</a> 版本 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>访客版本 </p> </td> 
   <td colname="col2"> <p>访客ID库的 <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external"> 版本</a> 。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Page Name </p> </td> 
   <td colname="col2"> <p>发送 <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/pageName.html" format="html" scope="external"> 到Analytics的pageName</a> 变量，其中包含站点的用户友好名称。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>模块 </p> </td> 
   <td colname="col2"> <p>Adobe Analytics加载的模块 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Audience Manager**

<table id="table_784AEABADBDA4D14BB9A7A9CB9EF07C3"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>合作伙伴 </p> </td> 
   <td colname="col2"> <p>DIL实 <a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_dil_get_partner.html" format="html" scope="external"> 例的合作伙伴</a> 名称 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p>DIL实例的版本号<a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_api_return_versions_dil.html" format="html" scope="external"></a> , </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>UUID </p> </td> 
   <td colname="col2"> <p>与 <a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/ids-in-aam.html" format="html" scope="external"> DIL实例关联的唯一用户ID</a> </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Launch**

<table id="table_E9574975444A407887E26514D1BB1601"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>名称 </p> </td> 
   <td colname="col2"> <p>Adobe Launch属性的名 <a href="https://docs.adobelaunch.com/administration/companies-and-properties" format="https" scope="external"> 称</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p>涡轮的版 <a href="https://developer.adobelaunch.com/guides/extensions/turbine-free-variable/" format="https" scope="external"> 本</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>构建日期 </p> </td> 
   <td colname="col2"> <p>启动库 <a href="https://docs.adobelaunch.com/publishing/libraries" format="https" scope="external"> 的构建日</a> 期 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>环境 </p> </td> 
   <td colname="col2"> <p>启 <a href="https://docs.adobelaunch.com/administration/environments" format="https" scope="external"> 动库</a> 使用的环境 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>脚本目录 </p> </td> 
   <td colname="col2"> <p>存储启动脚本的目录 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe DTM**

<table id="table_DC76D63FA6EF4891906B9E1D3E4A8A6C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>库名称 </p> </td> 
   <td colname="col2"> <p>Adobe DTM库的名称<a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/library_management.html" format="html" scope="external"></a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p>Turbin的版本 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>构建日期 </p> </td> 
   <td colname="col2"> <p>启动库 <a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/library_management.html" format="html" scope="external"> 的构建日</a> 期 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>环境 </p> </td> 
   <td colname="col2"> <p>DTM库使用的环境 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>脚本目录 </p> </td> 
   <td colname="col2"> <p>存储DTM脚本的目录 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Experience Cloud ID 服务**

<table id="table_274CFCEFA8F34D16BB546B4669EC0209"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Experience Cloud组织ID </p> </td> 
   <td colname="col2"> <p>Your <a href="https://experiencecloud.adobe.com/resources/help/en_US/mcvid/" format="https" scope="external"> Organization ID</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p>访客ID库的版本<a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external"></a> 。 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Target**

<table id="table_D30E0CD20FB04E41862B22655136E043"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Client Code </p> </td> 
   <td colname="col2"> <p>Your Target <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/deploy-at-js/implementing-target-without-a-tag-manager.html" format="html" scope="external"> Client Code </a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p>您当前 <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/target-atjs-versions.html" format="html" scope="external"> 的at.js</a> 或mbox.js版本 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Global Mbox Name </p> </td> 
   <td colname="col2"> <p>全局mbox<a href="https://docs.adobe.com/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> 指在Target实施中</a> ，每个网页顶部进行的单个服务器调用 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Mbox 名称 </p> </td> 
   <td colname="col2"> <p>页面上某个位置周围的mbox <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> 的名</a> 称。 仅当您在代码或标签管理器中实现调试事件监听器并在目标UI中打开必要的响应令牌时，才 <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> 可在不进行身份验证</a> 的情况下使用。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>活动名称 </p> </td> 
   <td colname="col2"> <p>Target营销活动或活 <a href="https://docs.adobe.com/content/help/en/target/using/activities/activities.html" format="html" scope="external"> 动的名称</a>。 仅当您在代码或标签管理器中实现调试事件监听器并在目标UI中打开必要的响应令牌时，才 <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> 可在不进行身份验证</a> 的情况下使用。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>活动ID </p> </td> 
   <td colname="col2"> <p>Target活动的ID。 仅当您在代码或标签管理器中实现调试事件监听器并在目标UI中打开必要的响应令牌时，才 <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> 可在不进行身份验证</a> 的情况下使用。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>菜谱名称 </p> </td> 
   <td colname="col2"> <p>Target体验的名 <a href="https://docs.adobe.com/content/help/en/target/using/experiences/experiences.html" format="html" scope="external"> 称</a>。 仅当您在代码或标签管理器中实现调试事件监听器并在目标UI中打开必要的响应令牌时，才 <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> 可在不进行身份验证</a> 的情况下使用。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>指导方针 ID </p> </td> 
   <td colname="col2"> <p>Target菜谱的ID。 仅当您在代码或标签管理器中实现调试事件监听器并在目标UI中打开必要的响应令牌时，才 <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> 可在不进行身份验证</a> 的情况下使用。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>选件 </p> </td> 
   <td colname="col2"> <p>Target选件的名 <a href="https://docs.adobe.com/content/help/en/target/using/experiences/offers/manage-content.html" format="html" scope="external"> 称</a>。 仅当您在代码或标签管理器中实现调试事件监听器并在目标UI中打开必要的响应令牌时，才 <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> 可在不进行身份验证</a> 的情况下使用。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>选件 ID </p> </td> 
   <td colname="col2"> <p>Target选件的ID。 仅当您在代码或标签管理器中实现调试事件监听器并在目标UI中打开必要的响应令牌时，才 <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> 可在不进行身份验证</a> 的情况下使用。 </p> </td> 
  </tr> 
 </tbody> 
</table>

