---
title: "WAF策略"
weight: 1
description: WAF策略用于为Web应用提供集中式保护，使其免受常见攻击和漏洞的侵害。
---

WAF（Web Application Firewall）用于为Web应用提供集中式保护，使其免受常见攻击和漏洞的侵害。WAF可以有效识别Web业务流量的恶意特征，在对流量进行清洗和过滤后，将正常、安全的流量返回给服务器，避免网站服务器被恶意入侵导致服务器性能异常等问题，保障网站的业务安全和数据安全。


目前仅只读对接AWS、Azure、阿里云平台的WAF。

**入口**：在云管平台单击左上角![](../../../images/intro/nav.png)导航菜单，在弹出的左侧菜单栏中单击 **_"网络/网络安全/WAF策略"_** 菜单项，进入WAF策略列表。

![](../../../images/network/waf.png)


## 同步状态

该功能用于获取WAF的当前状态。

**单个同步状态**

1. 在WAF策略页面，单击列表右侧操作列 **_"同步状态"_** 按钮，同步WAF状态。

**批量同步状态**

1. 在WAF策略页面，单击列表上方操作列 **_"同步状态"_** 按钮，同步WAF状态。

## 管理规则

该功能用于查看WAF策略下的规则信息。

1. 在WAF策略页面，单击WAF右侧操作列 **_"更多"_** 按钮，选择下拉菜单 **_"管理规则"_** 菜单项，进入规则页面。
2. 单击 **_"查看"_** 按钮，查看具体的规则信息。
    - 规则名称：WAF规则的名称。
    - 优先级：WAF规则的优先级，数值越小，优先级越大。
    - 匹配策略：支持对规则下的多个条件进行AND、OR、NOT的操作。
        - AND即满足以下全部条件。
        - OR即满足以下任意一个条件。
        - NOT即不满足以下条件。
    - 条件：WAF将通过条件中的设置检查请求流量，条件支持对IP、位置、字符串等类型。
    - 处理动作：WAF将满足规则条件的流量进行的处理动作，包括允许、阻塞、日志等。

## 管理资源

该功能用于查看WAF策略管理的资源信息。

1. 在WAF策略页面，单击WAF右侧操作列 **_"更多"_** 按钮，选择下拉菜单 **_"管理资源"_** 菜单项，进入关联资源页面。
2. 查看资源名称、资源类型、端口等信息。

## 删除

该功能用于删除WAF。

**单个删除**

1. 在WAF策略页面，单击WAF右侧操作列 **_"更多"_** 按钮，选择下拉菜单 **_"删除"_** 菜单项，弹出操作确认对话框。
2. 单击 **_"确定"_** 按钮，完成操作。

**批量删除**

1. 在WAF列表中选择一个或多个WAF，单击列表上方 **_"批量操作"_** 按钮，选择下拉菜单 **_"删除"_** 菜单项，弹出操作确认对话框。
2. 单击 **_"确定"_** 按钮，完成操作。

## 查看WAF详情

该功能用于查看WAF的详细信息。

1. 在WAF策略页面，单击WAF名称项，进入WAF详情页面。
2. 查看以下信息。
    - 基本信息：包括云上ID、ID、名称、状态、域、项目、WAF类型、默认策略动作、平台、区域、可用区、云账号、云订阅、创建时间、更新时间、备注。


## 查看WAF操作日志

该功能用于查看WAF相关操作的日志信息。

1. 在WAF策略页面，单击WAF的名称项，进入WAF详情页面。
2. 单击“操作日志”页签，进入操作日志页面。
    - 加载更多日志：列表默认显示20条操作日志信息，如需查看更多操作日志，请单击 **_"加载更多"_** 按钮，获取更多日志信息。
    - 查看日志详情：单击操作日志右侧操作列 **_"查看"_** 按钮，查看日志的详情信息。支持复制详情内容。
    - 查看指定时间段的日志：如需查看某个时间段的操作日志，在列表右上方的开始日期和结束日期中设置具体的日期，查询指定时间段的日志信息。
    - 导出日志：目前仅支持导出本页显示的日志。单击右上角![](../../../images/system/download.png)图标，在弹出的导出数据对话框中，设置导出数据列，单击 **_"确定"_** 按钮，导出日志。