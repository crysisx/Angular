#Angular
=======

###Angular test
- AngularJS 是一个 JavaScript 框架
- AngularJS 是一个 JavaScript 框架。它是一个以 JavaScript 编写的库。
- AngularJS 是以一个 JavaScript 文件形式发布的，可通过 script 标签添加到网页中.

-----------------

###ng-app 指令
- ng-app 指令定义了 AngularJS 应用程序的 根元素。
- ng-app 指令在网页加载完毕时会自动引导（自动初始化）应用程序。
- ng-app 通过一个值（比如 ng-app="myModule"）连接到代码模块。

###ng-init 指令
- ng-init 指令为 AngularJS 应用程序定义了 初始值。

通常情况下，不使用 ng-init。您将使用一个控制器或模块来代替它。


###ng-model 指令
- ng-model 指令 绑定 HTML 元素 到应用程序数据。

ng-model 指令也可以：

- 为应用程序数据提供类型验证（number、email、required）。
- 为应用程序数据提供状态（invalid、dirty、touched、error）。
- 为 HTML 元素提供 CSS 类。
- 绑定 HTML 元素到 HTML 表单。
###ng-repeat 指令
ng-repeat 指令对于集合中（数组中）的每个项会 克隆一次 HTML 元素。

----

###AngularJS 扩展了 HTML
- AngularJS 通过 ng-directives 扩展了 HTML。
- ng-app 指令定义一个 AngularJS 应用程序。
- ng-model 指令把元素值（比如输入域的值）绑定到应用程序。
- ng-bind 指令把应用程序数据绑定到 HTML 视图。

###什么是 AngularJS？
- "AngularJS 是专门为应用程序设计的 HTML。"
- AngularJS 使得开发现代的单一页面应用程序（SPAs：Single Page Applications）变得更加容易。
- AngularJS 把应用程序数据绑定到 HTML 元素。
- AngularJS 可以克隆和重复 HTML 元素。
- AngularJS 可以隐藏和显示 HTML 元素。
- AngularJS 可以在 HTML 元素"背后"添加代码。
- AngularJS 支持输入验证。
###AngularJS 指令
- AngularJS 指令是以 ng 作为前缀的 HTML 属性。
- ng-init 指令初始化 AngularJS 应用程序变量。

###AngularJS 表达式
- AngularJS 表达式写在双大括号内：{{ expression }}。
- AngularJS 表达式把数据绑定到 HTML，这与 ng-bind 指令有异曲同工之妙。
- AngularJS 将在表达式书写的位置"输出"数据。
- AngularJS 表达式 很像 JavaScript 表达式：它们可以包含文字、运算符和变量。

实例 {{ 5 + 5 }} 或 {{ firstName + " " + lastName }}

###AngularJS 数字
- AngularJS 数据就像 JavaScript 数字
- 使用 ng-bind 的相同实例

###AngularJS 字符串
- AngularJS 字符串就像 JavaScript 字符串
- 使用 ng-bind 的相同实例

###AngularJS 对象
- AngularJS 对象就像 JavaScript 对象
- 使用 ng-bind 的相同实例

###AngularJS 数组
- AngularJS 数组就像 JavaScript 数组
- 使用 ng-bind 的相同实例

###AngularJS 指令
- AngularJS 指令是扩展的 HTML 属性，带有前缀 ng-。
- ng-app 指令初始化一个 AngularJS 应用程序。
- ng-init 指令初始化应用程序数据。
- ng-model 指令把应用程序数据绑定到 HTML 元素。

###数据绑定
- 上面实例中的 {{ firstName }} 表达式是一个 AngularJS 数据绑定表达式。
- AngularJS 中的数据绑定，同步了 AngularJS 表达式与 AngularJS 数据。
- {{ firstName }} 是通过 ng-model="firstName" 进行同步。

###重复 HTML 元素
- ng-repeat 指令会重复一个 HTML 元素

 
