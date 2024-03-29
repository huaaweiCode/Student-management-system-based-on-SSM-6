# 基于SSM的学生管理系统



## 1、项目介绍：

基于SSM的学生管理系统拥有三种角色，分别为学生、教师和管理员。

- **学生**：个人信息查看、密码修改、成绩按照年份、学期教师查询

- **教师**：个人信息查看、密码修改、按照学号、姓名班级、查找学生、成绩查询、成绩统计、成绩发布与修改

- **管理员**：系统管理、院系增删改查、班级增删改查、教师增删改查、课程增删改查、学生增删改查、成绩增删改查

## 2、项目技术

**后端框架**：SSM（Spring、SpringMVC、Mybatis）

**前端框架**：layui、jsp

其它：mysql5-8、tomcat8-10、JDK1.8+

## 3、开发工具

Eclipse、idea和myEclipse都可以

## 4、功能介绍及视频演示

**4.1、登录页面**
![批注 2020-03-05 111628](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220515121233.jpg)

学生管理系统的中三种用户均可以通过此界面登录，系统将自动识别用户类型，经过密码正确性验证之后，将会跳转到不同的页面

**4.2、管理员界面**

![管理员-班级管理](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220515121439.jpg)

![管理员-成绩查询](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220515121444.jpg)

![管理员-添加学生](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220515121447.jpg)

![管理员-学生管理](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220515121459.jpg)

上图中的左侧菜单栏为管理员的功能列表，包括系统管理、院系增删改查、班级增删改查、教师增删改查、课程增删改查、学生增删改查、成绩增删改查等。上图也是管理员新增学生的页面，管理员点击右上角的“新增学生”按钮后，页面将会跳转出记录学生信息页面，学号为系统自动生成，填写完成后，点击“保存”按钮即可将数据存入至数据库中。

**4.3、教师界面**

![教师-成绩查询](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220515121513.jpg)

![教师-成绩统计](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220515121516.jpg)

上图左侧菜单栏为教师功能列表，包括系统管理、学生管理和成绩管理。教师可以对学生的成绩进行增改查。查找方式多种对样（如上图），同时教师还可以修改学生的的成绩。

**4.4、学生界面**

![学生-成绩查询 ](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220515121434.jpg)

上图为学生登录后的界面。学生可以根据多种方式查看自己的成绩，例如通过年份、学期和教师等条件。
### 获取方式&视频演示

下方扫一下，回复关键词：学生

![gitee](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202309291447341.png)
