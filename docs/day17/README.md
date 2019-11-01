## [html] 你认为 table 的作用和优缺点是什么呢？

优点

- 兼容性强

缺点

- 标签结构多, 布局相对其他方式需要更多的标签与嵌套.

## [css] 解释下 CSS sprites 的原理和优缺点分别是什么？

将多张小图合成一张大图, 通过指定位置来显示对应的图片.

### 优点

- 减少网络请求数

### 缺点

- 维护困难
- 使用繁琐, 需合成图片, 计算位置
- 更新部分需重新加载整个图片

## [js] typeof('abc')和 typeof 'abc'都是 string, 那么 typeof 是操作符还是函数？

`typeof` 是操作符

```javascript
typeof\("abc"); // 先 ("abc") 返回 "abc", 再执行 typeof "abc"
typeof "abc"; // 标准用法
```

## [软技能] 说说你对 SVN 和 GIT 的理解和区别

没使用过 SVN
Git 是分布式版本控制, 可在多个场景做版本管理, 不依赖服务器. 但不能对单个文件做回滚/拉取操作。