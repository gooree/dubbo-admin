# dubbo-admin
dubbo服务管理系统

## 如何使用
1. 下载war包，修改/WEB-INF/目录下的dubbo.properties。
```properties
#zookeeper地址
dubbo.registry.address=zookeeper://10.27.115.125:2181
#root用户密码
dubbo.admin.root.password=root
#guest用户密码
dubbo.admin.guest.password=guest
```

2. 将war包发布到tomcat部署目录下即可。
