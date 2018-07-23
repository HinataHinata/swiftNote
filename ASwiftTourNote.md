# A Swift Tour Note
## 原文地址 https://docs.swift.org/swift-book/GuidedTour/GuidedTour.html#//apple_ref/doc/uid/TP40014097-CH2-ID1
1 Hello World
print("Hello world!")
一条语句就是一段完整的程序。 不需要引入input/output 不需要 main 函数 不需要语句结尾的分号。

let 修饰不可变变量 var 修饰可变变量。
```py
var myVariable = 42
myVariable = 50
let myConstant = 42
```
类型推断，编译器会推断 myVariable 是 int 类型
如果类型不能够被推断出来，则可以手动指定
```py
let implicitInteger = 70
let implicitDouble = 70.0
let explicitDouble:Double = 70
```
变量从不会进行隐式转换，当需要转变类型时需要手动指定
```py
let label = "The width is "
let width = 94
let widthLabel = label + String(width)
```

字符串中使用参数  \()
使用[] 定义数组和字典。最后一个元素之后可以有逗号 “，”
创建空的数组和字典使用初始化语法。
```py
let emptyArray = [String]()
let emptyDictionary = [String:Float]()
```

Control Flow
1 if 语句必须是 Boolean 表达式
2 if 语句可以和 let 配合使用，防止变量是nil，！和？的配合使用方法
```py
var optionalString:String? = "Hello"
if let name = optionalString{
    print(name)
}
```
3 optional value 和 ?? 配合使用
```py
let nickName:String? = nil
let fullName = "John Appleseed"
let informalGreeting = "Hi \(nickName ?? fullName)"
print(informalGreeting)
```

3 switch 语句支持任意类型的数据，和多种比较操作，并不只限制于整数类型和等于操作。 匹配上之后就跳出，没有break
4 for - in 字典是无序容器，所以key和value是按照任意顺序迭代的。

## Functions and Closures
1 函数定义参数名称和返回类型 返回值可以是tuple 用于实现返回多个值
2 functions can be nested
3 functions are a first-class type this means that a funciton can return another function as its value.
4 a function can take another function as one of its arguments.

