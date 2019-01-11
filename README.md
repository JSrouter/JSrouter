# JSrouter JS前端路由

JS原生实现前端路由之web无刷单页面应用

前端路由有2种实现方式，一种是html5推出的historyapi，另一种hash路由，就是常见的 # 号，这种方式兼容性更好。

## 需求分析

1、无刷新切换页面，

2、监听popstate事件

3、单页化web应用

4、异步加载数据

5、路由兼容优化

<p>完整的demo
  
<a href="https://jsrouter.github.io/">JSroute</a>
</p>
<!---用户前进和后退事件
：一般单页面应用为了性能优化，都会把各个页面的文件拆分开，按需加载，所以路由里面要加入异步加载数据的功能。异步加载我们就采用最简单的原生方法，创建script标签，动态引入js。
简单的单页面在github上有完整的demo
spa-routers
--->
