### 基础

#### 赋值

赋值语句不能再函数体外赋值，Name:="a" 自动推倒等价与 var Name string Name="a"

1. 声明一个变量
   ```
   var name type
   name=value
   ```
2. 类型推断Type inference
    如果一个变量有一个初始值，go将自动能够使用初始值来推断该变量的类型
   > var name=value  


