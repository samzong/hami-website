---
title: 贡献者阶梯
translated: true
---

本文档介绍了在项目中参与和提升的不同方式。您可以在贡献者角色中看到项目中的不同角色。

- [贡献者阶梯](#contributor-ladder)
  - [贡献者阶梯](#contributor-ladder-1)
    - [社区参与者](#community-participant)
    - [贡献者](#contributor)
    - [组织成员](#organization-member)
    - [审阅者](#reviewer)
    - [维护者](#maintainer)
    - [活跃的维护者应该](#an-active-maintainer-should)
    - [如何成为维护者](#how-to-be-a-maintainer)
    - [移除维护者](#removing-maintainers)
  - [不活跃](#inactivity)
  - [非自愿移除或降级](#involuntary-removal-or-demotion)

## 贡献者阶梯

您好！我们很高兴您想了解更多关于我们项目贡献者阶梯的信息！这个贡献者阶梯概述了项目中的不同贡献者角色，以及与之相关的责任和特权。社区成员通常从“阶梯”的第一级开始，并随着他们在项目中的参与度增加而逐步提升。我们的项目成员乐于帮助您在贡献者阶梯上进步。

以下每个贡献者角色都分为三种类型的列表。“责任”是指贡献者应履行的事项。“要求”是指一个人需要满足的资格条件，而“特权”是指该级别的贡献者有权享有的事项。

### 社区参与者

描述：社区参与者与项目及其社区互动，贡献他们的时间、想法等。社区参与者通常是那些不再匿名并开始积极参与项目讨论的用户。

* 责任：
  * 必须遵循 [CNCF 行为准则](https://github.com/cncf/foundation/blob/main/code-of-conduct.md)
* 用户如何参与社区：
  * 参与社区讨论
  * 帮助其他用户
  * 提交错误报告
  * 评论问题
  * 试用新版本
  * 参加社区活动

### 贡献者

描述：贡献者直接为项目做出贡献并为其增值。贡献不一定是代码。处于贡献者级别的人可能是新贡献者，或者他们可能只是偶尔贡献。

* 责任包括：
  * 遵循 CNCF 行为准则
  * 遵循项目贡献指南
* 要求（以下之一或多个）：
  * 报告并有时解决问题
  * 偶尔提交 PR
  * 贡献文档
  * 参加会议并做笔记
  * 回答其他社区成员的问题
  * 提交问题和 PR 的反馈
  * 测试版本和补丁并提交评审
  * 组织或协助组织活动
  * 在公共场合推广项目
  * 帮助管理项目基础设施
  * [待办事项：其他小贡献]
* 特权：
  * 受邀参加贡献者活动
  * 有资格成为组织成员

特别感谢[长长的名单](https://github.com/Project-HAMi/HAMi/blob/master/AUTHORS.md)中那些为项目做出贡献并帮助维护项目的人。没有你们的贡献，我们不会有今天的成就。谢谢！💖

只要您为 HAMi 做出贡献，您的名字将被添加到[这里](https://github.com/Project-HAMi/HAMi/blob/master/AUTHORS.md)。如果您没有找到您的名字，请联系我们添加。

### 组织成员

描述：组织成员是定期参与项目的既定贡献者。组织成员在项目存储库和选举中享有特权，因此他们被期望以整个项目的利益为重。

组织成员必须满足贡献者的责任和要求，并且：

* 责任包括：
  * 继续定期贡献，至少每年有 50 次 GitHub 贡献
* 要求：
  * 在其 GitHub 账户上启用[双因素认证]
  * 必须对项目或社区有成功的贡献，包括以下至少一项：
    * 5 个被接受的 PR，
    * 审核了 5 个 PR，
    * 解决并关闭了 3 个问题，
    * 成为关键项目管理领域的负责人，
    * 或其他等效的组合或贡献
  * 必须至少贡献 1 个月
  * 必须积极参与至少一个项目领域
  * 必须有两个赞助者，他们也是组织成员，其中至少一个不为同一雇主工作
  * **[在 HAMi-project/HAMi 仓库中打开一个问题][membership request]**
    - 确保您的赞助者在问题中被 @提及
    - 完成问题清单上的每一项
    - 确保所列贡献代表您在项目中的工作。
  * 让您的赞助审阅者回复赞助确认：`+1`
  * 一旦您的赞助者回复，您的请求将由 `HAMi GitHub 管理团队`处理。

* 特权：
  * 可以被分配问题和评审
  * 可以向 CI/CD 自动化发出命令
  * 可以被添加到 [待办事项：Repo Host] 团队
  * 可以推荐其他贡献者成为组织成员

贡献者成为组织成员的过程如下：

1. 联系维护者并获得至少两个维护者的同意
2. 提交一个申请成为成员的问题

### 审阅者

描述：审阅者负责特定的代码、文档、测试或其他项目领域。他们与其他审阅者共同负责审阅这些领域的所有更改，并指示这些更改是否准备好合并。他们在项目中有贡献和审阅的记录。

审阅者负责一个“特定领域”。这可以是特定的代码目录、驱动程序、文档章节、测试任务、事件或其他明确定义的项目组件，通常小于整个存储库或子项目。最常见的是一个或多个 Git 存储库中的一个或一组目录。以下的“特定领域”指的是这个责任领域。

审阅者拥有组织成员的所有权利和责任，并且：

* 责任包括：
  * 遵循审阅指南
  * 审阅大多数针对其特定责任领域的拉取请求
  * 每年至少审阅 20 个 PR
  * 帮助其他贡献者成为审阅者
* 要求：
  * 至少有 3 个月的贡献者经验
  * 是组织成员
  * 已审阅或协助审阅至少 10 个拉取请求
  * 已分析并解决其特定领域的测试失败
  * 展示了对特定领域的深入了解
  * 承诺对该特定领域负责
  * 支持新的和偶尔的贡献者，并帮助使有用的 PR 准备好提交
* 额外特权：
  * 拥有 GitHub 或 CI/CD 权限以批准特定目录中的拉取请求
  * 可以推荐和审阅其他贡献者成为审阅者

成为审阅者的过程是：

1. 通过在适当的存储库中打开一个 PR 提名贡献者，将他们的 GitHub 用户名添加到一个或多个目录的 OWNERS 文件中。
2. 至少两个已经是批准者的团队成员批准该 PR。

### 维护者

描述：维护者是非常成熟的贡献者，负责整个项目。因此，他们有能力批准针对项目任何领域的 PR，并被期望参与项目战略和优先事项的决策。

维护者必须满足审阅者的责任和要求，并且：

当前维护者列表可以在 [MAINTAINERS](https://github.com/Project-HAMi/HAMi/blob/master/MAINTAINERS.md) 中找到。

### 活跃的维护者应该

* 积极参与审阅拉取请求和处理新问题。请注意，没有关于什么是“足够活跃”的硬性规定，这取决于当前维护者小组的判断。

* 积极参与关于项目设计和未来的讨论。

* 负责他们批准和合并的 PR 的适当分支的回溯。

* 尽力遵循所有代码、测试和设计惯例，这些惯例由活跃维护者之间的共识决定。

* 当他们不再计划积极参与项目时，优雅地退出他们的维护者角色。

### 如何成为维护者

新维护者由当前维护者小组通过共识添加。这可以通过 Slack 或电子邮件的私人讨论进行。大多数维护者应支持添加新成员，并且没有单个维护者反对添加新维护者。

在添加新维护者时，我们应提交一个 PR 到 [HAMi](https://github.com/Project-HAMi/HAMi) 并更新 [MAINTAINERS](https://github.com/Project-HAMi/HAMi/blob/master/MAINTAINERS.md)。一旦这个 PR 合并，您将成为 HAMi 的维护者。

### 移除维护者

由于其他责任，维护者的来去是正常的。如果没有持续参与的预期，可能会移除不活跃的维护者。如果前维护者恢复参与，他们应被快速考虑重新加入团队。

## 不活跃

对于贡献者来说，保持活跃以树立榜样并展示对项目的承诺是很重要的。不活跃对项目有害，因为它可能导致意外的延迟、贡献者流失以及对项目的信任丧失。

* 不活跃的衡量标准：
  * 超过 3 个月没有贡献的时期
  * 超过 3 个月没有沟通的时期
* 不活跃的后果包括：
  * 非自愿移除或降级
  * 被要求转为名誉状态

## 非自愿移除或降级

当贡献者未能履行责任和要求时，会发生非自愿移除/降级。这可能包括重复的不活跃模式、长时间的不活跃、未能满足角色要求的时期和/或违反行为准则。这个过程很重要，因为它保护了社区及其交付物，同时也为新贡献者提供了介入的机会。

非自愿移除或降级通过当前维护者的多数投票处理。

[双因素认证]: https://help.github.com/articles/about-two-factor-authentication