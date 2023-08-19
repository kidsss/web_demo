# web_demo
基于django提供一个本地的web系统，将存储于本地的html可视化与展示


#### 环境介绍
使用minconda 协助管理环境。
创建python3.10环境，`conda create -n web_demo python=3.10`
安装依赖，参考requirements.txt文件


#### 创建demo
使用django自带的django-admin服务，创建demo
执行命令如下：
```
django-admin startproject demo
cd demo; python manage.py runserver
```
自动在 127.0.0.1:8000创建网页服务，可通过浏览器访问
默认使用sqlite数据库，不需要额外修改


