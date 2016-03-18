---
root: true
name: Advanced Beego
sort: 6
---

# Advanced Beego

We have demonstrated the basic usage of Beego. Now we will talk about more advanced topics.

- [In process monitor](./monitor.md)

  Beego will serve pages on two ports by default. The first is port 8080 for the application to serve pages to users. The second is port 8088, to monitor the process status, execute tasks and so on.
	
- [Filters](../mvc/controller/filter.md)

  Filters are a very convenient feature for you to extend your logic. You can easily implement user authentication, log visiting, compatibility switching and so on.
	
- [Reload](./reload.md)

  Reload is always mentioned in web development that allows deploying applications without interrupting user requests.
	
>>> This feature is not well developed yet. It has only been tested on Mac and Linux. It has not been tested in a production environment yet. It's still being tested, so use it at your own risk. It is recommended that you use it upstream of nginx.
