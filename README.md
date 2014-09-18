cplusplus_attention
============

平时遇到的C++的问题汇总

在预分配的内存上创建对象，可以用placement new构造
语法：CTest * pFirst = new(pBuffer) CTest // 在pBuffer上分配CTest结构体

非类型模板形参
语法：template<int a> class B {};
非类型模板形参只能是整型、指针、引用，实参必须是一个常量表达式
