# introduction

设计思想：编译时加载或静态加载

#### export

| `export`可以输出变量、函数、类

```js
export var firstName = "Lebron";
export var lastName = "James";
export var year = 1996;

var firstName = "Lebron";
var lastName = "James";
var year = 1996;

export { firstName, lastName, year };
```

两种写法:

- 直接使用`export`关键字
- 在`export`关键字后面的`大括号`指定要导出的变量

#### import