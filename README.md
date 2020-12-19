# Proposal: TiCockpit

> WIP: 这篇文档仍在建设中

- Author(s): [STRRL](https://github.com/strrl), [lrrtuising](https://github.com/lrrtuising)
- Last updated:  2020-12-19
- Discussion at: https://github.com/fantastic-things/ticockpit-proposal/issues/new

非常感谢 @disksing 提供的灵感与思路!

## Abstract

TiCockpit 是一款虚拟现实~~游戏~~运维套件, 它允许 DBA 能够使用 VR 设备直观地观测 TiDB 集群的指标, 它能带来以下好处:

- 沉浸式的运维体验
- 直观的操作反馈
- ~~提高运维效率~~
- ~~让 DBA 爱上运维~~

## Background

> 此段内容引用自 https://disksing.com/hackathon-idea/ 

缘起很简单，就是想优化一下我们TiDB技术支持的体验。我们先分析一下，我们DBA在支持客户的时候，最大的痛点是什么呢？

是频繁的扩容缩容吗？
是复杂冗长的运维操作步骤吗？
是繁琐漫长的问题诊断吗？
显然对于现在的TiDB来说，这些都不是事儿。

根据马斯洛需求层次理论，当基本的生理和安全需求被满足了之后，人们就需要去满足更高级别的精神级别的需求。

因此，我大胆断定，现在对于TiDB的DBA来说，运维TiDB最大的问题就是：不够酷炫，不够嗨！

所以我们来搞一些设施，让运维体验嗨皮起来！

项目的名字叫“TiDB驾驶舱”，大致就是一个座舱，要运维集群的时候就直接坐进去，大家可以想象一下下面这两张图的结合形态。

![驾驶舱示意图](https://disksing.com/assets/img/hackathon-1.jpg)

TiDB驾驶舱，让你运维TiDB集群有如在开歼-20的感觉！

## Proposal

<!--
A precise statement of the proposed change:
- The new named concepts and a set of metrics to be collected in this proposal (if applicable)
- The overview of the design.
- How it works?
- What needs to be changed to implement this design?
- What may be positively influenced by the proposed change?
- What may be negatively impacted by the proposed change?
-->
我们计划使用 Google Cardboard 与 Unity XR 共同打造一款虚拟现实运维套件.

具体细节待补充.

## Rationale

具体细节待补充.
<!--
A discussion of alternate approaches and the trade-offs, advantages, and disadvantages of the specified approach:
- How other systems solve the same issue?
- What other designs have been considered and what are their disadvantages?
- What is the advantage of this design compared with other designs?
- What is the disadvantage of this design?
- What is the impact of not doing this?
-->

## Compatibility and Mirgration Plan

该项目适用于使用 tidb-operator 托管的 tidb 集群.

## Implementation

具体细节待补充.
<!--
A detailed description for each step in the implementation:
- Does any former steps block this step?
- Who will do it?
- When to do it?
- How long it takes to accomplish it?
-->

## Testing Plan

¯\\_(ツ)_/¯
<!--
A brief description on how the implementation will be tested. Both integration test and unit test should consider the following things:
- How to ensure that the implementation works as expected?
- How will we know nothing broke?
-->

## Open issues (if applicable)

¯\\_(ツ)_/¯
<!--
A discussion of issues relating to this proposal for which the author does not know the solution. This section may be omitted if there are none.
-->