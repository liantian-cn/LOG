在Linux中，除了`cat`命令外，还有许多其他命令可以用来显示文件内容。以下是一些例子：

1. `less` 命令：这是一个非常有效的工具，它允许你浏览和搜索文件内容。如果文件很大，你可以使用此命令。它还允许你在文件中向前或向后滚动。

```bash
less filename
```
2. `more` 命令： 这个命令也可以显示文件内容，但只能向下滚动。

```bash
more filename
```
3. `tail` 命令：这个命令默认显示文件的最后10行。但是，你可以通过 `-n` 选项来改变这一点。

```bash
tail filename

# 或者指定行数
tail -n 20 filename
```
4. `head` 命令：与 `tail` 相反，这个命令默认显示文件的前10行。

```bash
head filename

# 或者指定行数
head -n 20 filename
```
5. `awk`、`sed`、`grep` 等工具：这些都是强大的文本处理工具，可以用来显示文件内容。

例如，使用`awk`:

```bash
awk '{print}' filename
```

使用`sed`:

```bash
sed -n 'p' filename
```

使用`grep`:

```bash
grep . filename
```
以上就是一些基本命令，你可以根据需要选择使用。