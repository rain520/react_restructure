## react
- 声明式
- 组件化
- 一次学习，到处编写 通用性 跨平台

## 函数组件与类组件的异同
相同点
- 他们都是可以接受属性并且返回react元素

不同点
- 编程思想不同 类组件基于面向对象编程，函数组件面向函数编程
- 内存占用  类组件创建并保存类的实例，会占用一定内存，函数组件不需要创建类的实例，节约内存
- 捕获特性  函数组件具有值捕获特性
- 可测试下
- 状态
- 生命周期
- 逻辑复用 类组件可以通过继承实现逻辑的复用，但官方通过组件优于继承，函数组件可以通过hooks实现组件复用 
- 跳过更新  shouldUpdateProps memo
- 发展前景 未来函数组件会成为主流，因为它可以更好的屏蔽this问题、规范以及复用
- 类组件复用逻辑一般用HOC 高阶组件 1、写起来马阿帆，2、容易出现bug 3、继承静态属性还需要额外处理 4、如果复用逻辑太多，多层嵌套，非常麻烦，不易阅读
- 函数状态，更方便并发渲染，方便暂停和启动
- 