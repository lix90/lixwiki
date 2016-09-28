# Shell

什么是 shell？

> SHELL 作为一种用户接口，它实际上是一个能够解释和分析用户键盘输入，执行输入中的命令，然后返回结果的一个解释程序 (Interpreter, 例如在 Linux 下比较常用的 Bash)。

简单说来，shell 是用户与计算机操作系统内核之间的沟通桥梁，不是通过图形界面上的点按拖拽等动作，而是一个个命令，甚至一个具有特定语法结构的脚本文件。

命令执行优先顺序

一个命令的别名（alias)、函数(function)，内置命令（builtin)和程序(program)的执行优先次序：
> 先 alias ---> function ---> builtin ---> program 后

特殊符号：`|, &, >, <, >>, <<`

问题：

为什么要学习 shell 脚本？
- 自动化管理
- 追踪与管理系统
- 简单入侵侦测
- 连续指令单一化
- 简易的文档处理
- 跨平台支持与学习历程较短

---
参考学习资料：
- [高级 Bash 脚本编程指南](http://man.lupaworld.com/content/develop/advance_bash_scriipt_progaming_guide.pdf)
- [Shell 编程范例](https://tinylab.gitbooks.io/shellbook/content/)
- [Linux命令行上程序执行的那一刹那！](http://www.cppblog.com/cuijixin/archive/2008/03/14/44463.html)
- [學習 Shell Scripts](http://linux.vbird.org/linux_basic/0340bashshell-scripts.php)
