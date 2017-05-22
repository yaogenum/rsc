##项目介绍:资源中心

   不管是企业还是初具规模的应用,当流量上涨或者存在多个系统调用,不可避免会遇到应用管理,权限控制,API权限以及流控,以及上下文日志管理,分布式环境下状态一致性服务,因此,此项目旨在自身用于学习,更多的是能够做一些事情.


##资源中心功能介绍

 1.资源的流量控制

 2.资源的访问权限控制

 3.应用身份识别

 4.日志访问

 5.分布式一致性服务

 6.提供一个开源的资源中心DEMO



##资源中心的设计简叙

  (design by snapsot 2017.05.22)

 1.console service by spring boot httpService

 2.paxos&zk provide consistent service

 3.baseof bucket/rateLimit/leaky,we will provide api limit

 4.Hbase store your log

 5.quiky learn java web


##更多想说的是

   希望通过这个项目,梳理和落地从2012~2017这几年来从学校到工作,自己所学的,所做的,所听的,能够将其中一部分以工程的形式体现出来,也希望能够节省同样的开发者在遇到同样的问题的时候
能够快速复制,或者找到更好的解决方案.

                                                   open and share @snapshot 2017
