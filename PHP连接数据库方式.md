## php连接数据库的几种方式

**1.**

注意:mysql_connectPHP7.0之后就被废弃了,可以使用mysqli_connect替代

$link = @mysqli_connect("localhost","root","root","wangjing")