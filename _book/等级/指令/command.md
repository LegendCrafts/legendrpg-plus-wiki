# 指令

## 指令索引

|指令      |权限节点 |说明          |
| -------- | ------ | ------------ |
|/lr level help|lr.level.help|查看当前模块的分类|
|/lr level help os|lr.level.help.os|查看全局配置相关指令|
|/lr level help p|lr.level.help.p|查看玩家相关指令|
|/lr level help multiple|lr.level.help.multiple|查看倍数经验相关指令|

## 全局配置指令

|指令      |权限节点 |说明          |
| ------- | -------- | ------ | ------------ |
|/lr level setMaxLevel <数值>|lr.level.setMaxLevel|设置服务器最大等级|

## 玩家相关指令

|指令      |权限节点 |说明          |
| ------- | -------- | ------ | ------------ |
|/lr level addLevel <玩家名称> <数值>|lr.level.addLevel|给指定玩家增加指定数值的等级|
|/lr level dropLevel <玩家名称> <数值> |lr.level.dropLevel|给指定玩家降低指定数值的等级|
|/lr level addExp <玩家名称> <数值>|lr.level.addExp|给指定玩家增加指定数值的经验值|
|/lr level dropExp <玩家名称> <数值>|lr.level.dropExp|给指定玩家降低指定数值的经验值|
|/lr level info <玩家名称>|lr.level.othersInfo|查看指定玩家等级信息|
|/lr level info|lr.level.info|查看自己等级信息|

## 倍数经验指令

|指令      |权限节点 |说明          |
| ------- | -------- | ------ | ------------ |
|/lr level multiple <玩家名称> <倍值> <秒值>|lr.level.multiple|给某位玩家开启指定时间指定倍值的杀怪经验|
|/lr level multipleAll <倍值> <秒值> <叠加类型>|lr.level.multipleAll|开启全服指定时间指定倍值的杀怪经验,叠加类型: `PLUS(加算) | RIDE(乘算) | COVER(覆盖) | NONE(不影响玩家)`|
|/lr level stopMultipleAll|lr.level.stopMultipleAll|停止全服加倍经验|