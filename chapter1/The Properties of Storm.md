**Storm的特性**

在所有这些设计思想与决策中，有一些非常棒的特性成就了独一无二的Storm。

 - 简化编程

   如果你曾试着从零开始实现实时处理，你应该明白这是一件多么痛苦的事情。Storm使复杂性被大大降低了。

 - 支持多语言编程

    使用一门基于JVM的语言开发会更容易，但是你可以借助一个小的中间件，在Storm上使用任何语言开发。有现成的中间件可供选择，当然也可以自己开发中间件。

 - 容错

    Storm集群会关注工作节点状态，如果宕机了必要的时候会重新分配任务。

 - 可扩展
    
    所有你需要为扩展集群所做的工作就是增加机器。Storm会在新机器就绪时向它们分配任务。

 - 可靠的

    所有消息都可保证至少处理一次。如果出错了，消息可能处理不只一次，不过你永远不会丢失消息。

 - 快速

    速度是驱动Storm设计的一个关键因素。

 - 事务性

    你可以为几乎任何计算得到恰好一次消息语义。
