---
layout: post
title:  "Thanks for those 100 stars!"
---

输出字符
### echo
````
chcp 65001 支持中文
echo "字符串"
````

### 接收参数
使用%1 %2 ...接收参数
````
调用端 test.bat test
接收端
echo %1 %2 %3

````

### 接收用户输入

````
set /p serial=
echo %serial%
````