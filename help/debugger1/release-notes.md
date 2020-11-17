---
description: Experience Cloud Debugger 的发行说明
keywords: debugger;experience cloud debugger extension;chrome;extension;release notes
seo-description: Experience Cloud Debugger 的发行说明
seo-title: 发行说明
title: 发行说明
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
translation-type: ht
source-git-commit: e5f85bb78ad818d3507ca48eee27bb1e44f4e1a7
workflow-type: ht
source-wordcount: '723'
ht-degree: 100%

---


# 发行说明 {#release-notes}

## 发行说明 {#topic-a92c3eb799b74e7fa404af8af5efb215}

## 0.0.817 版 - 2019 年 5 月 17 日 {#topic-5dc9026cac864330b04361b1da8309a8}

## 新增功能 {#section-71352536e6894ad08f307535529394cd}

<table id="table_7EFCAF456B14404FAF3715FC56519AAF"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 功能 </th> 
   <th colname="col2" class="entry"> 描述 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>后处理点击数据 </p> </td> 
   <td colname="col2"> <p> 添加了<a href="solutions.md#section-f71dfcc22bb44c86bec328491606a482" format="dita" scope="local">在运行处理规则之后查看 Analytics 点击量值</a>的功能。 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 0.0.810 版 - 2019 年 3 月 6 日 {#topic-83bb7ddd68594177be9fd7826b650b80}

## 新增功能 {#section-0a2f6fcb0045464fa11f0586c69f7ffd}

<table id="table_96AEBFF29F3D40CAA859133B22756B0C"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 功能 </th> 
   <th colname="col2" class="entry"> 描述 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Adobe Experience Platform Auditor 测试 </p> </td> 
   <td colname="col2"> <p> 将 <a href="run-debugger.md#section-82bc57440406461ebf27a16855b71655" format="dita" scope="local">Platform Auditor 测试</a>添加到 Experience Cloud Debugger </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Adobe Audience Manager </p> </td> 
   <td colname="col2"> <p>Experience Cloud Debugger 现在可显示 AAM 响应 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 错误修复 {#section-f5e9d54e9d2546afb97972cdb6d8a093}

* 修复了页脚在页面底部隐藏内容的问题

* 更新了 Experience Cloud Debugger 页脚
* 修复了对 Target 使用过时术语的问题

## 0.0.809 版 - 2019 年 2 月 28 日 {#topic-6241de45fa9e4a23a95ad4d3a73f7348}

## 新增功能 {#section-14036b9f2c0144fdac5e292ea42ce564}

<table id="table_66E255E9BA8845CAA92779F580D14EB4"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 功能 </th> 
   <th colname="col2" class="entry"> 描述 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>嵌入代码函数 </p> </td> 
   <td colname="col2"> <p> 划分替换和插入嵌入代码函数。 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 改进 {#section-e9e8a6ddedde4c029b1d3d69c009cbad}

* 修复了未清理的用户输入导致的潜在漏洞。

## 错误修复 {#section-556417ff055848c1bf037354dd43cbd0}

* 修复了 AAM 选项卡中未捕获 AAM DIL 事件的问题

* 修复了动态插入 Launch 中用户界面似乎映射到不同嵌入代码，而实际上却没有的问题
* 修复了动态插入 Launch 中继续显示错误 URL 的问题
* 修复了在 Experience Cloud Debugger 窗口关闭后，Experience Cloud Debugger 仍继续替换嵌入代码的问题

## 0.0.806 版 - 2018 年 9 月 10 日 {#topic-a41c9d1969ff4d06ac3bb4e7d6b6d18a}

## 新增功能 {#section-4eb2a6ed26a44abc96623384a7e94b0f}

<table id="table_9AC6DE90AF4345DFA707BFBA1E58C328"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 功能 </th> 
   <th colname="col2" class="entry"> 描述 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>“工具”选项卡上的 Analytics 链接 </p> </td> 
   <td colname="col2"> <p>以 IMS 方式登录后，通过 Analytics API 显示 Evar/Prop 的友好名称。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>动态插入 Launch </p> </td> 
   <td colname="col2"> <p>在“工具”选项卡中，您可以在任何页面上动态插入 Adobe Experience Platform Launch，以在未安装 Platform Launch 的页面上测试某些内容。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Target 增强功能 </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_5FCD61733462495D8FB421DE7C813001"> 
      <li id="li_2E8E9AAE5D0D41DC8C42592AFDFA3377">为 Target 请求增加了性能计时。 </li> 
      <li id="li_98A56E71D72542D694A76DF84CE26AFA">捕获 adobe.target.trackEvent </li> 
     </ul> </p> </td> 
  </tr> 
 </tbody> 
</table>

## 改进 {#section-56003a12c32f4998bf1cf2a25a518592}

* 改进了“网络”选项卡的显示，使表格不会太高，避免用户需要先垂直滚动然后才能水平滚动。以前，滚动条显示在表格的底部。由于表格可能变得很大，用户必须一直垂直向下滚动才能看到全部内容。
* 更新了“工具”选项卡中指向 ObservePoint 的链接。

## 错误修复 {#section-d9231f5c77254d0888347e5f569a8b1d}

* 修复了 Experience Cloud 选项卡未更新的问题

* 修复了“网络”选项卡的“解决方案”行中显示“Media Optimizer”，而非最新“Advertising Cloud”名称的问题
* 修复了导致 Experience Cloud Debugger 在每个页面上注入 _satellite 的问题

## 0.0.803 版 - 2018 年 8 月 10 日 {#topic-d2901fb70ce04a5586f6c7a994fce875}

0.0.803 版不含任何面向客户的更改。

## 0.0.802 版 - 2018 年 8 月 1 日 {#topic-b93cd396af5e49dc97cd86264871aeb4}

## 新增功能 {#section-e6699fb9c9b24035ace56d6a84c9d09b}

<table id="table_E847A9D6711F4CF59E98806FA7AF8379"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 功能 </th> 
   <th colname="col2" class="entry"> 描述 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>“工具”选项卡上的 Platform Auditor 链接 </p> </td> 
   <td colname="col2"> <p>在 Experience Cloud Debugger 中添加了指向 Platform Auditor 的链接 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>折叠的选项卡 </p> </td> 
   <td colname="col2"> <p>“摘要”和“工具”选项卡上继续保留折叠的选项卡 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>单击以查看 </p> </td> 
   <td colname="col2"> <p> 为所有选项卡添加了单击查看功能 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 改进 {#section-0e7090e3e6a645f085d4553b983ecff8}

* 将名称从“Media Optimizer”更改为“Advertising Cloud”
* 从“网络”选项卡中移除了解决方案（如果未找到）

## 错误修复 {#section-7c0e4cc4b00a428489bed4a0a27c9501}

* 修复了“单击单元格以查看”功能未更新的问题
* 修复了 AAM 选项卡上未显示 AAM 点击量的问题

## 0.0.798 版 - 2018 年 6 月 14 日 {#topic-3b2d44277f2f4c0295d82724c34bf467}

## 新增功能 {#section-0d73ae8b7ced417e9039f986fafaa102}

<table id="table_8FDED5A7B7F7430A88AE441336F9C714"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 功能 </th> 
   <th colname="col2" class="entry"> 描述 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Excel 导出选项 </p> </td> 
   <td colname="col2"> <p>在“网络”选项卡上添加了 Excel 导出选项。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>改进了外观 </p> </td> 
   <td colname="col2"> <p>将 Chrome 扩展的字体更新为 Adobe Clean。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> 触控板轻扫功能 </p> </td> 
   <td colname="col2"> <p>禁用了前向/向后触控板轻扫功能。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Raw 服务器调用指示符 </p> </td> 
   <td colname="col2"> <p>添加了指示符，表明已复制 Raw 服务器调用字符串。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>清理日志选项卡 </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_D1EB0BE3A01C494983DAAF625562AC62"> 
      <li id="li_2696D26320F54A089D3CC99962EC9670">如果在日志中未找到解决方案对应的行项目，则在解决方案筛选器中隐藏该解决方案 </li> 
      <li id="li_D4586A6AB2AD42BB9F0FA3E7A01382C6">如果找不到 DTM 调用，则隐藏级别筛选器，因为该筛选器仅应用于 DTM </li> 
      <li id="li_E2AF179037DC4C63B960013AB1F9AD6A">更改“级别”列中显示的图标，这样如果这些图标在单击时不会有任何反应，那么它们在外观上看起来是不可点击的 </li> 
      <li id="li_3DB6682D6C9040D99F04C688E208CE1F">标准化 DTM 行项目上的“显示代码”格式 </li> 
     </ul> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>更新页脚中的帮助链接 </p> </td> 
   <td colname="col2"> <p>将页脚中的帮助链接更新为 <a href="https://docs.adobe.com/content/help/zh-Hans/debugger/using/experience-cloud-debugger.html" format="https" scope="external">https://docs.adobe.com/content/help/zh-Hans/debugger/using/experience-cloud-debugger.html</a> </p> </td> 
  </tr> 
 </tbody> 
</table>

## 错误修复 {#section-c292cf7dcb17463bb1928de73bd55121}

* 修复了徽章编号未清除的问题
* 修复了客户报告的空白摘要详细信息的问题

## 0.0.797 版 - 2018 年 5 月 25 日 {#topic-51490f4f42aa40eb879663fad9d62916}

## 新增功能 {#section-bbf8ff7e000e4b5592d348e0870471f6}

<table id="table_8CF872DC245A46C38FE21490C842D47A"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 功能 </th> 
   <th colname="col2" class="entry"> 描述 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Mbox 切换 </p> </td> 
   <td colname="col2"> <p>在“目标”选项卡上添加了 Mbox 切换 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>筛选器设置现已粘滞 </p> </td> 
   <td colname="col2"> <p>筛选器设置现已固定到网络和日志选项卡的屏幕顶部。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>查看和复制网络值 </p> </td> 
   <td colname="col2"> <p>您可以查看详细信息，并复制网络选项卡中任何单元格的值。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>页脚法律声明链接和版权信息 </p> </td> 
   <td colname="col2"> <p>在用户界面上添加了页脚法律声明链接和版权信息。 </p> </td> 
  </tr> 
 </tbody> 
</table>

