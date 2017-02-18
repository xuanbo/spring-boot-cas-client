# spring-boot-cas-client

spring boot 集成 cas 作为 cas-client

## 1快速入门

### 1.1配置cas-server

自己到官网下载cas，然后部署。我没有配置ssl，可能是jdk导出的证书问题。

*提示：*如果需要，我可以提供`cas-4.0.0`或`cas-5.0.2`的zip。`QQ：1345545983`

### 1.2配置cas-client

本项目实际上就是一个`cas-client`，修改`application.yml`中的配置。

### 1.3cas-client获取当前用户

看CasUserDetailsService类就明白了。

## 参考

* [玩转Spring Boot 使用Spring security 集成CAS](http://blog.csdn.net/cl_andywin/article/details/53998986)
* [CAS环境搭建](http://blog.csdn.net/cl_andywin/article/details/53222858)