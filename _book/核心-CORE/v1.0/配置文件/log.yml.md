# log.yml

## 日志文件
```yaml
#日志级别, 可选值: DEBUG , ERROR , WARN , INFO
#日志级别的权重: DEBUG > WARN > ERROR > INFO , 如设置为WARN , 则显示WARN及一下级别的日志信息, 不会显示DEBUG级别的信息
logLevel: DEBUG
#模板日志输出
#可选值: 
#   #SERVICE# : 服务名
#   #LOG_LEVEL# : 日志级别
#   #CLASS_NAME# : 类信息
#   #DATE_TIME# : 日志产生日期
#   #INFO# : 错误信息
templateInfo: '[#SERVICE#][#LOG_LEVEL#][#CLASS_NAME#][#DATE_TIME#]: #INFO#'
```