# 黑马点评项目总结

## 项目介绍 

黑马点评项目是一个前后端分离项目，类似于大众点评，实现了发布查看商家，达人探店，点赞，关注等功能，业务可以帮助商家引流，增加曝光度，也可以为用户提供查看提供附近消费场所，主要。用来配合学习Redis的知识。

1. 项目使用的技术栈

​      SpringBoot+MySql+Lombok+MyBatis-Plus+Hutool+Redis

2. 项目架构

​      采用单体架构   后端部署在Tomcat上，前端部分部署在Nginx 。

## 一、短信登录*

### 1. Session实现

登录验证功能：三个点，一个是拦截器 HandlerInterceptor 一个是ThreadLocal线程，隐藏用户敏感信息

- 拦截器 HandlerInterceptor
  HandlerInterceptor WebMvcConfigurer
- ThreadLocal线程
- 隐藏用户敏感信息

存在问题：Session共享问题，多台Tomcat并不共享Session

### 3. Redis缓存代替Session



## 二、商户查询缓存*



## 三、优惠券秒杀*



## 四、分布式锁*



## 五、分布式锁Redission*



## 六、秒杀优化*



## 七、消息队列*



## 八、达人探店



## 九、好友关注



## 十、附近商户



## 十一、用户签到



## 十二、UV统计

