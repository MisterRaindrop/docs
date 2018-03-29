# 开发指南

* [*您是第一次使用 HashData 数据仓库么？*](#1)

* [*您是数据库开发者么？*](#2)

* [*阅读前需要做的准备工作*](#3)

## <h2 id='1'> 您是第一次使用 HashData 数据仓库么？

如果您是第一次使用 HashData 数据仓库，我们强烈建议您先阅读下面的内容。

* [入门指南](../010-getting-started-guide/README.md) －包含了完整的示例，从创建 HashData 数据仓库集群，到创建数据库中的表，加载数据到最后的测试查询及验证结果。

* [管理指南](../020-admin-guide/README.md) －集群管理手册为您介绍如何创建和管理HashData 数据仓库集群。

如果具有其它关系型数据库或者数据仓库应用的经验，那么您需要注意 HashData 数据仓库与其它产品的设计和实现区别。您可以参考最佳实践章节来了解和学习如何更好地使用 HashData 数据仓库来加载数据和设计表结构。

HashData 数据仓库是基于 greenplum 和 postgres 开发的。

## <h2 id='2'> 您是数据库开发者么？

如果您是一位数据库用户，数据库设计者，或者数据库开发者，又或是数据库管理员，请参考下面表格，来帮助您快速定位您所需要查找的相关信息。

| 您需要的信息 | 推荐参考 |
| :--- | :--- |
| 快速地创建并使用 HashData 数据仓库 | 通过 [入门指南](../010-getting-started-guide/README.md) 介绍，快速的了解部署集群， 连接数据库和尝试一些最简单数据加载和查询。在您熟悉 HashData 数据仓库后，准备搭建您的数据库，将数据导入到表中，在数据仓库中使用查询操作 数据时，再回到本手册了解更多内容。 |
| 了解和学习 HashData 数据仓库的内部架构 | [HashData 数据仓库系统概述](./020-hashdata-shu-ju-cang-ku-xi-tong-gai-shu.md) 为您介绍 HashData 数据仓库内部架构的宏观概述。 |

## <h2 id='3'> 阅读前需要做的准备工作

在正式阅读文档前，您可以完成下面的任务来加速您对 HashData 数据仓库理解和掌握：

* 安装一个 PSQL 客户端程序
* 启动一个 HashData 数据仓库集群 
* 使用 PSQL 客户端程序连接到集群的 master 节点

如果您需要关于上面步骤的相关操作帮助，请参阅：[入门指南](../010-getting-started-guide/README.md)。

您最好了解 SQL 客户端程序的使用方法，并掌握一些基础的 SQL 语言知识。
