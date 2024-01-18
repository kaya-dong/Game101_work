# Game101_work
### 环境配置

WSL2+Ubuntu20.04+vscode

我遇到的问题是把ubuntu迁移到非C盘的磁盘之后，mnt共享文件夹打不开且vscode中无法配置Ubuntu中的编译器。解决办法是：把Ubuntu20.04映射成网络驱动器，之后在home/user路径下创建工作文件夹。再次用vscode打开创建的文件夹就可以正确的编译了。

参考配置教程：

https://zhuanlan.zhihu.com/p/371080057

https://blog.csdn.net/liangnihei/article/details/127918412
