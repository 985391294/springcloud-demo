1.先启动eureka服务，作为注册中心，会让其他服务都注册到这里，集中管理服务
2.再启动config服务，作为分布式注册中心，其他服务会从config里面拉取到需要的配置信息
3.然后启动相关的业务服务