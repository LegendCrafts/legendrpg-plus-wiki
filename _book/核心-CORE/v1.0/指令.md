# 指令

## 指令索引

|指令      |权限节点 |说明          |
| -------- | ------ | ------------ |
|/lr|lr.help.use|查看所有附属的指令菜单|
|/lr core help|lr.core.help|查看CORE的所有指令|

## CORE的所有指令

|指令      |权限节点 |说明          |
| ------- | -------- | ------ | ------------ |
|/lr core reload <附属ID>|lr.core.reload|重载附属,指定重载的附属,也可以不传入最后一个参数,即视为重载所有附属|
|/lr core restorePlayerData <附属ID> <玩家名称>|lr.core.restorePlayerData|还原各附属指定的玩家数据,还原各个附属的玩家数据,附属ID可以不传入,即视为还原所有附属的这位玩家的数据|
|/lr core restoreAllPlayerData <附属ID>|lr.core.restoreAllPlayerData|还原各附属所有的玩家数据,还原各个附属的所有玩家数据,附属ID可以不传入,即视为还原所有附属的玩家数据|
|/lr core showPlaceholders|lr.core.showPlaceholders|查看各个附属提供的变量|