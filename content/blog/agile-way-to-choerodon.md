+++
title = "Choerodon的敏捷之路"
date = "2018-03-15"
autor = "choerodon"
tags = ["agile"]
categories = ["技术类"]
+++

敏捷管理是基于用户需求的演变为中心，通过迭代的方式来进行的软件开发。

<!--more-->
关于软件开发，我们现在可以找到很多前人的经验，包括已经存在方法论和工具，这之间其实很难说哪个方法论是正确的，或是哪个工具是最好用的；其实开发是“任性的”，它没有定律，如人饮水冷暖自知，其过程是否高效，除了团队的实力这个决定性因素之外，还取决于整个开发的流程是否是清晰的。高效总是伴随着清晰而来，清晰的目标，清晰的计划，清晰的职责……

Choerodon认为软件交付的过程本质是用户价值的实现，而用户价值的实现是通过用户价值的流动来体现的，Choerodon提供了一套工具来帮助用户通过敏捷的方式来管理用户价值的流动，管理和规范化整个软件开发流程。

Choerodon敏捷管理的核心是需求，计划和执行。即通过故事地图、用户故事来管理用户故事和发布计划，通过迭代来管理冲刺，最后通过看板来可视化冲刺的执行。


![](/img/blog/2018/march/agile-1.jpg)

## 故事地图
故事地图已经成为敏捷管理在需求规划中的一个重要的方法。Choerodon的故事地图可以将你的用户故事（user stories）像地图一样展现出来，而不是传统的简单列表形式。故事地图之所以重要是因为：

*	让你更容易看清整个项目的规划，所有的product backlog
*	为新功能筛选（grooming）和划定优先级提供了更好的工具，帮助你做出决策
*	便于使用头脑风暴或其他协作方式来产生用户故事
*	帮助你更好的进行迭代开发，同时确保早期的发布可以验证整体架构和解决方案
*	对于传统的项目计划，如：传统产品需求文档（PRD）提供了一个更好的替代工具
*	有助于激发讨论和管理项目范围
*	允许你从多个维度进行项目规划，并确保不同的想法都可以得到采纳

### 创建故事地图的8个步骤：

1.	在公司或部门内找到最熟悉我们要开发的产品领域3-5人。之所以将范围定在3-5之间。因为少于三人很大程度上你没法得到足够的建议，而多于五人则讨论和协调会浪费很多时间，降低会议效率。
2.	使用头脑风暴模式，让每个人在便签纸上写下自己认为重要的“所要做的事情”也就是用户任务（user task）。每个人都用同样颜色的便签来书写自己的用户任务描述，这个阶段不要互相讨论。一旦大家都基本完成了准备，让每个人轮流大声读出自己的内容，并把便签纸全部放置在桌面上，这时如果出现重复的内容就可以省略掉：

    *   根据你的产品规模不同，这个过程可能需要3-10分钟的时间，通过观察实际状况而定。
    *	这些便签组成了一级用户故事，Jeff Patton称为用户任务（user tasks）。
    *	我们可以提示参与者：我们只用了很少的时间就完成了需求的收集过程，而且有些你可能没有想到内容，其他人帮你想到了。

3.	将桌面上所有的便签进行分组，将类似的任务分为一组。

    *	分组过程最好不要以讨论的模式进行，速度会更快。如果发现重复的内容，就略过；
    *	这时同样观察每个人的行为，判断大家是否已经做完，基本上这个过程需要2-5分钟

4.	选择另外一个颜色的便签，对分好每个组进行命名，贴在每组便签的上部
5.	对这些分好组的便签进行排序，一般按照用户完成操作的顺序，或者是其他的方式等，从左到右摆放

    *	如果大家无法决定顺序，那么顺序可能没有那么重要（明显）。
    *	这一组便签，Jeff Patton称为 用户活动 （User Activities）
    *	这时你的地图应该类似于

    ![](img/blog/2018/march/agile-2.jpg)

1.	现在，从粉色便签这行开始讲述用户故事，确保你没有遗漏任何用户活动和用户任务。这时一般由组织者来进行讲述，其他人提出意见，甚至可以让最终用户来参与讨论。
2.	以上我们已经完成了用户故事地图的基本框架；可以在每个用户任务下面添加更加细节的用户故事（User Stories）了。我们仍然建议使用头脑风暴的模式来进行第一轮用户故事的产生，同时可以借助如Persona和Scenario等方式协助完成这个过程。当我们完成了用户故事的创建，就可以开始划定发布计划（Releases）。
    *	在第一个发布计划中只选择每个用户任务的2-3个用户故事。这对于帮助大家排定优先级和范围将很有帮助。
    *	通常情况我们不必使用用户故事的标准句法来书写这些故事，因为每张便签都处于我们的地图的特定位置，很容易识别其所处的场景和角色。
3.	最后，针对第一个发布的所有用户故事进行分解，确保我们的第一个发布越小越好，基本上你需要保证在1-2个迭代后就可以发布你产品的第一个版本。

## Choerodon故事地图样例

![](/img/blog/2018/march/agile-3.jpg)

![](/img/blog/2018/march/agile-4.jpg)

*	第二行所包含的内容就是“相应的角色对应的活动”，包括类似：用户角色管理，服务管理等等。
*	第一行说明有哪几类不同角色。
*	橙色和蓝色标签包含了目前整个项目整体规划的所有用户故事，但会随着项目进行进行适当调整和完善。

现在如果我们专注于完成导入冲刺的橙色便签，我们就可以确保很快发布一款具有用户价值小功能的产品。这样我们就可以验证我们正在开发或修改的小功能点（如：去掉发布管理员，将服务发布权限更改等）可行。同时也可以帮助我们对系统的功能进行端到端的测试，确保我们可以从用户处获取到反馈，知道我们是否解决了它们的问题（提供了商业价值）。

## Choerodon用户故事样例

![](/img/blog/2018/march/agile-5.jpg)


*	点击“+”，查看每个用户故事（user stories）的相关用户任务（user tasks）有哪些。
*	直接清晰看到用户故事相应负责人
*	用户故事（user stories）可以根据优先级自上而下排列，大家可以根据优先级和状态进行评估，对开发进程进行适当的调整。

## 迭代

用迭代来管理冲刺，每一个迭代对应一次冲刺，也可以简单理解为每一次冲刺就是一个迭代周期。在固定的时间内，要完成需求分析、设计、实现、测试等一系列活动，在迭代周期完成的时候提供一个可工作的产品(Release/Report)。每一次迭代完成的可能是一个或几个完整的用户故事，也可能是一个用户故事（user story）中的若干用户任务（user tasks）。

敏捷方法很重视稳定的迭代节奏，Simon Baker描述说："就像心脏有规律地跳动来保持身体运行，固定的迭代长度提供了一个恒量，有助于建立开发和交付的节奏。根据我的经验，节奏是帮助取得不变的步幅的重要因素"（2004）。对于敏捷开发的团队而言，稳定的迭代节奏可以让产品保持更稳定的交付。

那我们要如何找到适合自身的迭代后期，我们可以从以下6各方面考虑：

1. 整个项目周期长度（完成计划的商业需求所需时间），较短的迭代周期将会有以下一些优点和缺点
    *	更频繁的向客户展示/交付可用的软件，更频繁的取得反馈并改进，一般大的项目最好有3次或以上获取反馈、修正的机会，错误能被尽快发现从而不会酿成大错；
    *	迭代周期缩短，团队没有能力保证作出的每一个决定都正确，很多开销都必须花在试错上；Scrum 团队的抗风险能力弱于瀑布模型团队，因为一个人的离职或病假都可能对单一功能的进度造成影响
2. 不确定性，客户需求的不确定，团队的工作效率，或者技术难度存在不确定性，总而言之，不确定性越多，迭代周期越短。
3. 获得反馈的难易程度
4. 迭代周期内优先级是否被改变，也是选择迭代长度时需要考虑的因素。
5. 迭代的系统开销，每次迭代的成本（时间），在测试过程中我们要花费的时间。
6. 团队成员的压力，选择一个合适的迭代周期长度，让团队成员在整个迭代过程中感受到的压力尽可能平均。

根据每个团队的实际情况，一般建议2~4周。在我们的实践中，通常以1-2周一次迭代的频率，保持相对稳定的开发和交付的节奏。

## Choerodon冲刺样例

![](/img/blog/2018/march/agile-6.jpg)

*	清晰展现当前迭代的完成度，以及总工作量。
*	可以根据优先级和状态进行评估，对当前迭代进程进程进行整体把控。

## 看板

看板方法是用于高效管理软件开发流程的新技术。看板方法源自丰田的“及时生产”（JIT=just-in-time）系统。尽管生产软件是一项创造性活动，与批量生产汽车有所不同，但是生产线管理背后所蕴含的原理仍然适用。

一个软件开发的流程可以看作是一段自来水管道，特性需求从一端进入，经过改进的软件从另一端涌现出来。

在管道内部，存在着各种各样的工序，有的是非正式的临时工序，有的是非常正式的阶段性流程。在本文中，我们假设一个简单的阶段性流程：(1)分析需求，(2)开发代码，(3)测试软件运行正常。

Choerodon的看板是Choerodon敏捷管理中执行部分，它的核心作用是可视化整个迭代的计划执行，并且暴露开发执行过程中的短板或者瓶颈。我们都知道在软件开发过程中，短板或者瓶颈会直接的影响整个开发进程。

例如，如果测试人员每周只能测试5个特性，而开发人员和分析人员每周能够生产10个特性，整个管道的吞吐量就只有每周5个特性 ，因为测试人员扮演了瓶颈角色。如果分析人员和开发人员不知道测试人员是瓶颈，那么测试人员的待办工作就会越堆积越多。

影响就是前置时间增加。并且，就如同库存一样，位于管道中的工作会套牢投入的资金、产生与市场的距离、以及随着时间逐渐失去价值。

最终，影响到质量。为了能够跟上进度，测试人员开始抄近路。最终bug被发布到产品中，导致给用户带来问题，从而影响未来的管道产能。

![](/img/blog/2018/march/agile-7.jpg)

另一方面，如果我们知道哪里有瓶颈，我们就能够重新部署资源来解除它。例如，分析人员可以帮忙测试，开发人员开始进行自动化测试。

但是，我们怎样才能知道在已知流程中哪里是瓶颈呢？而当瓶颈移动后会发生什么呢？

### 看板方法可以动态显示瓶颈
看板方法难以想象的简单，但却难以想象的强大。最简单的形式的看板系统包括了一个挂在墙上的大白板，上面有许多卡片或即时贴，这些即时贴按列来放置，每列上方有一个数字。

你之所以能找到这些瓶颈，是因为限制了在制品（work-in-progress, WIP）的数量会显示出瓶颈。
卡片代表了工作项，列代表了开发工序，卡片会从第一步工序流动到最后一步。每一列顶部的数字用来限制每一列最多允许放置卡片的数量。

看板白板的限制大相径庭于其他任何可视化故事板。在流程中的每一步限制在制品（WIP）数量，可以预防生产过剩并动态显现出瓶颈，以便于你可以在达到不可收拾的程度之前找到它们。

![](/img/blog/2018/march/agile-8.jpg)

#### Choerodon的看板

注意，我们已经将一些列分割成了两列，这是为了用来说明正在进行中的项与哪些已经完成并准备好被下游工序拉走的项。你也可以用一些不同的方式来布局白板。这里用的是比较简单的方式。列顶部的限制包含了“doing”（进行中）和“done”（完成）两列。

一旦测试人员完成了一个特性的测试，就会将卡片移走，并且在“测试”列空闲出一个卡片位置。

![](/img/blog/2018/march/agile-9.jpg)

现在，“测试”列中空出来的位置可以用开发“Done”列中的一个卡片补充进来。这时，“开发”列就会空闲出一个卡片位置，下一张卡片就可以从“分析”列中拉进来，其他列也是这样。

![](/img/blog/2018/march/agile-10.jpg)

敏捷管理过程中，看板的使用和敏捷会议流程往往是相辅相成的，常见的主要有以下四种会议

1. 计划会（一）：

参与人员：Product Owner、Scrum Master、团队成员，也可以邀请业务人员一起参加。
会议时长：1-4小时

根据确定好的故事地图和用户故事，我们通过计划会议，确定迭代的目标、团队成员、形成本次迭代的Sprint Backlog，同时明确评审会、回顾会时间；
确定Sprint Backlog确定工作量（工作时间）；

1. 计划会（二）

参与人员：Product Owner、Scrum Master、团队成员，其他人员选择性参加
会议时长：1-4小时

  * 团队成员共同拆解细化sprint backlog，拆解为若干tasks；
  * 共同进行工作量评估，可以按照天或小时来评估；
  * 团队成员自主选择任务，共同确定DoD完成标准，团队内部达成一致；

如果单个迭代内安排的Product Backlog安排的比较多的话，一般迭代计划会议需要开一个整天，虽然时间有点长，但这个会议会确认整个迭代的详细计划和安排，使开发流程变清晰

1. 每日站会

团队每天进行沟通的内部短会，一般只有10-15分钟，团队成员通常会在会议上讲述昨天的工作，今天计划做了什么以及遇到的问题，这些问题由专人记录，但不在站会上讨论。站会之后找相关的人讨论和解决。

1. 敏捷迭代评审会议

参与人员：产品经理、Product Owner、Scrum Master、团队所有成员
会议时长：1-4小时，视演示内容而定

在冲刺结束前给产品负责人演示并接受反馈和建议，提出新的产品Backlog，主要是检验成果，看是否完成本次迭代的目标，可以邀请用户参与测试流程，并征询客户的意见和想法。
由Scrum Master来推进会议进程，Product Owner进行会议记录，这些意见和反馈维护产品 backlog，一般在迭代结束前做一次。

1. Sprint Retrospective敏捷迭代回顾会议

参与人员：Scrum Master，Product Owner，团队成员。
会议时长：1-2小时

每个迭代结束后，关于团队自身如何做出改进如何优化产品的会议，团队成员自由讲述关于这次冲刺需要保持的做法，改进的点以及持续跟踪计划。找出本次冲刺中做的好的方面继续坚持，对于做得不好或者可以更好的方面持续改进。并选择出下一个迭代我们要完成的sprint backlog。

Scrum Master或者Product Owner，对于讨论内容整理成会议记录，并发送给整个团队和有关同事。

这四个会议会伴随着每一次冲刺，每一个团队在每个冲刺的执行过程当中不断学习发现和总结经验，找到最适合自身的方法，使团队真正的敏捷起来。
