# README123
0
![index.png](/assets/123.jpg)
![index.png](http://yijiebuyi.com/file/7e210b09e314b840ef3cd9c1773bb809)
![index.png](http://yijiebuyi.com/file/0405cdae51f50fc6db624c04c5824793)
![index.png](http://yijiebuyi.com/file/95742b3200d5cce03c9a99ad76698269)
![index.png](img/微信图片_20181029114017.jpg)
![index.png](img/微信图片_201810291140171.jpg)
![index.png](img/持续集成_1.png)

这个路由我们从数据库读取了一条记录最后返回给客户端,中间没有出现任何异常.

![index.png](img/0405cdae51f50fc6db624c04c5824793.png) (title=undefined data-bd-imgshare-binded=undefined)

这是我们模拟的一个异常已经被捕捉到,这是服务器端返回给客户端的一个500提示信息,这时我们再看一眼控制台,node 进程并没有挂掉.

![index.png](img/95742b3200d5cce03c9a99ad76698269.png) (title=undefined data-bd-imgshare-binded=undefined)

每次 domian 捕获到错误后,我都在控制台输出了一行提示信息 "捕获到错误" 当前进程并没有因为异常而挂掉,这就是我们要的效果.
![index.png](img/logo-o.png?v=2)
