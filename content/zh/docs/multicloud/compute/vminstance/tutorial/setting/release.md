---
title: "到期释放"
date: 2022-01-06T16:19:19+08:00
weight: 60
description: >
    设置虚拟机的使用时长
---

到期释放即设置虚拟机的使用时长，当超过设置期限时，虚拟机将会被自动删除，存放到回收站。

{{% alert title="注意" color="warning" %}}
- 公有云仅按量付费的虚拟机支持到期释放功能。
- 公有云虚拟机放入回收站后仍然收费，如虚拟机不再使用，请在回收站进行清除。
{{% /alert %}}

1. 在左侧导航栏，选择 **_"主机/主机/虚拟机"_** 菜单项，进入虚拟机页面。
2. 单击虚拟机右侧操作列 **_"更多"_** 按钮，选择下拉菜单 **_"实例设置-到期释放"_** 菜单项，弹出到期释放对话框。
2. 选择是否勾选到期释放，勾选后设置虚拟机的释放时间，单击 **_"确定"_** 按钮。
    - 单击释放时间输入框，显示日历等内容，支持直接在释放时间输入框中输入日期和时间，格式为yyyy-mm-dd hh:mm:ss，单击 **_"确定"_** 按钮。 
    - 在日历框中选择日期，单击 **_选择时间_** 按钮，将跳转到设置时间界面，选择时间后，单击 **_"确定"_** 按钮。
    - 支持快速选择“1小时”、“2小时”、“3小时”、 “6小时”、 “1天”、“2天”、 “1周”按钮，释放时间将设置为对应时间范围内的时间，单击 **_"确定"_** 按钮。
3. 设置完成后，在计费方式列显示虚拟机还有多久时间释放等信息。
4. 若不再需要到期释放功能，可在虚拟机释放之前，在弹出的到期释放对话框中取消勾选到期释放，单击 **_"确定"_** 按钮。