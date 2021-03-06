# 接口: getStuCourse | [返回](../Markdown/SelectCourse.md)
用例：学生选课

* 功能：查询学生可选的课程
* 权限：已登录的学生
* API请求地址：接口基本地址/v1/api/getStuCourse
* 请求方式：GET
* 请求实例:
```json
{
  "user_id": "001",
  "type": "student"
}
```
* 请求参数说明：

|  参数名称   |          说明          |
| :---------: | :--------------------: |
|   user_id   |         用户id         |
|    type     |    当前登录用户类型    |

* 返回实例：
```json
{
  "status": "true",
  "user_id": "001",
  "info":"",
  "data": [
      {
         "course_id": "10000001",
         "course_name": "信息系统",
         "course_detail": "信息系统是一门好课",
         "teacher_id": "001"
      },
      {
        "course_id": "10000002",
        "course_name": "软件工程",
        "course_detail": "软件工程是一门好课",
        "teacher_id": "001"
      }
    ]
}
```
* 返回参数说明:

| 参数名称 |             说明             |
| :------: | :--------------------------: |
|  status  |           请求状态           |
| user_id  |         登录用户的id         |
|   data   |    所有课程的信息,类型为一个数组     |
|   info   | 额外的信息，可以存放错误信息 |
