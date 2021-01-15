[TOC]



### 简历

- [《大厂面试》面试官看了直呼想要的简历](https://juejin.cn/post/6844904034218803214)
- [面试官到底想看什么样的简历？](https://juejin.cn/post/6844903879973273607)

### HTMl+CSS

- [实现水平垂直居中（所有方法）](https://www.cnblogs.com/xiaohuochai/p/5441210.html)

- margin塌陷

- [flex布局](https://juejin.cn/post/6844904004728668168)

- [不怕你用不上！CSS 列表项布局技巧](https://juejin.cn/post/6844903741494296590)

- [【CSS】Grid 布局总结](https://juejin.cn/post/6844903777888108557)

- [2019年了，你还不会CSS动画？](https://juejin.cn/post/6844903845470945294)

- [你未必知道的CSS知识点（第二季）](https://juejin.cn/post/6844903960386469895)

- 伪类和伪元素的区别

  伪类和伪元素是用来修饰不在文档树中的部分，比如，一句话中的第一个字母，或者是列表中的第一个元素。下面分别对伪类和伪元素进行解释：

  伪类用于当已有元素处于的某个状态时，为其添加对应的样式，这个状态是根据用户行为而动态变化的。比如说，当用户悬停在指定的元素时，我们可以通过:hover来描述这个元素的状态。虽然它和普通的css类相似，可以为已有的元素添加样式，但是它只有处于dom树无法描述的状态下才能为元素添加样式，所以将其称为伪类。

  伪元素用于创建一些不在文档树中的元素，并为其添加样式。比如说，我们可以通过:before来在一个元素前增加一些文本，并为这些文本添加样式。虽然用户可以看到这些文本，但是这些文本实际上不在文档树中。

  区别：

  伪类的操作对象是文档树中已有的元素，而伪元素则创建了一个文档树外的元素。因此，伪类与伪元素的区别在于：**有没有创建一个文档树之外的元素。**

  CSS3规范中的要求使用双冒号(::)表示伪元素，以此来区分伪元素和伪类，比如::before和::after等伪元素使用双冒号(::)，:hover和:active等伪类使用单冒号(:)。除了一些低于IE8版本的浏览器外，大部分浏览器都支持伪元素的双冒号(::)表示方法。

- BFC
- AFC
- GFC

### Javascript

- [类型与变量](https://github.com/charmJiang/front-end-knowledge-systems/blob/main/javascript/1.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md)

  - 基本数据类型和复杂数据类型
  - 基本数据类型和复杂数据类型区别
  - `null`和`undefined`区别
  - 类型识别
    - [`Obejct.prototype.call()`的原理](https://zhuanlan.zhihu.com/p/118793721)
  - `js`对象的底层数据结构是什么 [参考链接1](https://www.mdeditor.tw/jump/aHR0cHM6Ly93d3cuamlhbnNodS5jb20vcC83ZDNhYjlhMjJiMTE=) [参考链接2](https://www.mdeditor.tw/jump/aHR0cHM6Ly93d3cuY25ibG9ncy5jb20vemhvdWx1anVuL3AvMTA4ODE2MzkuaHRtbA==)
  - `Symbol`类型在实际开发中的应用、可手动实现一个简单的 `Symbol` [ES6 的 Symbol 类型及使用案例](https://my.oschina.net/u/2903254/blog/818796)
  - 隐性转换
  - 转 boolean
  - 四则运算
  - [== 和 ===](https://github.com/charmJiang/front-end-knowledge-systems/blob/main/javascript/1.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#7-%E5%92%8C)
  - 01 + 0.2 === 0.3? [详细讲解](https://juejin.im/post/5b90e00e6fb9a05cf9080dff)
  - 如何让01 + 0.2 === 0.3 [详细讲解](https://juejin.im/post/5b90e00e6fb9a05cf9080dff)
  - `var`, `let`,`const` 的区别
  - `var`,`let`,`const`原理

- 对象

  - 数组的方法 [js 数组详细操作方法及解析合集](https://juejin.cn/post/6844903614918459406)
  - [判断2个对象是否相等](https://github.com/mqyqingfeng/Blog/issues/41)  [参考链接2](https://juejin.cn/post/6844903802298974221)

- 原型链

  - instanceof原理
  - `new`原理
  - [实现new](https://github.com/mqyqingfeng/Blog/issues/13)
  - [创建对象的多种方式以及优缺点](https://github.com/mqyqingfeng/Blog/issues/15)
  - [继承](https://github.com/yygmind/blog/issues/7)
  - 原型链

- 调用栈以及深入

- [面试官：说说作用域和闭包吧](https://juejin.cn/post/6844904165672484871)

- 变量对象

- 作用域链

- 执行上下文栈

  - [闭包](https://www.mdeditor.tw/pl/pjQR) [掌握JavaScript面试：什么是闭包？](https://juejin.cn/post/6874829017006997511)

    ```javascript
    闭包优点：
    1.可以放一个变量保存在内存中，不被js的垃圾回收机制清除
    2.可以避免变量的全局污染
    3.可以定义模块，将操作函数暴露在外部，细节隐藏在模块内部
    
    闭包的缺点：
    1.容易造成内存泄露
    2.闭包对性能会产生负面影响，包括处理速度和内存消耗
    
    ```

  ```
  
  
  - `this`
  
  - [`V8`垃圾回收机制 ](https://my.oschina.net/LuckyWinty/blog/4662910)     [深入解读 V8 引擎的「并发标记」技术](https://www.oschina.net/translate/v8-javascript-engine)
  ```

- 函数

  - `call`,`apply`,`bind`的实现原理
  - 手写`call`,`apply`,`bind`  [call,apply](https://muyiy.cn/blog/3/3.3.html#call-%E5%92%8C-apply)  [bind](https://github.com/mqyqingfeng/Blog/issues/12)
  - 类数组对象与`arguments`
  - 高阶函数
  - 防抖和节流
  - [请实现一个 add 函数，满足以下功能 add(1)(2)(3) // 6 add(1,2)(3) // 6](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/134)

- 正则

  - [正则表达式不要背](https://juejin.cn/post/6844903845227659271)

- 深浅拷贝的区别

  - [深拷贝（多种方法）](https://muyiy.cn/blog/4/4.3.html#%E5%BC%95%E8%A8%80)
  - 使用广度和深度
  - [如何写出一个惊艳面试官的深拷贝?](https://juejin.cn/post/6844903929705136141)

- 异步

  - 回调地狱
  - `promise`, `promise.all`,`promise.race`原理
  - 手写`promise`, `promise.all`,`promise.race`
  - [BAT前端经典面试问题：史上最最最详细的手写Promise教程](https://juejin.cn/post/6844903625769091079)
  - [9k字 | Promise/async/Generator实现原理解析](https://juejin.cn/post/6844904096525189128#heading-11)
  - [Promise.all处理多次reject/最多n次reject](https://juejin.cn/post/6844903617246265357)
  - `gennnerator`原理
  - 手写`gennnerator`
  - `async...await`原理
  - [Async/Await 如何通过同步的方式实现异步](https://juejin.cn/post/6844903891021086734)
  - 手写`async...await`
  - `promise.all`错误处理，避免拿不到数据
  - [15道ES6 Promise实战练习题，助你快速理解Promise](https://mp.weixin.qq.com/s/EGqfImjSy39UExVYFusIIw)
  - [字节跳动面试官：请用JS实现Ajax并发请求控制](https://juejin.cn/post/6916317088521027598?utm_source=gold_browser_extension)
  - [细说 async/await 相较于 Promise 的优势](https://juejin.cn/post/6844903760217505805)

- 事件

  - 事件代理
  - [20k的前端是这样写事件委托的🐹](https://juejin.cn/post/6844904097372438542)

- 事件循环

  - 浏览器的事件循环（宏任务和微任务）

    

- 模块化

  - [CommonJS 和 ES6 Module 究竟有什么区别？](https://juejin.cn/post/6844904080955932680)
  - [JavaScript 模块的循环加载](http://www.ruanyifeng.com/blog/2015/11/circular-dependency.html)

- `es6`

  - [1.5万字概括ES6全部特性(已更新ES2020)](https://juejin.cn/post/6844903959283367950)
  - [近一万字的ES6语法知识点补充](https://juejin.cn/post/6844903775329583112)
  - [使用ES6的新特性Proxy来实现一个数据绑定实例](https://juejin.cn/post/6844903757675921421)

- DOM

- 正则

  - 匹配邮箱
  - 匹配手机号码

- 其他

  - url获取参数
  - [面试官：前端跨页面通信，你知道哪些方法？](https://juejin.cn/post/6844903811232825357)
  - [面试官：请用一句话描述 try catch 能捕获到哪些 JS 异常](https://juejin.cn/post/6844904143891464200)

### Vue

- 手写一个mvvm
- 虚拟dom原理
- [面试官问: 如何理解Virtual DOM？](https://juejin.cn/post/6844903921442422791)
- [面试官系列(2): Event Bus的实现](https://juejin.im/post/6844903587043082247)
- [面试官: 你了解前端路由吗?](https://juejin.cn/post/6844903589123457031)
- $emit如何触发父组件函数
- 如何解决vuex刷新后数据不见
- [字节跳动面试官：请说一下vuex工作原理（重点就几行代码而已啦）](https://juejin.cn/post/6844904062240948231)
- vue-router原理  [手写vue-router核心原理](https://juejin.cn/post/6854573222231605256) [vue-router原理剖析](https://juejin.cn/post/6844903612930326541)
- [vue-router源码解析 | 1.4w字 | 多图预警 - 【上】🏆 掘金技术征文|双节特别篇](https://juejin.cn/post/6880529850159874062)
- [高级前端开发者必会的34道Vue面试题系列（一）](https://juejin.cn/post/6844904097544405000)
- [高级前端开发者必会的34道Vue面试题系列（二）](https://juejin.cn/post/6844904100014866439)
- [高级前端开发者必会的34道Vue面试题解析（三）](https://juejin.cn/post/6844904106612654088)
- [高级前端开发者必会的34道Vue面试题解析（四）](https://juejin.cn/post/6844904117400240136)
- 如何理解mvvm原理？
- 响应式数据的原理是什么?
- vue监听数组的变化
- 为何vue才用异步渲染
- nextTick作用和原理
- vue生命周期，父子组件生命周期顺序
- ajax放在哪个生命周期
- 何时需要使用beforeDestroy
- vue中computed的特点
- watch中的deep:true是如何实现的
- vue中事件绑定原理
- vue中v-html会导致哪些问题
- v-if和v-show的区别
- 为什么v-for，v-if不能连用
- v-model中的实现原理以及如何自定义v-model
- 组件中data为什么是一个函数
- vue组件通信
- 什么是作用域插槽
- 用vnode来秒速dom结构
- diff算法的时间复杂度
- 简述vue中diff算法原理
- v-for为什么要用key
- 描述组件的渲染和更新过程
- vue中模板编译原理
- vue中常见的性能优化
- vue中相同逻辑如何抽离
- 为什么要用异步组件？
- 谈谈你对keep-alive的了解
- 实现hash路由和history路由
- vue-Router中导航守卫有哪些
- action和mutation区别
- 简述vuex的工作原理
- vue3.0的改进？
- [Vue 开发必须知道的 36 个技巧【近1W字】](https://juejin.cn/post/6844903959266590728)
- [Vue源码: 关于vm.$set()内部原理](https://juejin.cn/post/6844903830837002253)
- [Vue源码探究-虚拟DOM的渲染](https://juejin.cn/post/6844903830899916807)

- [让虚拟DOM和DOM-diff不再成为你的绊脚石](https://juejin.cn/post/6844903806132568072)





### React

- [React 灵魂 23 问，你能答对几个？](https://mp.weixin.qq.com/s/AGY6ZV4gIuNX1HLsUbXbAg)
- [React 开发必须知道的 34 个技巧【近1W字】](https://juejin.cn/post/6844903993278201870)
- [如何对 React 函数式组件进行优化](https://juejin.cn/post/6844904000043614222)

### Axios

- [Axios 源码解析](https://juejin.cn/post/6844903824583294984)
- [axios封装以及前端接口处理策略](https://juejin.cn/post/6844903827779354637)

### 性能优化

- [Web 架构师如何做性能优化？](https://juejin.cn/post/6898235695245197325)
- [还在看那些老掉牙的性能优化文章么？这些最新性能指标了解下](https://juejin.cn/post/6850037270729359367)
- [【译】面试官：请你实现一个PWA 我：😭](https://juejin.cn/post/6844904052166230030)
- [拯救你的年底KPI：前端性能优化](https://juejin.cn/post/6911472693405548557?utm_source=gold_browser_extension#heading-23)
- [页面性能优化办法有哪些？](https://mp.weixin.qq.com/s/Gxp0NRFa3HliD6xpDoNgSQ)
- [1.5W+字的全链路前端性能优化送给你](https://mp.weixin.qq.com/s/nqUMUoa2R5fIfzJV5kBBsg)
- [jsliang 求职系列 - 23 - 性能优化](https://juejin.cn/post/6898475853581402120)
- [前端黑科技：美团网页首帧优化实践](https://juejin.cn/post/6844903715262955533)
- [浏览器原理](https://juejin.cn/post/6844903613278470152)

### 网络

- 网络基础
  - OSI七层以及作用 （TCP四层）
  - 建立一个TCP需要三次握手四次挥手，为什么需要三次握手
  - TCP和UDP区别
  - TCP是如何保证传输的可靠性
  - https的握手过程
  - https的工作原理
  - websocket和tcp区别

- [【前端词典】进阶必备的网络基础（上）](https://juejin.cn/post/6844903789078675469)
- [【前端词典】进阶必备的网络基础（下）](https://juejin.cn/post/6844903790789967879)
- [图解HTTPS基本原理](https://juejin.cn/post/6844903912932147207)

- [前端基础篇之HTTP协议](https://juejin.cn/post/6844903844216832007)

- [深入理解https工作原理](https://mp.weixin.qq.com/s/2DqMuTYYvacH6W0339-cUA)
- 简单请求和非简单的请求的区别?如何绕过options请求
- [GET 和 POST请求的本质区别是什么？](https://mp.weixin.qq.com/s/mmxSgjL5dZuV70c3ehYgGQ)
- [面试官问：你了解HTTP2.0吗？](https://juejin.cn/post/6844903734670000142)
- [面试官问到TCP/IP怎么回答才过关](https://juejin.cn/post/6844903617732804622)
- [3000字说说跨域！面试官听完之后露出了满意的笑容😎](https://juejin.cn/post/6844903972742889480)
- [面试官，不要再问我三次握手和四次挥手](https://juejin.cn/post/6844903958624878606)
- [关于三次握手与四次挥手面试官想考我们什么？--- 不看后悔系列](https://juejin.cn/post/6844903834708344840)
- [WebSocket协议以及ws源码分析](https://juejin.cn/post/6844903850667671560)

### web安全

- [【面试篇】寒冬求职之你必须要懂的Web安全](https://juejin.cn/post/6844903842635579405)

- [常见六大 Web 安全攻防解析](https://mp.weixin.qq.com/s/up35Zd8EmEfDVnvxOX9EmA)
- [非对称加密技术- RSA算法数学原理分析](https://juejin.cn/post/6844903511768072199)
- [使用 RSA 和 AES 加密传输数据 js 到 php(前端非对称加密)](http://polande.com/?p=297)

### 数据结构和算法

- [JS版数据结构第二篇(队列)](https://juejin.cn/post/6844903830220439559)

- [重温数据结构系列--树](https://juejin.im/post/6844903825694785550)
- [重温数据结构系列--二叉树、堆](https://juejin.cn/post/6844903827351535624)

- [面试官: 100万个成员的数组取第一个和最后一个有性能差距吗?](https://juejin.cn/post/6844903938068578311)
- [前端该如何准备数据结构和算法？](https://juejin.cn/post/6844903919722692621#heading-18)
- [别再翻了，面试二叉树看这 11 个就够了~](https://juejin.cn/post/6844903938072772616)
- [十大经典排序算法总结（JavaScript描述）](https://juejin.cn/post/6844903444365443080)
- [「算法与数据结构」你可能需要的一份前端算法总结](https://juejin.cn/post/6900698814093459463)
- [前端跳槽面试算法——动态规划](https://juejin.cn/post/6844903846334971918)

### 移动端H5开发

- [关于移动端适配，你必须要知道的](https://juejin.cn/post/6844903845617729549)

- [H5软键盘兼容方案](https://mp.weixin.qq.com/s/wO4pD1bqaS5a2onttGEmHA)
- [移动端适配总结](https://juejin.cn/post/6844903734347055118)
- [移动端开发一些常见问题的解决方案](https://juejin.cn/post/6897937643372937224)
- [移动端网页调试](https://juejin.cn/post/6844903854111195143)
- [移动端1px像素问题的根本原因 | 优质解决方](https://juejin.cn/post/6850418109522640910)
- [移动端布局方案探究](https://juejin.cn/post/6844903565454999560)
- [移动端常见bug汇总001](https://juejin.cn/post/6844903605502214157)
- [移动端常见bug汇总002](https://juejin.cn/post/6844903605502214157)
- [吃透移动端 H5 与 Hybrid｜实践踩坑12种问题汇总](https://juejin.cn/post/6844904024790007815)
- [Hybrid App 应用 开发中 9 个必备知识点复习(WebView / 调试 等)](https://juejin.cn/post/6844903888735174670)
- [【移动端适配】用vw、vh＋媒体查询打造最完美的移动端适配方案](https://juejin.cn/post/6844903857454055438)
- [移动端适配解决方案-vw布局](https://www.xidaren.cn/archives/39/)
- [H5页面监听Android物理返回键]()

### webpack

- [jsliang 求职系列 - 31 - Webpack](https://juejin.cn/post/6901807555316547597)
- [关于webpack4的14个知识点,童叟无欺](https://juejin.cn/post/6844903853905674248)
- [带你深度解锁Webpack系列(进阶篇)](https://juejin.cn/post/6844904084927938567)
- [Webpack 源码研究](https://juejin.cn/post/6844903903675285511)
- [面试官：webpack原理都不会？](https://juejin.cn/post/6859538537830858759)
- [面试官：你使用webpack时手写过loader，分离过模块吗？](https://juejin.cn/post/6844903824356802567)
- [Webpack揭秘——走向高阶前端的必经之路](https://juejin.cn/post/6844903685407916039)
- [📚免费的渐进式教程：Webpack4的16篇讲解和16份代码](https://juejin.cn/post/6844903748783996942)
- [看完这篇，面试再也不怕被问 Webpack 热更新](https://juejin.cn/post/6844903953092591630)

### 浏览器

- [浏览器原理系列10篇正式完结](https://juejin.cn/post/6844903780140466189)

- [浏览器渲染原理（性能优化之如何减少重排和重绘）](https://juejin.cn/post/6844903759378645006)

- [浏览器是如何解析html的？](https://juejin.cn/post/6844903745730396174)

- [浏览器事件循环](https://juejin.cn/post/6844903638238756878) 
- [node事件循环](https://juejin.cn/post/6844904007270563848)
- [浏览器事件循环和node事件循环区别](https://juejin.cn/post/6844903761949753352#heading-11)
- 宏任务和微任务哪个性能更好？
- [面试官问我：说说你对浏览器缓存的理解](https://juejin.cn/post/6854573208444600333)
- [一文读懂前端缓存](https://juejin.cn/post/6844903747357769742)
- [微信面试官不讲武德，一上来就问我Chrome原理和HTTP协议](https://juejin.cn/post/6902556452721229837)
- [「导航渲染流程」你真的知道从输入URL到页面展示发生了什么吗？（内附思维导图）](https://juejin.cn/post/6902032954034225159)
- [史上最详细的经典面试题 从输入URL到看到页面发生了什么？](https://juejin.cn/post/6844903832435032072)

### 项目总结

- 在开发中遇到什么问题？是怎么解决的？
- [前端海报生成的不同方案和优劣](https://mp.weixin.qq.com/s/eUsl-efq78dCJYy7vrROzA)
- [字节跳动面试官：请你实现一个大文件上传和断点续传](https://juejin.cn/post/6844904046436843527)
- [刚教完我司一个面试官OAuth 2.0为什么要先获取授权码code](https://juejin.cn/post/6884934088931688462)
- [深入了解前端监控原理](https://juejin.cn/post/6899430989404045320)
- [正确姿势开发vue后台管理系统](https://juejin.cn/post/6844903928761417741)
- [vue中如何实现后台管理系统的权限控制](https://juejin.cn/post/6844903934545362952)
- [前端大文件上传](https://juejin.cn/post/6844903860327186445)

### 设计模式

- [JS设计模式一：工厂模式](https://juejin.im/post/6844903731239059470)
- [jS设计模式二：单例模式](https://juejin.im/post/6844903731239075853)
- [JS设计模式三：模块模式](https://juejin.im/post/6844903731239059464)
- [JS设计模式四：代理模式](https://juejin.im/post/6844903731243253767)
- [JS设计模式五：职责链模式](https://juejin.im/post/6844903731243253774)
- [JS设计模式六：策略模式](https://juejin.im/post/6844903731243270158)
- [JS设计模式七：发布-订阅模式](https://juejin.im/post/6844903731247448071)
- [前端面试之JavaScript设计模式](https://juejin.cn/post/6844903861606416397)
- [《JavaScript设计模式与开发实践》最全知识点汇总大全](https://juejin.cn/post/6844903751870840839)

### babel

- [Babel 插件原理的理解与深入](https://github.com/frontend9/fe9-library/issues/154)
- [starkwang](https://github.com/starkwang)/**[the-super-tiny-compiler-cn](https://github.com/starkwang/the-super-tiny-compiler-cn)** 这是一个只用了百来行代码的简单编译器开源项目

### Nginx

- [前端必备 Nginx 配置](https://juejin.cn/post/6844903942262882318)
- [前端Nginx那些事](https://juejin.cn/post/6844904102447546382)
- [nginx从入门到实践][https://juejin.cn/post/6844903519003099149]
- [前端的Nginx知识梳理](https://juejin.cn/post/6914160814152744973)

### 脚手架

- [【中高级前端必备】手摸手教你撸一个脚手架](https://juejin.cn/post/6844903896163303438)

### Node

- [面试官问你关于node的那些事（基础篇）](https://juejin.cn/post/6844904196265754638)
- [面试官问你关于node的那些事（进阶篇）](https://juejin.cn/post/6844904177466867726)
- [Node.js + Nginx 部署 HTTPS 服务](https://juejin.cn/post/6844903618013822984)
- [想学Node.js，stream先有必要搞清楚](https://juejin.cn/post/6844903891083984910)
- [Node.js的进程管理](https://juejin.cn/post/6844903757126303758)
- [小马的大前端之路——Node.js初探](https://juejin.cn/post/6844903586384576520)
- [如何在vscode里面调试js和node.js](https://juejin.cn/post/6844903744304316429)

### Koa2

- Koa的核心机制
- [逐行分析Koa中间件机制](https://juejin.cn/post/6844903790185807885)
- [玩转Koa -- koa-router原理解析](https://juejin.cn/post/6844903748423122957)
- 为什么要有洋葱模型
- 中间的使用和理解
- express，koa，egg区别
- compose的实现
- 某些接口允许跨域,某些不允许,如何实现?能不能使用koa2中间件的方式实现一下?
- koa2中ctx.set的等价写法
- koa-compose实现
  - [KOA2 compose 串联中间件实现（洋葱模型）](https://juejin.cn/post/6844903688985657357)

### Mysql

- [MySQL常见语句汇总](https://juejin.cn/post/6844904197305925639)
- [MySQL 三万字精华总结 + 面试100 问，和面试官扯皮绰绰有余（收藏系列）](https://juejin.cn/post/6850037271233331208)
- [MySQL优化面试](https://juejin.cn/post/6844903779284975630)

### 面向未来



### 前端博客推荐

- [木易杨](https://muyiy.cn/)
- [冴羽的博客](https://github.com/mqyqingfeng/Blog)
- [前端基础知识](https://juejin.cn/post/6844903891021086734)
- [前端进阶之道](https://yuchengkai.cn/)
- [浪里行舟](https://juejin.cn/user/4283353031252967/posts) 可以做一个回顾
- [前端工匠](https://github.com/ljianshu/Blog) 可以做之前知识的补充
- [nodejs-learning-guide](https://github.com/chyingp/nodejs-learning-guide)

### 面试题推荐

- [达达前端个人web分享92道JavaScript面试题附加回答](https://juejin.cn/post/6913480482638266382?utm_source=gold_browser_extension)
- [木易杨每天一题](https://github.com/Advanced-Frontend/Daily-Interview-Question)
- [震惊！前端300基础面试题+答案、分类学习整理（良心制作）持续更新](https://juejin.cn/post/6914831351271292936)
- [【周刊-2】三年大厂面试官-前端面试题（偏难）](https://juejin.cn/post/6844903821429178382)
- [【周刊-1】三年大厂面试官-面试题精选及答案](https://juejin.cn/post/6844903814638600205)
- [【周刊-3】三年大厂面试官-十道前端面试题（欢迎挑战）](https://juejin.cn/post/6844903842585247751)

### 其他

- [前端进阶必备，github 优质资源整理分享！](https://juejin.cn/post/6844903902299553806)
- [【Vue进阶】青铜选手，如何自研一套UI库？](https://juejin.cn/post/6844903862931832846)
- [解密初、中、高级程序员的进化之路（前端）](https://juejin.cn/post/6844903897593544718)
- [三个很不错的 Vue 资料](https://juejin.cn/post/6844903860289421326)
- [if 我是前端团队 Leader，怎么制定前端协作规范?](https://juejin.cn/post/6844903897610321934)
- [前端代码质量管理（一）](https://juejin.cn/post/6844903824512008205)

