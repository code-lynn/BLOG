###问题
    1.在根作用域绑定数据$rootSscope.lists，添加页执行savebook()，详情页显示。刷新页面弹出debugger，不报错？
  
    2.放在根作用域$rootSscope.lists，隔离作用域booklist下的$scope.lists=$rootSscope.lists;提示$rootSscope未定义？
   
    3.音乐播放控件太low，有没有更改播放控件的方法？
    
    4.mybook-添加图书后，数据暂时存在缓存里，新添加的数据点击-跳转详情，却调到主页去了？
###未完成效果
    1.media延迟加载背景图片
    2.搜索栏-百度搜索
    3.登录页+第三方登录
      login页点击提交验证js
      本地存储cookie-注册用户的信息
      只有登录的用户才可以发表文章
    4.整理笔记-添加到模板
      DOM库
      事件库
      运动库
      utils
      js五大模块
    5.首页简历图片5轮播
    6.项目中添加拖拽、走马灯等效果demo
###项目介绍
    1.本项目没有配置后台server及数据库
    2.media模块采用jsonp技术请求数据
    3.mybook-booklists是把原始数据暂存到了$rootScope上.
    4.angular实现前端页面跳转等技术。
    5.bootstrap实现基本布局。