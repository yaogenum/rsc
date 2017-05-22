# rsc
resource service control
## test add zk serser

## operate zk

开发一个公开小规模资源中心,提供以下服务


## 资源网关中心

### 不管是企业还是初具规模的应用,当流量上涨或者存在多个系统调用,不可避免会遇到应用管理,权限控制,API权限以及流控,以及上下文日志管理,分布式环境下状态一致性服务,因此,此项目旨在自身用于学习,更多的是能够做一些事情.

#### (兴趣之外,使用此项目进行JAVA的WEB应用初步学习也是可以的哈)

 1.资源的流量控制

 2.资源的访问权限控制

 3.应用身份识别

 4.日志访问

 5.分布式一致性服务

 6.提供一个开源的资源中心DEMO


design by snapsot 2017.05.22

1.console service by spring boot httpService

2.paxos&zk provide consistent service

3.baseof bucket/rateLimit/leaky,we will provide api limit

4.Hbase store your log

5.quiky learn java web 

