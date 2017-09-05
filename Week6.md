# Week 6

<br />
<hr>
This week is talking about SOA
<hr>
<br />
<hr>

<hr>

<br />

## SOA

* Service-Oriented Architecture (SOA) is an ICT architecture model
* Interoperability is the most important principle of SOA
* Service blueprinting -> Capture requirements and clarifying client's and engineer's concepts
* Provided over a network, middleware and enterprise service bus (ESB)
* black box for consumers
* may consist of other underlying services
* self-contained

### Advantages

* improved interoperability
* services are independent and do not depend on the context or state of the other services -> reusable
* Information consistency
* Reducing impact of change
* flexible business processes

### Loose coupling

* Tight coupling is a technique in which hardware and software components are highly dependent on each other
* Loose coupling allows us to reduce the inter-dependencies
  <br />
  <br />

## Service

### Categories

* Service providers
* Service requestors
* Intermediarry services -> retransmit messages along the routes between service requestors and service providers

<br />

### Web service

* XML
* Semantic, technical and organisational interoperability
* Enable loose coupling
* Reduce development times
* Reduce maintenance costs


<br />
<br />

### SOA adv/dis

* SOAs encourage reuse, composability & interoperability of Service Handlers
* SOAs bring a service provision mentality to systems developers
* can be readily implemented using legacy systems
* ============================
* SOAs introduce another level of complexity and specification / message handling
* Current web applications work okay
* SOAs require a change in design philosophy and a focus on a new service paradigm
* SOAs require new tools and interfaces that may not yet been fully implemented for all systems

<br />

## ESB 

即企业服务总线。它是传统中间件技术与XML、Web服务等技术结合的产物。ESB提供了网络中最基本的连接中枢，是构筑企业神经系统的必要元素。ESB的出现改变了传统的软件架构，可以提供比传统中间件产品更为廉价的解决方案，同时它还可以消除不同应用之间的技术差异，让不同的应用服务器协调运作，实现了不同服务之间的通信与整合。从功能上看，ESB提供了事件驱动和文档导向的处理模式，以及分布式的运行管理机制，它支持基于内容的路由和过滤，具备了复杂数据的传输能力，并可以提供一系列的标准接口

* An Enterprise Service Bus is the service interface of an SOA, extended to a whole of enterprise
* The core concept of the ESB architecture is to integrate different applications by putting a communication bus between them & then enable each application to talk to the bus
* Messages may be also be transformed from a source format into a target format as they pass through the bus
* Monitor service usage, error rates, security attacks, redundant/disused services
* Intelligent routing
* Real time monitoring
* Service Security
* Easy to change components or add additional components
* load balancing
* ​
* ====================
* Expensive
* challenge in the ESB concept is there is no single accepted standard for features or behaviour
* A single point of failure

<br />
<br />

### Difference between SOA & ESB

* SOA is just like a car and ESB is like a road on which this car runs -> ESB helps SOA
* SOA is way of building the next generation of applications from ‘lego blocks’ called Services whereas ESB is a piece of
  infrastructure software that provides APIs for developers to create services and send messages between services
* SOA is an architectural approach where we use ‘services’, whereas ESB is a technical implementation that aids in delivering a SOA.
* SOA brings cost effective, reusable and low lead time solutions to an organisation whereas ESB enables low cost integration


<br />
<br />

## Enterprise System

* Enterprise systems (Also known as enterprise resource planning-ERP-system) are typically built around thousands of predefined business processes and applications that reflect best practices in business
* Enterprise Systems are evolving into Integrated Enterprise Systems, focusing on interconnection, data interchange and distributed environments.
* Enterprise systems are quickly evolving from monolithic silos to distributed applications with SOA
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
  <hr>
  END