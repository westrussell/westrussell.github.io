---
title: hexo命令
date: 2022-09-22 16:37:00
tags: 学习
categories: 学习
---
# Hexo常用命令
## 写作命令
1. 新建分页：
``` bash
hexo new page 名称
```
2. 新建文章：
``` bash
hexo new 名称或hexo n 名称
```
3. 新建草稿：
``` bash
hexo new draft 名称或hexo n draft 名称
```
4. 草稿生成文章：
```bash
hexo publish 名称或hexo p 名称
```
5. 草稿生成分页：
```bash
hexo publish page 名称或hexo p page 名称
```
## 操作命令
1. 清除已生成文件：
```bash
hexo clean
```
2. 运行本地服务器（预览）：
```bash
hexo s
```
3. 运行本地服务器（预览草稿）：
```bash
hexo s --drafts
```
4. 生成静态文件：
```bash
hexo g
```
5. 部署到服务器：
```bash
hexo d
```
6. 生成并部署文件：
```bash
hexo g -d或hexo d -g
```


