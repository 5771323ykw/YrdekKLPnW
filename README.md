# 前言

随着健康意识的普及和企业对职工健康的重视，我们开发了一套基于SSM（Spring、SpringMVC、MyBatis）框架的职工健康申报系统。本系统旨在方便企业对职工的健康状况进行实时监控和管理，提高工作效率，保障职工健康。

# 内容介绍

本系统主要包括以下功能模块：用户登录、健康信息申报、健康信息查询、健康数据统计等。系统采用Java语言开发，使用Spring、SpringMVC、MyBatis框架，前端技术包括JS、Vue和CSS3。以下是各模块的简要介绍：

1. 用户登录：企业职工通过账号密码登录系统，进行健康信息申报和管理。
2. 健康信息申报：职工可以在线填写健康信息，包括体温、身体状况等。
3. 健康信息查询：管理员可以查询全体或指定职工的健康信息。
4. 健康数据统计：系统可以自动统计健康信息，生成数据报表，方便企业了解职工健康状况。

# 技术介绍

- 语言：Java
- 使用框架：Spring、SpringMVC、MyBatis
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

# 核心代码

以下是项目中的一个核心代码片段，展示了如何使用MyBatis实现健康信息查询功能：

```java
// HealthMapper.xml
<select id="queryHealthInfo" resultType="com.example.entity.HealthInfo">
    SELECT * FROM health_info WHERE user_id = #{userId}
</select>

// HealthMapper.java
public interface HealthMapper {
    List<HealthInfo> queryHealthInfo(Integer userId);
}

// HealthService.java
public List<HealthInfo> queryHealthInfo(Integer userId) {
    return healthMapper.queryHealthInfo(userId);
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

![封面图片](https://img12.360buyimg.com/ddimg/jfs/t1/295390/13/25987/175042/68b17a15F67a2d579/83f167f492230dbc.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/328721/26/12611/25788/68b179eeFacfbc8ad/f99ed2f67b1bcb6f.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/326428/27/12861/134644/68b179eeF1e53f600/04ec9725a11411a3.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/339121/12/3521/46654/68b179eeF48470c3d/b2290424fde741ef.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/338413/30/3507/20742/68b179efFcdadd656/32fd073a83476ccf.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/323469/20/12809/14701/68b179efF373af89b/1851a5b6150553a7.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/332398/4/6028/121369/68b179f0F36c1d753/049bb81e533d993b.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/324333/37/12822/52246/68b179f0F1dd7331a/c125f705ff28ea02.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/340253/11/3509/21105/68b179f0Fdba91aaa/d559fa9d50c426ad.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/326667/26/12929/19361/68b179f0F6b3b99a7/741e5a6080b0268a.jpg)
