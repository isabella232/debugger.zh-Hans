---
description: Debugger 会检查您的网页，并帮助您发现 Experience Cloud 解决方案的实施存在哪些问题
keywords: debugger;experience cloud debugger extension;chrome;extension
seo-description: Adobe Experience Cloud Debugger 2.0 Chrome 和 Firefox 扩展技术文档 - 检查您的网页，并了解您的 Experience Cloud 解决方案实施中存在的问题
seo-title: Adobe Experience Platform Debugger Chrome和Firefox Extension
title: Adobe Experience Platform调试器扩展
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
translation-type: tm+mt
source-git-commit: 3dc1876c0516b7a81f68a207c6a1651bc95b17ab

---


# （测试版）Adobe Experience Platform Debugger 2.0 {#adobe-experience-platform-debugger}

>[!IMPORTANT]
>
>Adobe Experience Cloud Debugger 2.0目前处于测试阶段。 文档和功能可能会发生更改。

The [Adobe Experience Platform Debugger for Chrome](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj) and [Firefox](https://addons.mozilla.org/zh-CN/firefox/addon/adobe-experience-platform-dbg/) examines your web pages and helps you find problems with how your Experience Cloud solutions are implemented.

将Adobe Experience Platform Debugger与其他Adobe激活解决方案结合使用，以实现如下工作流程：

1. 使用 [Launch](https://docs.adobe.com/content/help/zh-Hans/launch/using/overview.translate.html) 或 [DTM](https://docs.adobe.com/content/help/zh-Hans/dtm/using/dtm-home.translate.html) 插入可在您的页面上激活 [Adobe Experience Cloud](https://docs.adobe.com/content/help/zh-Hans/core-services/interface/experience-cloud.html) 解决方案的代码。

1. 使用 [Adobe Cloud Platform Auditor](https://experiencecloud.adobe.com/resources/help/en_US/auditor/) 对您的实施进行测试。
1. 使用Adobe Experience Platform Debugger调试Auditor找到的问题或检查有关您的实施的其他信息。

不一定按照列出的顺序执行上述步骤，但这是一个常见的流程。

尽管您可以在任何网页上运行 Debugger，但是只有当您在其中一个打开的 Chrome 标签页上通过 Experience Cloud 身份验证之后，才能在该扩展中使用任何非公共数据。

## 用例 {#section-9fcd0583ed184943a8f0c2d3c00658e0}

使用 Debugger 收集有助于了解 Experience Cloud 解决方案实施情况的信息。例如：

* **启动项：** 查看在页面上部署了哪个属性(环境、内部版本)。
* **Target：**&#x200B;查看您有无资格执行哪些活动及原因。
