# 东方财富股吧爬虫

## 项目介绍

该项目使用selenium模拟用户操作抓取股吧数据，借助stealth.min.js隐藏浏览器的特征，将抓取到的数据储存到MongoDB中。

## 主要功能

1. 爬取指定股票股吧中的发帖信息，包括帖子标题，浏览量，评论数，帖子链接，发帖时间 (YYYY-MM-DD, HH: MM)

2. 爬取指定时间范围中股吧帖子下的评论信息，包括评论内容，是一级或二级评论，点赞数，发帖时间 (YYYY-MM-DD, HH: MM)

## 文件介绍

- `main.py` : 主程序，直接在里面调用函数就可。
- `crawler.py` : 
- `parser.py` : 
- `mongodb,py` : 
- `stealth.min.js` :

## 爬取逻辑

## 使用步骤

### 1.下载代码

### 2.MongoDB安装，创建名为xxx的数据库

### 3.Webdriver安装

### 4.main中修改参数
