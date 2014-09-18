cplusplus_attention
============

平时遇到的C++的问题汇总

在预分配的内存上创建对象，可以用placement new构造
语法：CTest * pFirst = new(pBuffer) CTest // 在pBuffer上分配CTest结构体
