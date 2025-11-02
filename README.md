# 前言

欢迎来到基于SSM的运动会成绩管理系统！此项目旨在帮助学校或组织者高效地管理运动会成绩信息，提供便捷的成绩录入、查询、统计等功能。

# 内容介绍

本项目基于Java语言和Spring、Springmvc、Mybatis框架进行开发，前端采用JS、Vue和CSS3技术，数据库使用MySQL 5.7/8.0。以下是本项目的主要功能模块：

1. 成绩录入：支持手动添加运动员成绩信息，自动计算总成绩。
2. 成绩查询：可根据运动员姓名、项目名称等条件查询成绩。
3. 成绩统计：按照项目、年级、班级等维度进行成绩统计。
4. 用户管理：实现对系统用户的增删改查操作，保障系统安全。

# 技术介绍

- 语言：Java
- 使用框架：Spring、Springmvc、Mybatis
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

# 核心代码

以下是项目中一个简单的查询成绩的代码片段：

```java
// 注解方式查询成绩
@RequestMapping("/queryScore")
public List<Score> queryScore(@RequestParam("athleteName") String athleteName,
                              @RequestParam("eventName") String eventName) {
    Map<String, Object> paramMap = new HashMap<>();
    paramMap.put("athleteName", athleteName);
    paramMap.put("eventName", eventName);
    return scoreService.queryScore(paramMap);
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img12.360buyimg.com/ddimg/jfs/t1/291780/25/27014/94101/68ad51beFea3e5e0f/e3cd1cbb317a31e4.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/327176/19/11182/18478/68ad5197Fe2f09cd2/a8cb2a6b8c79b488.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/291335/27/26906/16959/68ad5197F31676e74/ae0dd9826ed9eeea.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/332177/22/4445/67461/68ad5198Ffcf3a589/520c5adb81ce79dc.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/325835/9/11122/27171/68ad5198F198cab5f/fce73e7e4ba05fe7.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/328403/28/11227/36807/68ad5199F48285b39/bee7c755ab811830.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/324060/30/11096/32172/68ad519aF3e4bab72/90eb21408a5a3dea.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/336736/15/1915/23912/68ad519aF7ca8fd4a/605bb09d9b7c0765.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/292246/28/26181/51974/68ad519bF7173e2eb/fd0e087b38b4060d.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/326444/16/11190/20700/68ad519bF178afd2b/2f32b837e18b7a5a.jpg)

