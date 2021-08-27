# 课表( v1.0 )


## 零-关于本课程

## 一 前置的概念解析   (建议时长: 8min + 15min + 15min)
- tree型数据结构
- MVC模式——数据、视图与控制层
- MVVM模式——模型与视图的映射关系


## 二 抽离视图模型——vDomTree与数据 (建议时长: 15 + 15 + 30)
### VdomTree即dom树的模型
- 什么是vDom
- VDomTree是domTree的模型
### vDomTree(模型)与domTree(视图)形成映射关系
- 映射，就是同步数据结构与数据变更
### 如何维护vDomtree?
- 数据与vDom树的绑定
- 数据层的维护
- 数据更新 -> vDom树的更新 -> 映射 -> dom树的更新

## 三 十分钟入门react (建议时长: 20)
### react的设计思想
- jsx语法糖与vDom树
- ReactDOM-映射-同步react-vdomTree与domTree的数据结构与数据变更
- react的本质 - 维护模型(维护vDomTree),映射视图 ———— 同步模型与视图的数据结构与数据变更!


## 四 组件化思想 (建议时长:  30 + 15 + 25)
### 原生组件化
- 组件化的概念
- 构造函数与类与组件
- 面向对象与组件实例
- 参数的传递
- 函数的实例化
- 父子实例的通信方式

### 函数式组件
- 函数式组件
- props通信与单向数据流


### 类组件简介
- React.Component
- 继承
- 生命周期钩子

## 五 react模型的维护 (建议时长:  30 + 30)
### commit与diff算法
- commit-提交树结构数据的变更！
- diff - 变更前后的差异！ 映射到 视图中！
- 列表渲染
- diff优化——key值的意义

### 模型数据层中的特殊数据与内置的控制层api
- 类组件的特殊实例属性 state 与 this.setState
- state更新 => 模型更新 => diff => 映射 =>视图更新
- 状态提升

## 六 组合与继承 (建议时长:  15 + 20 + 15)

### react组合
- react中的插槽
- 组合

### 继承
- 继承extends

### 高阶函数与类的装饰器与高阶组件 
- 高阶组件预热

## 七 总结React：有点东西 (建议时长:  30)
- Props与State的限制级
- react框架的本质：MVVM 
- v-dom的优点与缺点?
- diff算法的优点与缺点

# 进阶吧，React！

## 八 Dom操作，ref (建议时长:  20 + 25)
- 回流与重绘
- dom操作的场景
- Ref的三个历程
- ref的其他作用
- ref转发

## 九 组件间的隔代通信 与 context上下文  (建议时长:  15 + 15)
- context的本质
- context的两个历程


## 十 状态提升与状态分发 (建议时长:  20 + 20)
- 状态提升 UI组件与容器组件
- 状态分发 
- 手写Provider实现状态提升+分发

## 十一 函数组件与hooks  (建议时长:  25 + 20)
- 函数组件的优缺点
- 闭包与useRef
- hooks！
- useCallback与useMemo
- useState

## 十二 副作用  (建议时长:  25 + 20)
- 什么是副作用
- useEffect
- 副作用与消除副作用
- useLayoutEffect


## 十三 react的底层实现！ (建议时长:  20 + 25)
- vdom？不，现在是fiber节点
- commit的姿势？以树为单位diff的致命缺点-线程阻塞！
- 并发模式！18版本！
- 链表结构与hooks

## 十四 react的全面回顾 (建议时长: 30 + 20) 
- 模型与vdom
- diff 与 fiber
- 类组件中生命周期与函数组件副作用
- 并发模式与不安全的生命周期
- 状态提升与状态分发
- 统计组件间通信的所有姿势

## 十五 SPA与路由 (建议时长: 25 + 25) 
- 路由的本质与实现
- React-router-dom

## 十六 高阶函数与类的修饰器与react高阶组件 (建议时长: 30) 
- 高阶函数与类的修饰器
- 高阶组件

# 走向React的巅峰  
## 十七 ui组件性能的极限  (建议时长: 30 + 30) 
- 状态提升-UI组件与容器组件
- PureComponent
- renderProps
- 函数式组件
- useRef/useCallback/useMemo

## 十八 模型自带的优化！ (建议时长: 20  + 10) 
- 事件代理 与 react中的合成事件
- xss攻击？映射自带防注入

## 十九 React提供的几个API  (建议时长: 10 + 10 + 10) 
- React.Fragment
- 错误边界
- React.Lazy与React.Suspense

## 二十 react-spa全方位优化 (建议时长: 30 ) 
略

## 二十一 react-spa项目全解析 (建议时长: 20  + 10) 
- 目录设计
- 全局状态管理库react-redux 

## 二十二 组件封装的关键点 (建议时长: 20) 
- Props？功能设计
- 组件文档-md语法

## 二十三 react中单元测试  (建议时长: 30) 
- 单元测试？
- 用例
- react中的单元测试

## 二十四 react生态讲解  (建议时长: 25 + 25) 
- react-router与 react-router-dom的版本历程
- ant-design 与 ant Pro
- react语法的native混合开发框架 react-native
- react语法的小程序开发框架 remax
- react语法的多端框架 rax || taro || nanachi

## 二十五 react项目开发实战 (建议时长: 140) 
- 业务逻辑的抽离！极度优雅的代码范式！

## 二十六 react-ssr?nextjs


## 二十七 react-native项目实战 (建议时长: 50) 

## 二十八 tarojs的项目实战 (建议时长: 50) 

## 二十九 react面试题全修秘籍 (建议时长: 80)


