ICEworld
=========
A multithread implementation based on Tornado

######a fast restful dev framework based on tornado.

######Take advantage of a fashionable C10K framework Tornado(ioloop).

######ioloop throws requests to threadpool, threadpool notifies ioloop when it is done.

######Before deployment, `tornado` and `futures` are required.
```bash
    sudo easy_install tornado
    sudo easy_install futures
```
1.In "biz" folder, make a py file from demo which existed there

2.Use "Router.route" to decorate a method of your business class after import Router module

3.Go to the "bin" folder, then use command --"python serv.py" to start up


基于tornado改装的多线程业务处理模型框架，自带跨域请求，json/xml参数解析，缓存和路由优化。适合多人合作的service系统后台搭建！*
>疑问请联系:
<rowland.lan@163.com>

***no rights reserved, enjoy!!***
