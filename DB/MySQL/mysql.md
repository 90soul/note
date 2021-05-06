### 数据库备份和恢复
```
备份数据库DOS命令行
    mysqldump -u 用户名 -p -B 数据库1、2...... > 备份路径/文件名.sql

备份数据库表DOS命令（ps 带上-B是备份数据库）
    mysqldump -u 用户名 -p密码 数据库 tb1、tbn > 备份路径/文件名.sql
    
恢复数据库(登录MySQL命令行再执行)
    source 文件名.sql
```
