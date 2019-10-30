### [html] html5 中的 form 怎么关闭自动完成？

`form` 有个 `autocomplete` 属性, 取值为 `off`/ `on`, 默认 `on`, 开启自动完成. 可通过设置该属性为 `off` 来关闭自动完成.

### [css] ::before 和:after 中单冒号和双冒号的区别是什么，这两个伪元素有什么作用？

`:` 时 css3 之前的语法, `::` 时 css3 标准. 伪元素(Pseudo-element)均用 `::` 表示, 用于区分伪类(Pseudo-class).

`::after` 是在匹配元素的内部创建一个元素并插入到最后.

`::before` 是在匹配元素的内部创建一个元素并插入到最前面.

### [js] 说说你对 javascript 的作用域的理解

js 所有变量都有其能作用的范围, 范围内均可访问该变量, 但在范围外无法访问. 这个作用范围就是作用于.
js 作用域为词法作用域, 所有变量的查询路径在书写代码时就已经确定. 但也存在动态作用域: 如 eval, 使用 eval 时会在执行位置动态插入字符串并执行.

### [软技能] http 都有哪些状态码？

常用状态码可分为四类

- 2xx, 用于资源请求成功。
- 3xx, 用于重定向。
- 4xx, 用于客户端错误。
- 5xx, 用于服务器内部错误。