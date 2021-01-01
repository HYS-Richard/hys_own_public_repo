# GDB learning note

[toc]

## References

[GDB中文手册](https://blog.csdn.net/joliny/article/details/3261466?utm_medium=distribute.pc_relevant_t0.none-task-blog-BlogCommendFromBaidu-1.control&depth_1-utm_source=distribute.pc_relevant_t0.none-task-blog-BlogCommendFromBaidu-1.control)

## 概述(what is gdb and it usually used to do what)

### what is gdb

- GDB  是GNU开源组织发布的一个强大的UNIX下的程序调试工具。或许，各位比较喜欢那种图形界面方式的，像VC、BCB等IDE的调试，但如果你是在  UNIX平台下做软件，你会发现GDB这个调试工具有比VC、BCB的图形化调试器更强大的功能。所谓“寸有所长，尺有所短”就是这个道理

### its function

- 1、启动你的程序，可以按照你的自定义的要求随心所欲的运行程序。
  2、可让被调试的程序在你所指定的调置的断点处停住。（断点可以是条件表达式）
  3、当程序被停住时，可以检查此时你的程序中所发生的事。
  4、动态的改变你程序的执行环境。

## 常用指令

- 直接回车：表示重复上一次指令
- l :表示列出代码: -------(gdb) l
- 

