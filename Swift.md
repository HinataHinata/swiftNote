## 网页原地址：https://swift.org
从这个网站开始学习。
1 swift是开源实现。地址在这里 https://github.com/apple/swift.git
2 首先是吹的几个牛，swift是应用现代化方法构建的安全、高性能、软件设计模式。
    Swift is a general-purpose programming language built using a modern approach to safety, performance, and software design patterns. 没想好咋翻译，总之是先吹为敬。
主要提到的三大特点。
# 安全
    不确定性是安全的敌人
    开发者的错误应该在软件成品被制作出来之前被捕获。
    swift是语法是严格的，但是清晰的表达长远来看是节省时间的。
# 快
    本来想说快速，但是感觉快比快速还要快。
    swift的目标是替代 一些基于C的语言，比如 C C++ Objective-C。所以要快
    性能要求是可预测的，并且是始终如一的。
# 富有变现力
    swift 参考现代语言设计理念，应用最新的计算机科学研究成果。
    
    # 其他 
    提到工具和语言生态系统。
    努力为开发者提供工具箱， to build quickly, to present excellent diagnostics, and to enable interactive development experiences. 
    其实就是X-Code支持和 web-based REPL。总之是蛮厉害的。

# 特性
    关键词 代码方便读写 类型推断 消除头文件 提供命名空间 自动管理存储 不需要打分号 借鉴OC命名，提高方法可读性。
    其他特性：
    Closures unified with function pointers
    Tuples and multiple return values
    Generics
    Fast and concise iteration over a range or collection
    Structs that support methods, extensions, and protocols
    Functional programming patterns, e.g., map and filter
    Powerful error handling built-in
    Advanced control flow with do, guard, defer, and repeat keywords
    
    ## 安全性 
    变量在使用前被初始化
    数组和整数检查溢出
    自动管理memory
    变量初始化表明意图 let var
    
    Another safety feature is that by default Swift objects can never be nil, and trying to make or use a nil object will results in a compile-time error. This makes writing code much cleaner and safer, and prevents a common cause of runtime crashes. However, there are cases where nil is appropriate, and for these situations Swift has an innovative feature known as optionals. An optional may contain nil, but Swift syntax forces you to safely deal with it using ? to indicate to the compiler you understand the behavior and will handle it safely.

# swift.org and Open Source
    开源实现，Apache 2.0 license。
    github地址 https://github.com/apple/swift.git
    
    ...
    
    支持的操作系统：iOS macOS watchOS tvOS
    Xcode开发环境
    
    还可以运行在 Linux系统，REPL LLDB
    
    
    BLOG 和 DOWNLOAD 提供了一些发布公告和swift版本啥啥啥
    
    
