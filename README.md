# 相关代码已经修改调试成功----2017-4-7 #

## 一、说明 ##

1.**目标网址**：[智联招聘](http://www.zhaopin.com/)

2.**实现**：对智联招聘上搜索 [数据分析](http://sou.zhaopin.com/jobs/searchresult.ashx?jl=%E5%8C%97%E4%BA%AC&kw=%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90&sm=0&p=1) 的职位相关信息的爬取，如职位名称、薪资、工作经验等等。具体看如下图：

![](http://i.imgur.com/0BYnbZd.png)

3.**数据**：我都存放在百度网盘里面 链接：[http://pan.baidu.com/s/1i5okiZb](http://pan.baidu.com/s/1i5okiZb) 密码：xnig
	![](http://i.imgur.com/JcN9g3f.png)![](http://i.imgur.com/Lapfys1.png)

	爬取的是热门城市的**数据分析**职位信息 ['北京','上海', '广州', '深圳', '天津', '武汉', '西安', '成都', '大连', '长春', '沈阳', '南京', '济南', '青岛','杭州', '苏州', '无锡', '宁波', '重庆', '郑州', '长沙', '福州', '厦门', '哈尔滨', '石家庄', '合肥', '惠州'] **一共50111条记录**。
## 二、运行 ##
1. 先设置好place_name.py文件中 **place_name** 和 **job_name**，你要爬取的城市名称和职位名称。
2. zhilian.py中配置好数据库信息的函数。
3. 最后运行zhilian.py文件即可。 

## 三、问题----欢迎留言提出问题 ##

声明：本项目爬取的数据主要是给同事做数据分析

1. 其实对智联的爬取一直觉得爬取的速度很慢，用睡眠1-3秒来避免IP被禁，不知道怎么改成多线程或者是多进程？（待解决）
2. ........
 
**欢迎有兴趣的小伙伴帮我优化，解决以上问题，之后我将合并你的代码，作为贡献者,共同成长。**


----------
如果本项目对你有用请给我一颗star，万分感谢。 

## 补充：网友提出建议 ##
    （已添加进去）在你的爬虫zhilian的基础上，增加了两个点：
    	1、支持多个关键词爬取。
    	2、将关键词保存到数据库中 

