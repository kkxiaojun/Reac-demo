# todoList
## 注意点
`react.js`细节
1. 尽量不要用index做key（为什么）
> key 帮助 React 识别哪些元素改变了，比如被添加或删除。因此你应当给数组中的每一个元素赋予一个确定的标识。如果<font color=red>列表项目的顺序可能会变化</font>，我们不建议使用索引来用作 key 值，因为这样做会导致性能变差，还可能引起组件状态的问题。
2. 方法需要绑定this（为什么）
> 在 JavaScript 中，class 的方法默认不会绑定 this。
3. state只能用setState改变
4. 对于数组的新增可以使用展开运算符`[...this.state.mapList, a, b]`


`JSPX`细节

1. 样式应该用`className`代替`class`
2. `dangerouslySetInnerHTML`不会被转义。`JSX`默认是转义的。
3. `for`应该用`htmlFor`代替
