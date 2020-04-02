# 部署

**部署就是将 Parse Server  预装包在线复制到你的云服务器中**。例如：用户在云平台购买 Parse Server  之后，云平台就会自动将 Parse Server  复制到对应的云服务器。

- 如果已经部署 Parse Server ，请进入[初始化安装](/zh/stack-installation.md) ，完成相关操作。
- 如果没有部署 Parse Server ，需要先将 Parse Server  部署到您的云服务器。

我们提供了两种部署 Parse Server  方案（部署结果是一样的）：

## 镜像部署

**镜像部署**就是用户基于镜像来创建云服务器，从而获得与镜像一致的系统环境。**镜像**是指云服务器可选择的运行环境模板，一般包括操作系统和预装的软件。

对有云服务器使用经验的用户来说，镜像部署可以等同于“一键部署”。

我们在主流的云平台上发布了 [Parse Server  镜像](https://apps.websoft9.com/parse)供用户使用。云平台一般支持三种镜像部署方式：

* 在 **选购新服务器** 的时候，找到并选取 Parse Server  镜像作为服务器启动环境
* 在 **云市场（Marketplace）**  的 Parse Server  商品页面直接购买镜像
* 对于已有服务器，通过 **更换镜像（重装系统）** 的操作，将已有镜像替换为 Parse Server  镜像。

## 脚本部署

**脚本部署**是指在云服务器上运行一段脚本程序，一边将预装包在线下载到云服务器，一边预配置

我们在 Github上发布了 [Parse Server  自动化部署脚本](https://github.com/Websoft9/ansible-parse-server)，脚本基于 Ansible 编写。只要熟悉 Ansible，便可以实现无人值守的方式将 Parse Server  部署到服务器。

## 对比

虽然通过镜像部署与脚本部署的结果一致，这两种部署方式有什么差异或优劣呢？：

建议立即阅读 [《镜像部署 vs 脚本部署》](https://support.websoft9.com/docs/faq/zh/bz-product.html#镜像部署-vs-脚本部署)