---

copyright:
  years: 2017
lastupdated: "2018-11-30"

keywords: bypass, firewall, rules,

subcollection: hardware-firewall-dedicated

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:download: .download}
{:note: .note}
{:important: .important}

# 绕过 Hardware Firewall (Dedicated) 规则
{: #bypassing-hardware-firewall-dedicated-rules}

要绕过防火墙规则：

1. 从浏览器，打开[客户门户网站 ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")](https://control.softlayer.com/){: new_window}，并登录到帐户。
2. 在“客户门户网站”导航中，转至**网络 > IP 管理 > VLAN**，然后单击要绕过的防火墙设备。
3. 在**设备详细信息**页面中，可使用**操作**下拉菜单来选择**设置绕过规则**，或者在**状态**部分中单击**绕过规则**按钮。不管是哪种方式，都应该会显示确认对话框。单击**是**以确认操作。绕过规则大约会在两分钟后生效。在绕过模式下，“状态”将为“正在绕过所有规则”。

	另一个选择是在执行故障诊断等操作时绕过防火墙，可使用**操作**下拉菜单来选择**设置绕过路由**，或者在**状态**部分中单击**绕过**。

## 重新启用规则
{: #enable-the-rules-again}

要重新启用规则，请按照以上指示信息，到达**设备详细信息**页面，然后单击**操作**下拉菜单，选择**设置绕过路由**。此时将显示确认对话框。单击**是**以确认操作。“状态”将在两分钟后重新变回“正在绕过防火墙”。
