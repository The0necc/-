#### mysql5.6与mysql5.7的区别

##### 1.初始化方式变化了

```
mysql_install_db
mysqld --initialize-insecure
```

##### 2.用户安全

```
mysql5.7：
	12伪随机大小写，数字，字符密码
	180默认过期
```

##### 3.密码字段改变了

```
authentication_string
```

