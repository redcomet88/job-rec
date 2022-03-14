# 推荐算法+可视化+图像识别  Vue+Flask求职推荐大数据可视化平台招聘python爬虫 (12W条数据)mysql 一体化系统源码+前后端分离
B站地址： [https://www.bilibili.com/video/BV19S4y1S7pX?share_source=copy_web](https://www.bilibili.com/video/BV19S4y1S7pX?share_source=copy_web)

## 1 系统功能

- 爬取智联招聘10多个城市的12万条就业数据后，进行转化和清洗，存储到mysql数据库
- 利用Flask开发接口，对接Vue前端，实现对求职招聘数据的可视化分析（Echarts 多种图形和词云、薪酬分析）
- 百度AI身份证识别  OCR识别
- 注册与登录 

## 2 系统亮点 ⭐

- 实现的分析图：数据大屏、职位分布中国地图、薪酬散点图、词云、多种折线图、饼图、环图等 （Vue集成 Apache Echarts）； 实现jieba分词+词云。
- 推荐算法： 两种协同过滤推荐算法使用。 【User Based & Item Based】
- 实名认证功能：通过使用百度AI-ORC识别身份证实现 【python实现】
- 前端界面为专业美工设计，响应式，自动适配移动端，前后端分离一体化系统（爬虫→MySQL→Flask→Vue）；
- 卡片式登录页面 + 大数据Style动画； 

## 3 架构功能图

- 架构图

![](https://secure2.wostatic.cn/static/u66nFJtfeCtGnZ5ukxvCRY/image.png)

- 功能模块图

![](https://secure2.wostatic.cn/static/xovyArxf7LgNT79zH14i6C/image.png)

- 词云的逻辑

![](https://secure2.wostatic.cn/static/iL1cJP1s9b63nvk49tWtRc/image.png)

## 4 开发环境和关键技术

- 服务端技术：Flask 、百度AI识别、SQLAlchemy、MarshMallow、Blueprint  等
- 前端技术：Vue  、Echarts 、Axios、Vuex等
- 爬虫技术： Scrapy 等
- 数据库：MySQL 
- 开发语言： Python 3.8  Vue 2.x
- 集成开发环境： PyCharm-2021 WebStorm-2021  Windows-10  Node-12
