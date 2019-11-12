# Angular

## 快速上手

[Angular 入门：你的第一个应用](https://angular.cn/start) 挺好的，完成前两章就有了完成个人学习项目的基础了。

## Angular CLI 

### 创建项目

创建方法是简单的：

```
ng new project-name
```

坑的地方在于，在 Windows 里， git bash 会跳过配置项引导，给你选择一个默认配置，而使用命令提示符窗口则不会有这个问题。 —— xun哥

### 创建组件

在 Angular 的入门教程里，是使用 Angular Files 插件来新建一个组件。

也可以在命令行里[使用 Angular CLI (ng generate)创建组件、服务、类、路由、指令、管道](http://www.nbsite.cn/qdjs/152)。

有一件奇怪的事情是，有人用 Angular Files 新建的组件的样式表是 css ，而他的项目配置的是 scss ，用 ng generate 则是正确的 scss 。

## 目录结构

@王鹏老师：参考官方文档：[工作区和项目文件结构](https://angular.cn/guide/file-structure)。至于如何组织模块，也可以看下文档的 基本原理>架构>模块 部分。

公共的模块可以放在一个公共的文件夹内（比如 common、shared）。

## 样式封装

相关问题：组件内部的样式无法更改。

解决方法：在选择器前添加 `:host ::ng-deep` 进行样式覆盖。

参考资料：

* [Angular - 组件样式](https://angular.cn/guide/component-styles)
* [关于Angular样式封装 - 知乎](https://zhuanlan.zhihu.com/p/31235358)
* [Angular 的样式封装 - 沈超然的博客 \| ShenChaoran's Blog](https://shenchaoran.github.io/2018/08/22/Angular-的样式封装/)

## 图片路径

在 [DevUIStudy/devui-study-101-isanbel](https://github.com/DevUIStudy/devui-study-101-isanbel) 项目里，贡献者使用了[华为云](https://www.huaweicloud.com)的 header logo （可以直接右键保存到本地）。 图片如何在 angular 项目中使用呢？请看参考资料。

参考资料：

* [angular--图片路径](https://blog.csdn.net/weixin_42429288/article/details/96484668)

## 路由与导航

推荐阅读官方文档 [路由与导航](https://angular.cn/guide/router#routing--navigation) ，从“基础知识”看到“里程碑2:路由模块“就足够完成个人学习项目了。如果您在新建angular项目的时候配置了路由，那路由模块就是一开始就有了。如果不是的话，可以不用模块化，只是模块化会更整洁。

