#StudentScoreManageSystem
---
   
##一个前端基于easyui框架，后端基于Struts2、Mybatis、Spring框架的学生成绩管理系统

	使用该项目的麻烦点下右上角的***star***，感激不尽。
##系统功能简述  

学生成绩管理系统中，系统的用户是学校的学生、教师和管理员。各类用户经登录认证后方可使用系统。学生使用本系统可以查询自己的信息和成绩。教师使用本系统查询个人信息、查询自己所授课程信息和自己所授课程考试成绩。教学管理员可以添加班级，学生的增删改查，教师的增删改查，课程的增删改查，授课的增删改查和查询教师已经批改成绩的成绩信息。(所有查询均支持多条件查询,支持导入学生教师信息/导出成绩信息)   

##使用前注意事项  

eclipse直接导入解压后的文件夹即可,tomcat则只需将sms1.war放进你的tomcat目录下的webapps文件夹下面，然后启动tomcat即可.导入程序后，先将db.sql导入到你的数据库，然后进入applicationContext.xml文件将bean的id为dataSource下的用户名，密码，数据库名改为你自己对应的.导入文件要符合相对应的student.xls/teacher.xls格式.   

##程序截图如下:  

1.登录界面:
![](https://i.imgur.com/v7aBMNG.png)
2.管理员界面:  
1)主页
![](https://i.imgur.com/8D6U2UY.png)
2)学生管理
![](https://i.imgur.com/Z21nBzz.png)
3)教师管理
![](https://i.imgur.com/tcWjWjK.png)
4)课程管理
![](https://i.imgur.com/wLpnbHj.png)
5)授课管理
![](https://i.imgur.com/0NzJaKp.png)
6)成绩管理
![](https://i.imgur.com/2NePabE.png)
3.学生界面:  
1)主页
![](https://i.imgur.com/tAsk7R6.png)
2)学生信息
![](https://i.imgur.com/wEeWSNG.png)
3)学生成绩
![](https://i.imgur.com/1WBy2BL.png)
4.教师界面:  
1)主页
![](https://i.imgur.com/vd9Eat9.png)
2)教师信息
![](https://i.imgur.com/jIBgf0H.png)
3)教师课程
![](https://i.imgur.com/tryxlRh.png)
4)教师成绩管理
![](https://i.imgur.com/RdL8000.png)
