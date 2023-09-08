
# strings



`strings`命令在Linux中通常用于从二进制文件中提取可打印的字符串。

默认情况下，它会在输入文件中寻找并打印出长度至少为4个字符长的连续可打印字符序列。

以下是一个基本的使用例子：

```bash
strings filename
```

其中，“filename”是你想检查的文件名。这条命令将打印出文件中所有可打印的字符串。

请注意，`strings`不仅可以应用于纯二进制文件，也经常被用于查看非文本文件（如编译后的对象或者执行文件等）中的文本内容。

`strings`命令通常在`binutils`包中，你可以使用`apt`包管理器进行安装。下面是安装步骤：

```bash
sudo apt-get install binutils
```

