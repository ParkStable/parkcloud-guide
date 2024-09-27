---
description: 仔细阅读教程很多问题都会自行解决
---

# Clash 使用教程

{% hint style="success" %}
**使用前请先确认是否满足以下条件:**

✔  我的帕克云会员没有过期

✔  设备中没有开启其他VPN类软件

✔  我的网络不是校园网或者公司内网
{% endhint %}

## **客户端安装**

**1.客户端下载**

> 以下链接提供 ClashX 的安装包

{% embed url="https://file.parkcloud.cc/s/v8hM" %}

#### **2.拖入安装**

官网首页下载客户端后，打开下载的 **「 ClashX.dmg 」** 文件，将 **「 ClashX 」** 拖拽到 **「 Applications 」** 文件夹当中

![拖入安装](https://pic.parkcloud.cc/i/2024/09/10/112cqep.gif)

#### **3.启动客户端**

在启动台或者应用程序中找到 **「 ClashX 」** 启动软件，首次打开的时候会有安全提示，点击 **「 **<mark style="background-color:red;">**打开**</mark>** 」** 选项

根据系统提示点击 **「 **<mark style="background-color:red;">**安装**</mark>** 」** 然后输入电脑账户的密码并 **「 **<mark style="background-color:red;">**安装帮助程序**</mark>** 」** ，检测核查更新可根据情况自行选择检查或不检查。

成功打开软件后，状态栏会出现 **「 ClashX 」** 的图标

![启](https://pic.parkcloud.cc/i/2024/09/10/112cbd5.gif)

## **导入订阅**

#### **方式一 自动导入**

使用浏览器登录进入帕克云首页 **「 用户中心 」** ，如果您忘记了帕克云官网地址可前往地址发布页[ 点击前往](https://guide.923ka.com/) 找到最新的官网地址

在 **「 订阅链接 」** 中找到 **「 Clash订阅 」** 点击 **「 **<mark style="background-color:red;">**一键导入Clash**</mark>** 」** 按钮

点击后会自动提示跳转到 Clash 客户端，根据提示点击 **「 **<mark style="background-color:red;">**允许**</mark>** 」** 按钮。

在 ClashX 弹出的 **「 添加托管配置文件界面 」** 点击 **「 **<mark style="background-color:red;">**确定**</mark>** 」** 按钮，即可成功订阅配置文件。

![自动导入](https://pic.parkcloud.cc/i/2024/09/10/112clff.gif)

> 如果系统无法自动跳转或订阅失败，请参考下面 [手动导入](clash-shi-yong-jiao-cheng.md#fang-shi-er-shou-dong-dao-ru) 方式

#### **方式二 手动导入**

在 **「 订阅链接 」** 中找到 **「 Clash订阅 」** 点击 **「 **<mark style="background-color:red;">**复制Clash订阅**</mark>** 」** 按钮

![复制订阅](https://pic.parkcloud.cc/i/2024/09/10/112cz47.gif)

打开 **「 **<mark style="background-color:red;">**主菜单**</mark>** 」** -> **「 **<mark style="background-color:red;">**配置**</mark>** 」** -> **「 **<mark style="background-color:red;">**托管配置**</mark>** 」** -> **「 **<mark style="background-color:red;">**管理**</mark>** 」** ，在 **「 托管的配置文件 」** 下方点击 **「 **<mark style="background-color:red;">**添加**</mark>** 」** 按钮。

将刚刚复制的地址粘贴进入 **「 Url 」** 栏， **「 Config Name 」** 栏可随意填写，点击 **「 **<mark style="background-color:red;">**确定**</mark>** 」** 即可成功订阅配置文件。

![手动导入](https://pic.parkcloud.cc/i/2024/09/10/112cswp.gif)

## **开启代理**

打开 **「 主菜单 」** 在 **「 **<mark style="background-color:red;">**出站模式(规则)**</mark>** 」** 中选择 **「 **<mark style="background-color:red;">**全局连接**</mark>** 」** ，然后在 **「 **<mark style="background-color:red;">**GLOBAL**</mark>** 」** 中选择一个国家地区节点。

其他规则如「其他流量、Telegram」等可自行设置选择节点。

![选择节点](https://pic.parkcloud.cc/i/2024/09/10/112clfz.gif)

选择好国家地区节点并改为全局连接后，点击 **「 **<mark style="background-color:red;">**设置为系统代理**</mark>** 」** 开启系统代理。

此时状态栏 ClashX 图标由**灰色变成黑色**，即成功开启了VPN代理。

![开启代理](https://pic.parkcloud.cc/i/2024/09/10/112cqzl.gif)

{% hint style="danger" %}
**使用建议**

订阅地址是你个人账号密码及节点的总集成，不能泄露给任何人及网络，以防止他人使用及知晓你的密码。&#x20;

建议定期手动更新订阅，即可保持与服务器同步更新。
{% endhint %}

## **更新订阅**

#### **1.关闭代理**

打开状态栏 **「 **<mark style="background-color:red;">**主菜单**</mark>** 」** 将 **「 **<mark style="background-color:red;">**设置为系统代理**</mark>** 」** 取消勾选，关闭代理（这一步很重要）

![关闭代理](https://pic.parkcloud.cc/i/2024/09/10/112cz77.gif)

#### **2.更新订阅**

打开 **「 **<mark style="background-color:red;">**主菜单**</mark>** 」** -> **「 **<mark style="background-color:red;">**配置**</mark>** 」** -> **「 **<mark style="background-color:red;">**托管配置**</mark>** 」** -> **「 **<mark style="background-color:red;">**管理**</mark>** 」** ，在 **「 托管的配置文件 」** 下方选择已添加的帕克云订阅。

点击 **「 **<mark style="background-color:red;">**更新**</mark>** 」** 按钮，即可成功更新订阅节点

![更新订阅](https://pic.parkcloud.cc/i/2024/09/10/112d15t.gif)

{% hint style="danger" %}
**更新失败解决办法：**

删除「托管的配置文件」中的帕克云订阅。

&#x20;前往 【ClashX 使用教程】 根据教程一步一步操作，重新配置导入节点
{% endhint %}
