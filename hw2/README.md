一、判断题

1. Java 是编译型语言。
```
即是编译型语言，也是解释型语言。先从源代码编译成字节码，再由虚拟机解释执行。
```

2. Javascript 中，不区分大小写字母，也就是说 A 和 a 是同一个变量。
```
错，区分大小写。
```

3. Javascript 中的常量包括 String、Number、Boolean、Null、Undefined。
```
错，常量包括 Number、Boolean、Null。
```

4. String 字符串的语法中既可以使用单引号，也可以使用双引号。
```
对，但是不要混用。
```

5. typeof 是用来判断变量类型，不可以当作运算符使用。
```
错，typeof 是运算符。
```

6. 任何值和 undefined 运算，undefined 可看做 0 运算。
```
错，任何值和 undefined 运算，结果都是 NaN。
```

二、请分别描述下列代码中“+”的作用。
1. console.log(“年龄:” + 20); 
```
字符串拼接
```
2. console.log(11+22+33); 
```
数字相加
```
3. console.log(“网络 + 安全”); 
```
字符串拼接
```
4. 
```
var a = 1; 
var b = 2;
console.log(“a” + b); 
```
```
字符串拼接
```
5. 
```
var a = 1;
var b = 2;
console.log(“a + b”);
```
```
字符
```

三、计算下述代码的打印值
```
var a = 10;
var b = 10;
console.log(a++); // 10
console.log(++a); // 12
console.log(–b);  // -10
console.log(b–);  // error
```
