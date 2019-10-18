---
description: 'null'
keywords: 调试器；Experience Cloud调试器扩展；chrome；扩展；发行说明
seo-description: 'null'
seo-title: 发行说明
title: 发行说明
uuid: 47a5d6f3-c074-4ad5-ad4b-e603049689b
translation-type: tm+mt
source-git-commit: 3fd50cde86f0dfc5f66d8faf63112adf24beeac0

---


# 发行说明{#release-notes}

## 发行说明 {#topic-a92c3eb799b74e7fa404af8af5efb215}

## Version 0.0.817 May 17, 2019 {#topic-5dc9026cac864330b04361b1da8309a8}

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
   <td colname="col2"> <p> 添加了在处理规 <a href="solutions.md#section-f71dfcc22bb44c86bec328491606a482" format="dita" scope="local"> 则运行后查看Analytics点击值的功能</a>。 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 版本0.0.810 2019年3月6日 {#topic-83bb7ddd68594177be9fd7826b650b80}

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
   <td colname="col1"> <p>Auditor测试 </p> </td> 
   <td colname="col2"> <p> 向调试 <a href="run-debugger.md#section-82bc57440406461ebf27a16855b71655" format="dita" scope="local"> 器添加了Auditor测试</a> 。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Adobe Audience Manager </p> </td> 
   <td colname="col2"> <p>调试器现在显示AAM响应 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 错误修复 {#section-f5e9d54e9d2546afb97972cdb6d8a093}

* 修复了页脚在页面底部隐藏内容的问题

* 更新了调试器页脚
* 修复了Target使用过时术语的问题

## 版本0.0.809 2019年2月28日 {#topic-6241de45fa9e4a23a95ad4d3a73f7348}

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

* 修复了AAM选项卡中未捕获AAM DIL事件的问题

* 修复了动态插入启动项中的一个问题，该问题导致用户界面在未映射到其他嵌入代码时显示为
* 修复了动态插入启动项中继续显示错误URL的问题
* 修复了调试器在关闭调试器窗口时仍继续替换嵌入代码的问题

## 版本0.0.806 2018年9月10日 {#topic-a41c9d1969ff4d06ac3bb4e7d6b6d18a}

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
   <td colname="col1"> <p>“工具”选项卡上的分析链接 </p> </td> 
   <td colname="col2"> <p>通过IMS登录通过Analytics API显示evar/prop的友好名称。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>动态插入启动项 </p> </td> 
   <td colname="col2"> <p>在工具选项卡中，您可以在任何页面上动态插入启动项，以测试未安装启动项的页面上的某些内容。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Target增强功能 </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_5FCD61733462495D8FB421DE7C813001"> 
      <li id="li_2E8E9AAE5D0D41DC8C42592AFDFA3377">为Target请求增加了性能定时。 </li> 
      <li id="li_98A56E71D72542D694A76DF84CE26AFA">捕获adobe.target.trackEvent </li> 
     </ul> </p> </td> 
  </tr> 
 </tbody> 
</table>

## 改进 {#section-56003a12c32f4998bf1cf2a25a518592}

* 改进了“网络”选项卡的显示，使表的高度不会过大，并强制用户在水平滚动之前垂直滚动。 以前，滚动条会显示在表的底部。 由于表格可能很大，用户必须垂直向下滚动所有表格才能看到它们。
* 更新了“工具”选项卡中指向ObservePoint的链接。

## 错误修复 {#section-d9231f5c77254d0888347e5f569a8b1d}

* 修复了Experience cloud选项卡未更新的问题

* 修复了“网络”选项卡的“解决方案”行中显示“Media Optimizer”而非当前“Advertising Cloud”名称的问题
* 修复了导致调试器在每个页面上插入_satellite的问题

## 版本0.0.803 2018年8月10日 {#topic-d2901fb70ce04a5586f6c7a994fce875}

版本0.0.803不包括任何面向客户的更改。

## 版本0.0.802 2018年8月1日 {#topic-b93cd396af5e49dc97cd86264871aeb4}

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
   <td colname="col1"> <p>“工具”选项卡上的“审计者”链接 </p> </td> 
   <td colname="col2"> <p>从调试器中添加了指向Auditor的链接 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>折叠的选项卡 </p> </td> 
   <td colname="col2"> <p>折叠的选项卡会保留在“摘要”和“工具”选项卡上 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>单击以查看 </p> </td> 
   <td colname="col2"> <p> 向所有选项卡添加了单击查看功能 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 改进 {#section-0e7090e3e6a645f085d4553b983ecff8}

* 将Media Optimizer的名称更改为Advertising Cloud
* 从“网络”选项卡中删除了解决方案（如果未找到）

## 错误修复 {#section-7c0e4cc4b00a428489bed4a0a27c9501}

* 修复了“单击单元格以查看”功能未更新的问题
* 修复了AAM选项卡上未显示AAM点击的问题

## 版本0.0.798 2018年6月14日 {#topic-3b2d44277f2f4c0295d82724c34bf467}

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
   <td colname="col1"> <p>Excel导出选项 </p> </td> 
   <td colname="col2"> <p>向“网络”选项卡添加了Excel导出选项。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>改进的外观 </p> </td> 
   <td colname="col2"> <p>已将Chrome扩展字体更新为Adobe Clean。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> 轨迹板轻扫功能 </p> </td> 
   <td colname="col2"> <p>禁用前向／后向轨迹板轻扫功能。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>原始服务器调用指示符 </p> </td> 
   <td colname="col2"> <p>添加了一个指示符，指示已复制原始服务器调用字符串。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>“清理日志”选项卡 </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_D1EB0BE3A01C494983DAAF625562AC62"> 
      <li id="li_2696D26320F54A089D3CC99962EC9670">如果日志中没有找到解决方案的行项目，请在解决方案筛选器中隐藏解决方案 </li> 
      <li id="li_D4586A6AB2AD42BB9F0FA3E7A01382C6">如果找不到DTM调用，则隐藏级别过滤器，因为它仅适用于DTM </li> 
      <li id="li_E2AF179037DC4C63B960013AB1F9AD6A">更改“级别”列中显示的图标，以便在单击时不发生任何事件时，它们看起来不可单击 </li> 
      <li id="li_3DB6682D6C9040D99F04C688E208CE1F">标准化DTM行项目上的“显示代码”格式 </li> 
     </ul> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Update help link in footer </p> </td> 
   <td colname="col2"> <p>将页脚中的帮助链接更新到 <a href="https://marketing.adobe.com/resources/help/en_US/experience-cloud-debugger/" format="https" scope="external"> https://marketing.adobe.com/resources/help/en_US/experience-cloud-debugger/</a> </p> </td> 
  </tr> 
 </tbody> 
</table>

## 错误修复 {#section-c292cf7dcb17463bb1928de73bd55121}

* 修复了徽章编号未清除的问题
* 修复了客户报告空白摘要详细信息的问题

## Version 0.0.797 May 25, 2018 {#topic-51490f4f42aa40eb879663fad9d62916}

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
   <td colname="col2"> <p>Mbox切换已添加到“目标”选项卡 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>过滤器设置现在变得粘滞 </p> </td> 
   <td colname="col2"> <p>过滤器设置现在粘贴到网络屏幕顶部并记录选项卡。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>查看和复制网络值 </p> </td> 
   <td colname="col2"> <p>您可以查看详细信息并复制网络选项卡中任何单元格的值。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>法律页脚链接和版权 </p> </td> 
   <td colname="col2"> <p>向用户界面添加了合法页脚链接和版权信息。 </p> </td> 
  </tr> 
 </tbody> 
</table>

