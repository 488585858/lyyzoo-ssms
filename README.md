学校课程设计作业，完成一个简单的学生信息管理系统，考虑到系统实用性，把它做成了一个简单的能够使用的学生成绩管理系统，包含了学生信息管理，就当做练手吧。

发一个博客，做展示用！！

第一次做的一个比较完整的系统，难免会有一些bug(^_^)

下载链接：学生成绩管理系统

 

一、  开发背景

软件名称：学生成绩管理系统(SSMS)

使用对象：小学、初中、高中

二、  需求分析

1. 系统分析

该学生信息管理系统涉及到学生、教师、系统管理员、班级、学生成绩、课程。设置一个系统管理员对系统进行管理。所有用户需输入账号、密码登录进入系统；管理员进入系统后可对学生、老师、班级、课程进行增删改查操作；学生进入系统，查看成绩、查看和修改自己的信息；老师进入系统后，对自己这门课程的学生设置课程成绩、查看和修改自己的信息，查看学生的信息和成绩、以及统计分析学生的成绩；

管理员为班级设置年级，为年级设置课程，为班级的每门课程设置老师，为学生设置班级。一个年级有多门课程(语文、数学、外语等等)，班级的每门课程只能有一名老师，一个老师可以有多门课程；老师选择自己这门课程为该课程的学生登记成绩。老师可以查看其他老师的信息(可以当成是老师的通讯录)，查看本课程学生的信息和成绩；学生可以查看班级其他同学的信息(可以看成是班级的同学录)。

考试分为两种，一种是年级统考，一种是平时考试。年级统考需要管理员事先添加一次年级统考，考试成绩出来后，老师进入系统选择该次考试为学生登记成绩。平时考试则是班级平时的考试，老师添加考试信息，登记成绩。成绩统计分析则是针对年级统考进行分析，主要涉及各学科分数名次，总分名次。

三、开发环境

系统环境：Windows

开发工具：Eclipse

Java版本：JDK 1.7

服务器：tomcat 7.0

数据库：MySQL 5.1

系统采用技术：Servlet+Jsp+Jdbc+H-ui+EasyUI+jQuery+Ajax+面向接口编程

四、其它的看截图

登录界面：
![image](https://github.com/user-attachments/assets/a3234a81-cfc6-4360-9fa1-9fed3fca9651)



 

管理员界面：
![image](https://github.com/user-attachments/assets/e242efa4-5041-4384-ba5c-255525082adc)



 

考试列表：
![image](https://github.com/user-attachments/assets/19f28c5d-8d41-4c33-bcc1-0219306beca1)



 

成绩统计：
![image](https://github.com/user-attachments/assets/10b534fe-daef-4c10-a8fa-dca892b025a1)



 

教师列表：
![image](https://github.com/user-attachments/assets/3b20abc6-a77a-4889-adc6-5c778ff43374)



 

学生列表：
![image](https://github.com/user-attachments/assets/0b0c1355-b571-4106-94c1-25f63d937358)



 

系统设置：
![image](https://github.com/user-attachments/assets/ef62da28-7a45-4553-b5c9-e615126d42e4)



 

教师界面：
![image](https://github.com/user-attachments/assets/93b5ecc8-08e0-4219-9fc6-1a5eda9d5b58)



 

成绩登记：
![image](https://github.com/user-attachments/assets/fe3b9d55-eacd-4623-badc-f7686aa2ea82)



 

教师通讯录：
![image](https://github.com/user-attachments/assets/cab1764b-73be-4b1f-b01b-ab62f6d91a1c)



 

个人信息：
![image](https://github.com/user-attachments/assets/6388c1be-c371-4276-9bd0-07b27fb16e6b)



 

学生界面：
![image](https://github.com/user-attachments/assets/89d3cdf4-a18a-4faf-b077-e22abd648e59)



 

学生成绩查询：
![image](https://github.com/user-attachments/assets/d27649c3-6bf1-45be-82bf-e9ae65928e45)


