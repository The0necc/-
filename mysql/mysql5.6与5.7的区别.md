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

##### 4.only_full_group_by

```
在使用group by的时候。select后面出现的列，必须在group by 后面出现，或者是用聚合函数包裹。
防止出现一对多的情况出现，得到我们不想要的值。
```

