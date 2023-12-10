# dubbo-spring-boot-demo
> 实践工程：https://github.com/apache/dubbo-samples  
> 实践工程讲解：https://cn.dubbo.apache.org/zh-cn/overview/quickstart/java/brief/

## hello world 关键点：
provider @DubboService   暴露服务  
consumer @DubboReference 引用服务

配置application.yaml和@EnableDubbo

---
1. 引入依赖
2. 注册服务
3. 引用服务
4. 调用服务
5. 监控服务
6. 负载均衡
7. 超时控制
8. 重试机制
9. 泛化调用
10. 泛化调用（泛化接口）
11. 泛化调用（泛化引用）
12. 泛化调用（泛化引用+泛化接口）

## 注意事项
1. 泛化调用需要在provider和consumer都配置@EnableDubboConfigBinding