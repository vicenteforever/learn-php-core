1. 符号表
```
EG()	这个宏可以用来访问符号表，函数，资源信息和常量。
CG()	用来访问核心全局变量。
PG()	PHP全局变量。我们知道php.ini会映射一个或者多个PHP全局结构。举几个使用这个宏的例子：PG(register_globals),
PG(safe_mode), PG(memory_limit)
FG()	文件全局变量。大多数文件I/O或相关的全局变量的数据流都塞进标准扩展出口结构。
```
