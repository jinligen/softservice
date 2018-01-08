# softservice
基于SpringCloud的微服务框架，实现了微服务的基本模块，持久层框架采用基于注解的mybatis，oauth2的授权码，access_token存放在redis中
## eureka
服务的注册与发现
## ribbon
负载均衡器，实现了断路器功能
## feign
负载均衡器，集成了ribbon框架，实现了断路器功能
## zuul
服务网关
## config
服务配置中心
## client
微服务客户端
## user
用户系统，实现了oauth2协议
