

```
if (isset($_GET['file'])) {  
```
是否通过get接收到参数“file”


```
error_reporting(0);  

```
取消报错

```
  if (!strpos($_GET["file"], "flag")) {  

```
如果接受到的file参数内容里包含有“flag”字段，则


```
        include $_GET["file"];  

```
假如在index.php中include了一个文件
那么不管这个文件后缀是什么 这个文件中的内容将会直接出现在index.php中

