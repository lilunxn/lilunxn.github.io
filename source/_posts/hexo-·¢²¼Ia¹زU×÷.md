---
title: hexo多端发布相关操作
date: 2018-11-04 10:25:14
tags: 
categories： 其他操作
---

在不同的端口进行相关操作时，需要按照下述方法进行：

```
git pull origin hexo //先pull完成本地与远端的融合
hexo new post "new post name" //新建一个文件
git add source //将新建文件进行添加
git commit -m "将添加说明写在这里"
git push origin hexo //将本地修改push到远程仓库
hexo d -g //生成并发表
```
