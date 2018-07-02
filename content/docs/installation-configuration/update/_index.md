+++
title = "升级指南"
description = "详细描述了意见部署和分步部署的各版本升级的要求与步骤"
weight = 9
icon = "icon-update"
+++

## 升级指南

一键部署与分布部署都请参照本升级指南进行升级，升级时执行升级命令的主机可以通过kubectl管理集群且安装有helm命令行。请按顺序依次进行升级部署，请不要随意调整升级顺序。升级后可能数据库结构会发生改变，故不能进行版本回退。文档升级命令中的RELEASE NAME是在基于分步安装文档之上编写的，若你在安装时指定了其他RELEASE NAME，请以你安装时指定的RELEASE NAME为准。一键部署安装的请执行helm list命令查看RELEASE NAME。

---

{{< docdir >}}