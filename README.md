# 贵工程寝室快修小程序

## 前言

在这个快节奏的生活中，高效便捷的服务显得尤为重要。为此，我们团队开发了“贵工程寝室快修小程序”，旨在为在校师生提供一个方便快捷的报修服务平台。通过此小程序，用户可以轻松提交报修申请，实时跟踪维修进度，提高维修效率。

## 内容介绍

本项目是一款基于Spring Boot的微信小程序，主要功能包括：用户注册登录、报修申请、维修进度查询、个人信息管理等。通过微信小程序，用户可以随时随地提交报修申请，方便快捷。同时，后台管理员可以实时查看报修信息，合理分配维修任务，提高维修效率。

## 技术介绍

- 语言：Java
- 使用框架：Spring、Spring MVC、MyBatis、微信小程序
- 前端技术：JS、Vue、CSS3、Uniapp
- 开发工具：IDEA/Eclipse、Uniapp
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.js 12/14/16

## 核心代码

以下是一段关于报修申请提交的核心代码：

```java
// 报修申请接口
@RequestMapping(value = "/submitRepair", method = RequestMethod.POST)
public ResponseEntity<String> submitRepair(@RequestBody RepairRequest repairRequest) {
    // 逻辑处理
    repairService.submitRepair(repairRequest);
    return new ResponseEntity<>("报修成功", HttpStatus.OK);
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图
![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/340226/22/10613/161178/68c63604F0e556855/690b124125b9c018.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/349355/5/3103/28822/68c635dcF6b4ba6b0/c1991e7aea237fa4.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/337382/2/10541/22995/68c635dcF3aa5a940/2695917675322afd.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/350328/1/3153/71448/68c635dcF2170464c/92e30e3ed7826989.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/331931/26/13170/22414/68c635dcFc6362ac8/4c7904e8c9164662.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/346822/31/3221/32512/68c635dcF802a79bc/3f8efd570de944fb.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/324015/15/19782/31199/68c635ddFe989ede1/bc9cfc1ec75e4824.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/331549/22/13037/18909/68c635ddFc58f3893/d3155c8ca98ea1d1.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/338085/2/10351/21919/68c635ddFb6c8422b/9d9f212546f1f0d9.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/336196/13/10526/91743/68c635ddF20f0bc7d/4801e81e094469f5.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
