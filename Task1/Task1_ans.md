# Task1

## 什么是编译器？

所谓编译器，就是实现高级语言翻译成低级语言（汇编语言）使用的功能性程序，编译器并不是现实中存在的机器名称，而是一类实现上述功能的软件，，如gcc

## 编译器前端的主要任务是什么？

前端的主要任务是实现对源程序（高级语言）的词法分析、语法分析、语义分析等任务。

## ex.编译器后端的主要任务是什么？

编译器后端主要负责目标架构的代码的生成与寄存器的分配，并对程序执行面向具体架构的具体优化策略

## 编译器中端的主要任务是什么？

据我所知，部分编译器并不具有明显的中端过程，而对于部分具有中间表示（IR）的编译器（如llvm架构编译器），可以通过编写针对对IR的优化pass实现通用级别的优化，而对于不显式含有ir的编译器，中端也会进行优化，但是很难追踪这一过程。
