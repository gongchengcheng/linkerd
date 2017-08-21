# Linkerd是什么?

Linkerd是一个用于云原生应用的开源可扩展服务网格。

Linkerd旨在解决我们在Twitter，Yahoo，Google和Microsoft等公司运营大型生产系统时发现的问题。根据我们的经验，最复杂，令人惊奇和紧急行为的来源通常不是服务本身，而是服务之间的通讯。Linkerd解决了这些问题，不仅仅是控制通讯机制，而是在其上提供一个抽象层。

![](images/diagram-individual-instance.png)

**Linkerd为现有应用增加可靠性和仪器仪表**

通过提供跨服务的一致，统一的仪器仪表和控制层，linkerd 可以让服务所有者自由选择最适合其服务的语言。通过分离通讯机制与应用代码，linkerd 可以让您可以对这些机制进行可视化和控制，而无需更改应用本身。

今天，世界各地的公司都使用 linkerd 来加强软件基础设施的核心。Linkerd 负责跨服务通信的困难而容易出错的部分，包括延迟感知负载平衡，连接池，TLS，仪器仪表和请求级路由——让应用代码具备可伸缩性，高性能和弹性。