# TodayStudy_Action

[![Attendance](https://github.com/Boos4721/TodayStudy_Action/actions/workflows/auto_attendance.yml/badge.svg)](https://github.com/Boos4721/TodayStudy_Action/actions/workflows/auto_attendance.yml)

## 如何使用

1. 点击右上绿色的**Use this template**
2. 如图部署到你的仓库后开始第二步
![](https://github.com/Boos4721/TodayStudy_Action/raw/master/docs/1.jpg)

## 配置&部署

1. 编辑里面的config.yml为你自己的配置
2. 并替换你的图片(**如果你不需要**)
3. 修改`.github/workflows/auto_attendance.yml`里的第七行划重点 这里是**UTC**时间
4. 这样到时间就可以自动进行签到了
5. btw 这是cron表达式 不支持秒 [点我查看Github说明](https://docs.github.com/cn/actions/learn-github-actions/workflow-syntax-for-github-actions#example)

## 测试

1. 点击右上的**Star**
2. 进入**Actions**查看运行状态

## 个人建议

### 测试完成后改成私人项目最佳
