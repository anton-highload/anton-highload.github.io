---
title:  "Introduction To The Blog Theme"
date:   2020-10-25 21:49:17 +0300
categories: jekyll update
---
Despite the name, the theme of this blog not limitate only to Django optimization. I want to tell you about different types of speed up Django or Python applications, that include:
* Working with database and cache
* Core python optimization (imports, garbage collector)
* Microservice architecture optimization (working with Apache Kafka etc.)
* And other interesting things


Therу is much information about this on the web, but there is no compilation in one place. If you now a good source please, write a link to the comment section. I’d appreciate it.)


I want to start this blog by reviewing a good book: **High-Performance Django**

![highload](/assets/img/highload.png)

You can buy it here: [High Performance Django The Book](https://highperformancedjango.com)

Strongly recommend.


This is a really good book, and it covers all aspects of the Django application in depth from logging to deploy. But, unfortunately, this book was published in 2014, and many points outdated and irrelevant. About these moments, and I’d like to talk to you.


The key idea is: If you think that Django isn’t scalable or python is naturally slow, you should pass by)


So, in the first place we go thought base *Pain points* from this book:
* **Database**. 
	* Nothing has changed here, it still bottles neck of many apps, we can go through it with appropriate cache policy or we can switch to NoSQL (but complexity and cost of development will grow)
* **Templates**
	* This item is no longer relevant, for our days de facto we use Django only with Django Rest Framework in big projects. But it has bottlenecks too. Such as the chronic problem with n+1 issues or Django lazy objects nature. We talk about it in the future.
* **Python**
	* And last but not least - Python) as I said before it has two big (or narrow?) bottlenecks: a lot of imports and memory leaks.


So we have our RoadMap anв see you soon;)
