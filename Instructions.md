## windows网络命令

### ip与计算机名

nbtstat -a ip， 通过ip查看计算机名

ping -a ip，ping电脑ip显示用户域信息

## sql语句

join连接时除了参与join连接的字段外，其余跟在join连接条件后的条件没用

### Sql server



### Oracle

查询排序后的前n条数据

select * from (select * from tb order by tb.field desc) where rownum<n;

