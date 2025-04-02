### 1.c++11之constexpr与const区别
c++11中新增加了constexpr关键字，二者主要区别为：
1. const用于表示被修饰变量或函数具有只读的特性，无法修改，而constexpr用于表示被修饰变量具有“常量特性”。
2. **`constexpr`**: 表示编译时常量，它要求变量在编译时就必须能够求值，无需等到运行时计算，极大提高运行效率。而 **`const`**：表示运行时常量。  
   [点击查看const和constexpr详细区别](https://zhuanlan.zhihu.com/p/685959718)
### 2.c++四种类型转换
在编写c++代码过程中，经常用到类型转换，如父类指针或引用转换为子类指针或引用，常量地址转换为类或结构体指针等等。  
c++中主要有四种强制类型转换，要与C风格的类型转换相区分：  
1.static_cast  
2.dynamic_cast  
3.reinterpret_cast  
4.const_cast  
[点击查看四种类型转换的用法及区别](https://blog.csdn.net/weixin_45031801/article/details/142147962)  
