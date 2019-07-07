## 为什么学习TypeScript

* 超集
* 面向对象（Prototype, Function, Object -> Class）
* 类型检查  (静态类型， 强类型), 编译前能提前发现错误，例如undefined错误
* 函数签名可以一定程度减少文档注释，自带文档特性
* IDE 自动完成提示，追踪函数定义， 潜在错误提示等等
* 适合中大型项目


## JavaScript弊端
* 一个变量可以赋值不同类型的值
* 函数签名不严谨，导致运行结果无法预料，容易产生Bug

TypeScript = JavaScript + Type + Other features

### 编译

```
$ npx tsc index.ts
```