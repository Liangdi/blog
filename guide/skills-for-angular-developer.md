# angular 开发所需技术能力
* Author: Liangdi(wu@liangdi.me)
* Last Updated(2017-07-12)

所需能力
>了解: 知道相关技术/工具以及其基本用途，能安装使用

>会用: 会使用相关技术/工具的基本能力，解决入门级问题

>熟悉: 能使用相关技术/工具进行生产工作，遇到问题能深入分析解决问题

>精通: 深入了解相关技术/工具的原理知识，能提供相关技术/工具的整体性解决方案

### 工具
* angular-cli(ng):
  > angular 项目使用 angular-cli 创建， angular-cli 是一个 node 的包

  所需能力: 熟悉

  能力检测：
  * 创建/调试/构建项目
  * 使用 angular-cli 生成不同功能模块代码模板
  * 常用问题排查
* node
  > nodejs 是 angular-cli 的开发语言，需要通过 npde 的 npm 工具安装 angular-cli

  所需能力: 了解

  能力检测:
    * 通过 nvm 安装 node https://github.com/creationix/nvm , for windows: https://github.com/coreybutler/nvm-windows
* npm
  > node 的包管理工具

  所需能力：会用

  能力检测:
    * 能正确的安装常用工具以及项目依赖包
    * 理解 npm install -g 与 npm instlal 的不同
    * 理解 dependencies 和 devDependencies 的不同
* git
  > 代码版本管理工具

  所需能力: 熟悉

  能力检测:
  * git init / git clone
  * git status / git pull / git add / git commit / git push
  * git branch / git merge / git tag
  * git revert / git checkout
  * git stash / git rebase

### 面向对象基础
* 面向对象设计理论
  > 面向对象设计是设计可扩展，代码复用高的复杂系统的合适选择

  所需能力：熟悉

  能力检测：
    * 熟悉面向对象的理论基础
    * 熟悉基本概念：抽象，封装，组合，继承，耦合，接口，多态
    * 实践面向对象的软件设计

* 基本设计模式
  > 设计模式是面向对象设计领域对常见问题概括的经验，是面向对象软件开发的共同语言，每一种设计模式都比较好的解决了一类问题，熟悉基本的设计模式是必备知识

  * 单例模式： angular 中的依赖注入就是单例模式的应用
  * 装饰器模式： angular 中的 @NgModule/@Component 等 Decorator 就是装饰器模式的应用
  * 观察者模式： RxJs 中基本的模式就是观察者模式

### angular
 > 一站式的前端框架

 所需能力：熟悉

 能力检测：
  * 熟悉 angular 的架构设计
  * 熟悉视图模板的语法
  * 熟悉 angular 开发中模块(@NgModule)的应用
  * 熟悉路由模块的应用, 路由以及跳转，内嵌路由
  * 熟悉 Http 模块的应用，泛指前后端交互的相关技术，不限于：ajax , websocket , http 协议，以及各种应用层协议（如 MQTT）等
  * 熟悉动画模块的应用
  * 熟悉 Form 模块的应用，表单创建和验证
  * 充分理解服务 (Service) 的理念，熟悉其在前端开发中的应用
  * 熟悉内置管道 (Pipe) ，并且能编写自定义管道
  * 理解指令 (Directive) ，并且能编写自定义组件
  * 熟悉 angular 标准包的 API (https://angular.io/api)

### typescript
 > angular 使用的编程语言，前端必须熟练掌握

 所需能力：熟悉

 能力检测：

 * 熟悉 ts 的基本数据类型
 * 熟悉 ts 的语法，包括但不限于：分支/循环结构，接口，Class，泛型，枚举，函数等
 * 熟悉接口 (Interface) 和类 (Class) 的区别以及相关应用
 * 泛型相关知识
 * 装饰器相关知识
 * 模块化相关知识
 * lambda 表达式相关支持，理解函数式编程的思想
 * 官方文档 (http://www.typescriptlang.org/docs/handbook/basic-types.html)

### ES6
  > 由于 typescript 是 ES6 的超集，所以掌握 typescript 的同时，需要了解 ES6 本身和 typescript 的差别

  所需能力: 熟悉

  参考文档：(http://es6.ruanyifeng.com/)

### CSS/LESS/SASS
  > less / sass 也是必备技能

  所需能力: 熟悉

  * 熟悉各种 css3 级别的选择器的写法
  * 熟悉 flex 布局，以及响应式布局的原理
  * 了解常用页面类型的布局
  * 熟练使用 css3 的动画: 元素动画效果，交互动画效果，转场动画效果
