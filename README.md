---
### 👉作者QQ ：1556708905 微信：zheng0123Long (支持修改、部署调试、定制毕设)

### 👉接网站建设、小程序、H5、APP、各种系统等

### 👉选题+开题报告+任务书+程序定制+安装调试+ppt 都可以做
---

**博客地址：
[https://blog.csdn.net/2303_76227485/article/details/134594288](https://blog.csdn.net/2303_76227485/article/details/134594288)**

**视频演示：
[https://www.bilibili.com/video/BV1WC4y1P7Y6/](https://www.bilibili.com/video/BV1WC4y1P7Y6/)**

**毕业设计所有选题地址：
[https://github.com/ynwynw/allProject](https://github.com/ynwynw/allProject)**

## 基于Java+Springboot+Vue的宠物领养社区小程序(源码+数据库)112

## 一、系统介绍
本系统前后端分离带小程序

小程序（用户端），后台管理系统（管理员）

- 小程序：
登录、注册、宠物领养、发布寻宠、发布领养、宠物社区、宠物评论、发布动态、领养审批、我的收藏、我的关注、举报。

- 管理后台：
用户管理、角色管理、菜单管理、宠物领养管理、答题管理、寻宠管理、动态管理、文章管理、积分管理，宠物科普管理、聊天管理、评论管理。

## 二、所用技术
后端技术栈：
- Springboot
- SpringMvc
- mybatisPlus
- mysql
- redis
- jwt
- SpringSecurity

前端技术栈：
- Vue
- elementui
- vue-router
- axios
- uniapp
- 微信小程序

## 三、环境介绍
基础环境 :IDEA/eclipse, JDK 1.8, Mysql5.7及以上, Node.js(14.21), Maven3.6, Vscode, hbuilder, 微信开发者工具, redis5.0

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图
### 1、小程序app页面
![contents](./picture/picture1.png)
![contents](./picture/picture2.png)
![contents](./picture/picture3.png)
![contents](./picture/picture4.png)
![contents](./picture/picture5.png)
![contents](./picture/picture6.png)
![contents](./picture/picture7.png)
![contents](./picture/picture8.png)
![contents](./picture/picture9.png)
![contents](./picture/picture10.png)
![contents](./picture/picture11.png)
![contents](./picture/picture12.png)
![contents](./picture/picture13.png)
![contents](./picture/picture14.png)

### 2、管理员页面
![contents](./picture/picture15.png)
![contents](./picture/picture16.png)
![contents](./picture/picture17.png)
![contents](./picture/picture18.png)
![contents](./picture/picture19.png)
![contents](./picture/picture20.png)
![contents](./picture/picture21.png)
![contents](./picture/picture22.png)
![contents](./picture/picture23.png)
![contents](./picture/picture24.png)
![contents](./picture/picture25.png)
![contents](./picture/picture26.png)
![contents](./picture/picture27.png)
![contents](./picture/picture28.png)
![contents](./picture/picture29.png)
![contents](./picture/picture30.png)
![contents](./picture/picture31.png)
![contents](./picture/picture32.png)
![contents](./picture/picture33.png)
![contents](./picture/picture34.png)
![contents](./picture/picture35.png)

## 五、浏览地址

- 后台管理访问路径：http://localhost:99
  admin/123456

## 六、安装教程

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并执行项目的sql
 
2. 使用IDEA/Eclipse导入pet-life-admin项目，导入时，若为maven项目请选择maven; 等待依赖下载完成

3. 修改ruoyi-admin目录的resources目录下面application.yml里面的redis配置, 文件路径配置,application-druid.yml里面的数据库配置

4. ruoyi-admin/src/main/java/com/ruoyi/RuoYiApplication.java启动管理后端

5. vscode或idea打开pet-admins-vue项目

6. 在编译器中打开terminal，执行npm install 依赖下载完成后执行 npm run dev,执行成功后会显示后台管理访问地址

7. 使用IDEA/Eclipse导入pet-life-main项目，导入时，若为maven项目请选择maven; 等待依赖下载完成

8. 修改resources目录下面application-dev.yml里面的数据库配置,redis配置, 文件路径配置和微信小程序配置

9. com/lian/pet/PetApplication.java启动小程序后端

10. hbuilder打开pet-wx-uniapp项目, 修改manifest.json里面的微信小程序配置AppId(从注册的微信小程序账号里面复制)

11. hbuilder点击运行-运行到小程序模拟器-微信开发者工具，然后会打开微信开发者工具，小程序页面就展示出来了(如果没有微信小程序开发工具也可以运行到浏览器打开)



