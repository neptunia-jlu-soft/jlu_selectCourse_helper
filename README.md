# 吉林大学选课助手/jlu_selectCourse_helper

## 简介

轻量级，占用资源极低，非常适合挂机刷课。并且可以手动设置使用的线程数量和等待无响应的时间，支持多个课程多线程同时操作。

## 配置

配置源码中的 user_id 为自己的学号，pass_plain 为自己的密码（初始为身份证后 6 位），course_id 为自己想选的课的 id(支持多课程同时选课)。

## 启动小助手

```bash
python jlu_select_courses.py
```

## 注意

course_id 不是 uims 系统中教学班提供的编号，是在页面源代码中选课按钮旁的编号。
请在有线网络环境下使用该脚本。

如下所示：
![sample](https://raw.githubusercontent.com/42binwang/jlu_selectCourses_tools/master/sample.png)
