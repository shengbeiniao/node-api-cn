
返回错误的字符串描述，通过调用 `new Error(message)` 设置。
传给构造函数的 `message` 也会出现在 `Error` 的堆栈跟踪的第一行。
但是，`Error` 对象创建后改变这个属性可能不会改变堆栈跟踪的第一行。


```js
const err = new Error('错误信息');
console.log(err.message);
// 打印: 错误信息
```

