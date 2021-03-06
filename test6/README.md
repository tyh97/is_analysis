# 实验6:基于GitHub的实验管理平台的分析与设计

|学号|班级|姓名|
|----|------|----|
|201610414112|软件（本）16-1|唐银浩|

## 1.概述
* 基于GitHub的实验管理平台的作用是在线管理实验成绩的Web应用系统。学生和老师的实验内容均存放在GitHUB 页面上。
* 学生的功能主要有：一是设置自己的GitHub用户名；二是查询自己的实验成绩；三是可以选择需要学习的课程；学生的GitHub用户名是公开的，但成绩不公开。
* 老师的功能主要有：一是选择自己需要教学的科目；二是批改每个学生的成绩；三是查看每个学生的成绩。
* 老师和学生都能通过本系统的链接方便地跳转到学生的每个GitHUB实验目录，以便批改实验或者查看实验情况。
* 实验成绩按数字分数计算，老师先制定每个实验的评分细则，然后根据每项评分细则进行评分，最后系统
根据评分细则来进行总分的评定，每项实验的满分为100分，最低为0分。
* 老师首先需要添加自己要教学的课程，可以同时添加多门课程；然后学生根据自己需要选择要上的课程
，一个学生可以同时选择多门课程。

## 2.系统总体结构
![img](./picture/系统总体结构.png)

<br>

## 3.用例设计图 [源码](./puml/SystemCase.puml)
![img](./picture/SystemCase.png)

<br>

## 4.类设计图 [源码](./puml/SystemClass.puml)
![img](./picture/SystemClass.png)

<br>

## 5.数据库设计

* [参见数据库设计](./Markdown/DataBase.md)

## 6.用例及界面详细设计
* ["登录"用例](./Markdown/LoginInfo.md)，[界面](https://tyh97.github.io/is_analysis_terminal_pages/)
* ["登出"用例](./Markdown/LoginOut.md)，[界面](https://tyh97.github.io/is_analysis_terminal_pages/top.html)
* ["查看用户信息"用例](./Markdown/UserInfo.md)，[界面](https://tyh97.github.io/is_analysis_terminal_pages/userinfo.html)
* ["修改用户信息"用例](./Markdown/ModifyUserInfo.md)，[界面](https://tyh97.github.io/is_analysis_terminal_pages/modifyuserinfo.html)
* ["修改密码"用例](./Markdown/ModifyPassword.md)，[界面](https://tyh97.github.io/is_analysis_terminal_pages/modifypassword.html)
* ["用户列表"用例](./Markdown/AllUserList.md)，[界面](https://tyh97.github.io/is_analysis_terminal_pages/studenlist.html)
* ["维护用户数据"用例](./Markdown/MaintainUserInfo.md)，[界面](https://tyh97.github.io/is_analysis_terminal_pages/addcourse.html)
* ["学生列表"用例](./Markdown/AllStudentList.md)，[界面](https://tyh97.github.io/is_analysis_terminal_pages/studenlist.html)
* ["添加课程"用例](./Markdown/AddCourse.md)，[界面](https://tyh97.github.io/is_analysis_terminal_pages/addcourse_1.html)
* ["设定实验"用例](./Markdown/AddTests.md)，[界面](https://tyh97.github.io/is_analysis_terminal_pages/addtests.html)
* ["选择课程"用例](./Markdown/SelectCourse.md)，[界面](https://tyh97.github.io/is_analysis_terminal_pages/selectcourse.html)
* ["评定成绩"用例](./Markdown/JudgeScore.md)，[界面](https://tyh97.github.io/is_analysis_terminal_pages/judgescore.html)
* ["查看成绩"用例](./Markdown/CheckScore.md)，[界面](https://tyh97.github.io/is_analysis_terminal_pages/chackscore.html)








