--- 
layout: post
title: 图形无处不在，或者正如我们所知道的图形数据库的诞生
tags: 
- 图数据库
- Graph Database
status: publish
type: post
published: false
top: false
---

现在是1999年，每个人都工作了23个小时。至少它是这样感觉的。似乎每天都会有一个疯狂的想法，只需要数百万美元的资金。&nbsp;我们所有的竞争对手有数百名工程师，我们是一个20人的开发团队。好像这还不够，我们10的工程师把大部分时间花在和关系数据库打交道上。
我们花了一段时间才明白为什么。当我们深入深入研究企业内容管理应用的持久层时，我们意识到我们的软件不仅管理大量的单独的、孤立的和离散的数据项，而且还管理它们之间的连接。虽然我们可以很容易地将离散数据拟合在关系表中，但连接的数据存储更具挑战性，并且查询速度非常慢。
出于纯粹的绝望，我的两个新的合作者，Johan和彼得，和我开始试验其他数据模型，特别是围绕图的模型。我们被认为有可能用图表为中心的模型来代替表格的SQL语义，这对于开发人员在导航连接的数据时更容易使用。我们意识到，拥有一个图形数据模型，我们的开发团队可能不会浪费一半的时间来对抗数据库。
当然，我们对自己说，我们在这里不可能是独一无二的。图论已经存在了将近300年，并且由于其广泛适用于许多不同的数学问题而闻名。当然，必须有数据库支持图形！ 

嗯，我们在AltaVistad的年轻网站上找不到任何东西。经过几个月的调查，我们（天真地）开始从头开始构建一个以图表为单位工作的数据库。我们的愿景是保持从关系数据库（事务、ACID、触发器等）证明的所有特征，但是在二十一世纪使用数据模型。Project Neo诞生了，我们现在还使用了图形数据库。
新千年的第一个十年经历了几次世界变化的新生活，包括谷歌、脸谱网和Twitter。它们之间有一个共同的线程：它们把连接的数据图表放在业务的中心。15年后，图表到处可见。
例如，脸谱网是建立在这样一种理念上的：尽管人们对他们的名字、他们所做的事情等离散信息有价值，但在它们之间的关系中更有价值。脸谱网创始人马克·扎克伯格建立了一个帝国的洞察力捕捉这些关系在社会图。
同样，谷歌的拉里·佩奇和塞吉·布林发现了如何存储和处理不只是离散的Web文档，而是如何将这些Web文档连接起来。Goo-GLE捕获了网络图，这使得他们可以说是前十年最具影响力的公司。
如今，图形已经成功地应用于网络巨头之外。世界上最大的物流公司之一使用实时的图形数据库来路由Pys的包裹；一个主要的航空公司利用它的媒体内容元数据的图形；一个顶级的金融服务公司在NeN4J上重写了它的完整的权利基础设施。LLY在几年前未知，图形数据库现在被应用于各种各样的行业，如医疗、零售、石油和天然气、媒体、游戏等等，每一个迹象都表明它们已经加速了其爆炸性的步伐。
这些想法应该得到一种新的工具：通用数据库管理技术，它拥抱连接的数据并启用图形思维，这是我希望在1999返回战斗数据库时所能提供的工具。

我希望这本书可以作为一个伟大的介绍这一美妙的新兴图形技术世界，我希望它会激励你开始使用图形数据库在你的下一个项目，这样你也可以解锁非凡的力量的图表。祝你好运！

—Emil Eifrem Cofounder of Neo4j and CEO of Neo Technology Menlo Park, California May 2013