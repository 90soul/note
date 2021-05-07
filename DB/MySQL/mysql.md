### 数据库备份和恢复
```
备份数据库DOS命令行
    mysqldump -u 用户名 -p -B 数据库1、2...... > 备份路径/文件名.sql

备份数据库表DOS命令（ps 带上-B是备份数据库）
    mysqldump -u 用户名 -p密码 数据库 tb1、tbn > 备份路径/文件名.sql
    
恢复数据库(登录MySQL命令行再执行)
    source 文件名.sql
```
### 函数
```
统计函数 - count
    count 返回行的总数
    SELECT count(*) | count(列名) FROM table_name [WHERE where_definition]
    count(*) 和count(列名)的区别
        count(*)：返回满足条件的记录行数；
        count(列名)：统计满足条件的某列有多少个，并且会排除为null的情况
```
