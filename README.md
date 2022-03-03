# 

# 90.EnglishLearningManagementSystem

<p>群: 123300273(大佬群 2TB学习资料,讲解)(入群获取sql文件)</p>
<p>QQ: 1095737364(加好友获取sql文件)</p>

<p><h1 align="center">90.学习英语管理系统</h1></p>

<p align="center">
	<img src="https://img.shields.io/badge/jdk-1.8-orange.svg"/>
    <img src="https://img.shields.io/badge/spring-5.x-lightgrey.svg"/>
    <img src="https://img.shields.io/badge/springmvc-3.x-blue.svg"/>
    <img src="https://img.shields.io/badge/mybatis-3.x-blue.svg"/>
    <img src="https://img.shields.io/badge/springboot-2.x-blue.svg"/>
</p>

## 简介

> 本代码来源于网络, 请入群(123300273)后联系群主索要sql文件!
> 
> 本英语学习项目是为了满足学生学习英语的需求而开发，在本系统中学生可以通过背单词，每日一句，听听力，看阅读等方式加深对英语的学习与了解。

**本项目用到的技术和框架**<br>
1.项目构建：Maven<br>
2.web框架：Springboot<br>
3.数据库ORM：Mybatis<br>
4.数据库：MySQL<br>
5.前端框架：BootStrap<br>
6.模板引擎：Thymeleaf<br>
7.文章展示：Editor.md<br>
## 环境

- <b>IntelliJ IDEA 2009.3</b>

- <b>Mysql 5.7.26</b>

- <b>Maven</b>

- <b>JDK 1.8</b>

## 功能介绍
本学习系统分为注册登录模块，公告展示模块，背单词模块，听力练习模块，阅读书籍模块，每日一句模块，个人中心模块，以及后台管理模块。
#### 登录注册模块
- 登录功能
    - 验证信息：输入邮箱与密码，如果正确则进入网站首页，如果错误则提示错误信息
    - 登录拦截：在进入网站页面之前，系统会检测用户是否带有Session，如果没有则没有权限进入其他页面
- 注册功能
    - 新用户可以输入邮箱与密码进行注册，提交信息后返回登录页面提示去邮箱激活
    - 系统通过QQ邮箱服务器发送给新用户，新用户点击收到激活网站进行注册
#### 公告展示模块
- 网站首页会展示管理员发布的公告
- 用户可以查看发布的历史公告

#### 每日一句模块
- 网站首页会随机展示句子与翻译
- 图片展示使用了必应的每日一图api

#### 背单词模块
- 选择单词
    - 用户可以根据单词的等级进行学习
- 学习单词
    - 会从未学习过的单词之中随机抽取相应等级的单词
    - 页面会展示该单词是否被收藏，以及当前的学习进度
    - 用户可以点击收藏，认识，不认识，下一个等按钮进行学习

#### 听力练习模块
- 用户可以选择哪些年份的真题与等级
- 用户可以播放听力，以及查看真题

#### 阅读书籍模块
- 用户可以选择喜欢的书籍进行阅读
#### 个人中心模块
- 用户可以自行修改自己的名字，邮箱以及密码

#### 后台管理模块
- 管理员可以进入后台，对系统的用户，单词，书籍，公告进行管理

## 缩略图

![](https://img2022.cnblogs.com/blog/588112/202203/588112-20220304070855637-1034656785.png)
![](https://img2022.cnblogs.com/blog/588112/202203/588112-20220304070903502-242381062.png)
![](https://img2022.cnblogs.com/blog/588112/202203/588112-20220304070909449-276257840.png)
![](https://img2022.cnblogs.com/blog/588112/202203/588112-20220304070916532-537302335.png)
![](https://img2022.cnblogs.com/blog/588112/202203/588112-20220304070922561-894433324.png)
![](https://img2022.cnblogs.com/blog/588112/202203/588112-20220304070928514-2086452781.png)
![](https://img2022.cnblogs.com/blog/588112/202203/588112-20220304070934417-1684218567.png)
![](https://img2022.cnblogs.com/blog/588112/202203/588112-20220304070939710-2060231454.png)


## License

##### [个人站点: 全栈九九六(Java全栈知识资料下载)](https://www.blog996.com/)
##### [个人博客: 博客园精品博客](https://www.cnblogs.com/yysbolg/)
##### [更多论文: 精品论文查看](https://www.cnblogs.com/yysbolg/category/1886262.html)
##### [更多论文: 全目录查看](https://www.blog996.com/md/2021-09-22-1632317852192.html)



