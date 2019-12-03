---
description: 'null'
keywords: debugger;experience cloud debugger extension;chrome;extension;network;information
seo-description: 'null'
seo-title: 网络信息
title: 网络信息
uuid: 839686c9-6e4f-4661-acf6-150ea24dc47f
translation-type: tm+mt
source-git-commit: b9147536b8312599dd3144cac31dea9f0f1c3625

---


# 网络信息{#network-information}

To view Network information, click **[!UICONTROL Network]**.

“网络”屏幕汇总页面上发出的所有 Adobe Experience Cloud 解决方案调用，并按从左到右的顺序显示。标准参数会自动标示友好名称，并按照相同的角色对常用参数进行分组。

![](assets/network.jpg)

此屏幕有助于确认用于集成的参数（如Experience Cloud访客ID或补充数据ID）是否在整合中保持一致。

>[!NOTE]
>
>目前，并非所有在解决方案调用中传递的参数都在“网络”屏幕中可见，例如，Analytics 上下文变量、Target 自定义参数或 Experience Cloud ID 服务客户 ID。

要按解决方案筛选信息，请从左侧导航的列表中选择要查看的解决方案。 以下示例经过筛选，仅显示Analytics:

![](assets/network-analytics.jpg)

要返回显示所有解决方案，请单击 **[!UICONTROL Network]**

单击“网络”视图中的某个项目可查看扩展视图。 从展开的视图窗口中，可以将显示的信息复制到剪贴板。

![](assets/network-expand.jpg)

<!--Use the icon at the top of each column to copy the server call URL to your clipboard, where you can paste it into another document for reference or debugging purposes.

![](assets/copy.jpg)-->

要清除列表，请单击 **[!UICONTROL Remove Events]**。

要下载包含此屏幕上信息的Excel文件，请单击 **[!UICONTROL Download]**。