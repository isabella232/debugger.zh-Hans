---
description: 使用Adobe Debugger中的“解决方案”选项卡
keywords: 调试器；体验云调试器扩展；铬色；扩展；摘要；清除；请求；解决方案；解决方案；信息；分析；目标；受众管理器；媒体优化器；amo;id服务
seo-description: 使用Adobe Debugger中的“解决方案”选项卡
seo-title: Adobe Debugger中的解决方案选项卡
title: 解决方案选项卡
uuid: 5e999ef2-6399-4ab5-a841-3a839d081728
translation-type: tm+mt
source-git-commit: 3fd50cde86f0dfc5f66d8faf63112adf24beeac0

---


# 解决方案选项卡{#solution-tabs}

单击解决方案选项卡，查看特定Adobe Experience cloud解决方案的结果。

## Analytics {#section-f71dfcc22bb44c86bec328491606a482}

“分析”选项卡提供有关 [Analytics实施](https://experiencecloud.adobe.com/resources/help/en_US/reference/) 的信息。

**点击量**

默认情况下，对同一报表包进行的所有服务器调用都会折叠。

![](assets/analytics-hits.jpg)

**** 下载：下载有关所有显示的报表包的信息，作为Excel电子表格。

**** 清除所有请求：从“分析”视图中删除所有显示的请求。 清除请求后，新请求将在发生时显示。

单击报表包ID以展开视图：

![](assets/analytics-hits-expand.jpg)

此屏幕显示自调试器打开或请求清除以来的所有请求。 默认参数会自动映射到友好名称。 [如果您使用“链接分析”功能进行身份验证，则prop和eVar变量可映射到您的自定义友好名称（例如，“prop1”可显示为“用户类型”）。](https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/props_eVars.html) 请求按从左到右的顺序显示。

**** 下载：将向报表包发出的所有请求另存为Excel电子表格。

**** 清除请求：删除对此报表包发出的所有请求。 新请求在出现时显示。

**关联帐户（旧版）**

单击 **[!UICONTROL 关联帐户]**，然后输入请求的信息以将Analytics帐户关联到调试器。

>[!NOTE]
>
>目前，仅旧版Analytics用户登录凭据支持此功能。

![](assets/analytics-link-account.jpg)

**检索后处理的点击**

如果要在处理规则运行后查看Analytics点击的值，请启用检索处理后的点击选项。 您必须登录到Adobe Experience Cloud，才能使用此功能。

启用此选项后，将向Analytics请求添加一个调试参数。 与任何其他点击一样，点击将继续得到处理。 调试器轮询Analytics调试API，以检索具有原始点击ID的任何点击的后处理规则值。 后处理的点击具有紫色背景，并显示在原始点击旁边。

对于大多数Analytics实施，在几分钟内即可获得后处理规则信息。 Analytics for Target(A4T)实施需要更长的时间。

## Target {#section-988873ba5ede4317953193bd7ac5474c}

使用Target选项卡可查看 [Target请求](https://docs.adobe.com/content/help/en/target/using/target-home.html) 或 [Mbox Trace响应详细信](https://docs.adobe.com/content/help/en/target/using/activities/troubleshoot-activities/content-trouble.html) 息。

单击 **[!UICONTROL 请求]**，然后展开环境以查看有关Target的信息。

![](assets/target-requests.jpg)

单击 **[!UICONTROL 清除所有请求]** ，以删除当前显示的请求。 将在发出请求时显示更多请求。

您还可以使用“目标”过滤器启 [用“MBox跟踪”以用于Target调试](https://docs.adobe.com/content/help/en/target/using/activities/troubleshoot-activities/content-trouble.html)。

您必须有一个打开的Chrome选项卡，该选项卡通过身份验证后才能进入Experience Cloud以启用Mbox跟踪。 启用后，将显示您的Adobe id用户名。 展开您的用户名，以显示与您有权访问的Experience cloud组织关联的Target客户端代码。 单击要为其启用Mbox跟踪的客户端代码，并确认出现绿色复选标记。 现在将显示所有包含Mbox跟踪信息的Target请求，这些请求按客户代码分组。 要浏览Mbox跟踪信息，请展开请求以查看选项卡：

* [活动](https://docs.adobe.com/content/help/en/target/using/activities/activities.html) “活动”选项卡显示与目标请求名称关联的所有活动，无论您是否符合活动的条件。 “匹配活动”是您符合条件的活动，响应时会提供其选件。 您可以展开活动名称以确认您所在的体验，以及哪些受众和定位条件使您有资格参与活动。 “评估的活动”是评估的所有活动，无论您是否合格。 要解决您未符合“已评估”但未“匹配”活动资格的原因，请展开活动名称并查看“不匹配的受众”部分。

* 请求

   Mbox跟踪的请求 [选项卡与主请求选项卡](https://docs.adobe.com/content/help/en/target/using/activities/troubleshoot-activities/content-trouble.html) 类似。 除了请求标题外，您还可以查看Target请求传递的所有参数。
* Profile

   展开“配置文件快照”部分，查 [看在Target配置文件数据库中](https://docs.adobe.com/content/help/en/target/using/audiences/visitor-profiles/variables-profiles-parameters-methods.html) ，以访客身份存储的有关您的配置文件信息。 此处显示所有Mbox内和脚本配置文件以及一些系统配置文件。 “状态”列显示在此请求范围内更改了哪些配置文件，以及在请求进入配置文件系统之前和之后更改的配置文件的值。
* Audience Manager

   Audience Manager选项卡的“segmentId”和“cachedSegmentId”部分显示从Experience cloud共享到Target的受众的 [ID](https://docs.adobe.com/content/help/en/target/using/audiences/target.html) ，并且您已为这些ID进行了资格验证。 这些受众可以是在Audience Manager、Analytics中创建的受众，也可以是People Core service中的Audience Builder。 可以在Audience manager用户界面中查找这些ID以查找受众名称。

以下视频展示了Target的一般功能：

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/?captions=chi_hans)

以下视频显示了Mbox跟踪：

>[!VIDEO](https://video.tv.adobe.com/v/23113t2/?captions=chi_hans)

## Audience Manager {#section-1d4484f8b46f457f859ba88039a9a585}

使用 [Audience Manager](https://experiencecloud.adobe.com/resources/help/en_US/aam/) 选项卡查看活动的详细 [信息](https://experiencecloud.adobe.com/resources/help/en_US/aam/dcs-event-calls.html)。 单击组织以展开它并显示信息。

![](assets/audience-manager.jpg)

单击 **[!UICONTROL 清除所有事件]** ，以重置显示的信息。 新事件将在发生时显示。

**ID同步**

ID同步是入站异步数据传输过程中的第一步。 在此步骤中，Audience manager和供应商比较并匹配各自站点访客的ID。

![](assets/aam-idsync.jpg)

有关详 [细信息，请参阅Audience Manager产品文档中的](https://experiencecloud.adobe.com/resources/help/en_US/aam/c_id_sync_in.html) “入站数据传输的ID同步”。

## Advertising Cloud {#section-ee80a9c509f2462c89c1e5bd8d05d7c8}

使用Advertising cloud选项卡查看Advertising cloud请求。

单击 **[!UICONTROL 请求]**，然后展开环境以查看有关Advertising Cloud的信息。

单击 **[!UICONTROL 清除所有请求]** ，以删除当前显示的请求。 将在发出请求时显示更多请求。

## Experience Cloud ID 服务 {#section-a96c32f8e63a4991abb296f6e8ea01cf}

使用Experience Cloud ID服务选项卡查看 [Experience Cloud ID服务请求](https://experiencecloud.adobe.com/resources/help/en_US/mcvid/) 。

单击 **[!UICONTROL 请求]**，然后展开环境以查看有关Experience Cloud ID服务的信息。

单击 **[!UICONTROL 清除所有请求]** ，以删除当前显示的请求。 将在发出请求时显示更多请求。
