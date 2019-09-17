vue-cli:
    安装：npm install -g @vue/cli
    创建项目：vue create myproject
    进入项目：cd myproject
    启动项目：npm run serve

路由：
    一个URL对应一个页面，根据标题的路由，可以渲染出来不同的页面
    使用vue-router模块 npm install vue-router

路由案例：
    主页------>Home组件 
    发现页----->Find组件
    设置页----->Setting组件

路由的基本使用：
    1、创建我们需要的组件
    2、在router.js中设置匹配规则
    3、在APP.Vue中使用router-view用来放路由匹配的组件
    4、使用router-link通过点击实现匹配路由

在vue-cli中有两个地方可以放组件，一个是components,一个是views
如果一个组件是页面级的组件放到views中，如果一个组件是通用级的
组件，放到components中

---------------------------------嵌套路由



   
 
        
       
 
