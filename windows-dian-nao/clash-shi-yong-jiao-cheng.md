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

## **下载安装**

**1.客户端下载**

> 以下链接提供 Clash for Windows 的安装包&#x20;

{% embed url="https://file.parkcloud.cc/s/ojTR" %}

![下载客户端](https://pic.parkcloud.cc/i/2024/09/10/xzn076.gif)

#### **2.解压安装**

将下载好的压缩包直接解压到电脑内某目录，打开该目录，运行 **「 **<mark style="background-color:red;">**Clash for Windows**</mark>** 」** 并在弹出的提示框中点击 **「 **<mark style="background-color:red;">**是**</mark>** 」** 继续运行。

![安装应用](https://pic.parkcloud.cc/i/2024/09/10/xzmyty.gif)

## **导入订阅**

#### **方式一：自动导入**

使用浏览器登录进入帕克云首页 **「 用户中心 」** ，如果您忘记了帕克云官网地址可前往地址发布页[ 点击前往](https://guide.923ka.com/) 找到最新的官网地址

在 **「 订阅链接 」** 中找到 **「 Clash订阅 」** 点击 **「 **<mark style="background-color:red;">**一键导入Clash**</mark>** 」** 按钮

点击后会自动提示跳转到 Clash 客户端，根据提示点击 **「 **<mark style="background-color:red;">**打开Clash for Windows 」**</mark> ，此时 Clash 客户端中会出现帕克云订阅配置文件。

![自动导入](https://pic.parkcloud.cc/i/2024/09/10/xzn1s8.gif)

> 如果系统无法自动跳转或订阅失败，请参考下方 [手动导入](clash-shi-yong-jiao-cheng.md#fang-shi-er-shou-dong-dao-ru) 方式

#### **方式二：手动导入**

在 **「 订阅链接 」** 中找到 **「 Clash订阅 」** 点击 **「 **<mark style="background-color:red;">**复制Clash订阅**</mark>** 」** 按钮

打开 Clash 客户端的 **「 **<mark style="background-color:red;">**配置**</mark>** 」** 栏，将刚刚复制的地址粘贴到 **「 **<mark style="background-color:red;">**从URL下载**</mark>** 」** 框中点击 **「 **<mark style="background-color:red;">**下载**</mark>** 」** ，此时 Clash 客户端中会出现订阅配置文件。

![手动导入](https://pic.parkcloud.cc/i/2024/09/10/xzn8nu.gif)

## **开启代理**

在 Clash 客户端的 **「 **<mark style="background-color:red;">**配置**</mark>** 」** 栏中，选择刚刚导入好的订阅文件，选中后会出现绿色选中提示。

在 Clash 客户端的 **「 **<mark style="background-color:red;">**代理**</mark>** 」** 栏中，选择 **「 **<mark style="background-color:red;">**全局**</mark>** 」** 然后在下方节点列表中选择一个国家地区节点。

在 Clash 客户端的 **「 **<mark style="background-color:red;">**主页**</mark>** 」** 栏中，找到并打开 **「 **<mark style="background-color:red;">**系统代理**</mark>** 」** 选项。

此时电脑任务栏 Clash 图标由蓝色变成橙色，即成功开启了VPN代理。

![开启代理](https://pic.parkcloud.cc/i/2024/09/10/xzn7yz.gif)

{% hint style="danger" %}
**使用建议**

订阅地址是你个人账号密码及节点的总集成，不能泄露给任何人及网络，以防止他人使用及知晓你的密码。&#x20;

建议定期手动更新或者设置成每2小时自动更新订阅，即可保持与服务器同步更新。
{% endhint %}



## **更新订阅**

#### **1.关闭代理**

打开 Clash 客户端的 **「 主页 」** 将 **「 系统代理 」** 关闭（这一步很重要）

![关闭代理](https://pic.parkcloud.cc/i/2024/09/10/xzn9v6.gif)

#### **2.更新订阅**

打开 Clash 客户端的 **「 **<mark style="background-color:red;">**配置**</mark>** 」** 栏， 点击配置文件后面的 **「 **<mark style="background-color:red;">**刷新**</mark>** 」** 按钮即可成功更新订阅帕克云节点。

![更新订阅](https://pic.parkcloud.cc/i/2024/09/10/xzn9wn.gif)

{% hint style="danger" %}
**更新失败解决办法**

在 Clash 客户端的 「 配置 」 栏中右键删除 「 帕克云 」 的配置文件。

前往 「 [导入订阅步骤](clash-shi-yong-jiao-cheng.md#dao-ru-ding-yue) 」 根据教程一步一步操作，重新配置导入节点。
{% endhint %}

## **异常退出**

请注意，如果你在未退出Clash软件的情况下直接关机，可能会导致再次开机后网络无法使用的情况

此时重新打开Clash软件，**开启代理** 或 **退出应用** 即可正常使用网络
