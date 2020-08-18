# mysql.yml

## 数据库文件
```yaml
#库名称
dbName: legendrpg
#连接池起始连接数量
initialSize: 50
#连接池最大连接数量(如果未设置数据库最大并发连接数,请勿设置超过100)
maxActive: 100
#用户名
username: root
#密码
password: root
#数据库IP:端口
url: 127.0.0.1:3306
#是否使用数据库,如为false,则启用yml本地存储,默认为false
useSql: false
```