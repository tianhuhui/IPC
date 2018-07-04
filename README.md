# IPC
UNIX Network Programming Volume2：Interprocess Communications

UNIX网络编程 卷2：进程间通信

IPC传统上是Unix中一个杂乱不堪的领域。虽然有了各种各样的解决办法，但是没有一个是完美的。我们的讨论分成4个主要领域：

- 消息传递（管道、FIFO、消息队列）；
- 同步（互斥锁、条件变量、读写锁、信号量）；
- 共享内存区（匿名共享内存区、有名共享内存区）；
- 过程调用（Solaris门、Sun RPC）。

我们考虑单个进程中多个线程间的IPC以及多个进程间的IPC。
