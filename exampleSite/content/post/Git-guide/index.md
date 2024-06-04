+++
author = "G"
title = "Git语法指南"
date = "2024-06-04"
description = "Git常用命令集"
tags = [
    "Git"
]
categories = [
    "开发工具"
]
+++
# Git基本命令
## 设置用户名
```bash
git config --global user.name "guzhenan"

git config --global user.email "gzn.gmail.com"
```

## 初始化和查看日志
```bash
git init
git log
```
## 添加文件和提交文件
```bash
git add test.txt    // 表示文件放到暂存区
git commit -m "注释" test.txt   // -m 表注释
```
## 查看工作区和暂存区状态
```bash
git status
```
## 删除文件
```bash
rm test.txt
git add test.txt
git commit -m "删除test.txt" test.txt
```
# Git分支命令
## 查看、创建、切换分支
```bash
git branch branch01  // 创建分支
git branch -v  // 查看分支
git branch branch01 //  切换分支
```

# Github相关
## 为URL起别名以及查看别名
```bash
git remote add origin [url]
git remote -v
```
## 推送操作和克隆操作
```bash
git push [url] master  // master表示要推送的分支
git clone [url]
```
## 远程库修改的拉取
```bash
git pull [url] master
```
## 实例
```bash
git remote add cs_notes https://github.com/CyC2018/CS-Notes.git  // 起别名
git pull cs_notes master  // 拉项目
git add .  // 添加到暂存区
git commit -m "modify test"  // 提交给git管理
git push cs_notes master  // 提交到GitHub
```
