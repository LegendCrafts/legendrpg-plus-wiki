# 指令

## 指令索引

|指令      |权限节点 |说明          |
| -------- | ------ | ------------ |
|/lr role help|lr.role.help|查看当前模块的分类|
|/lr role help os|lr.role.help.os|查看全局配置指令|
|/lr role help player|lr.role.help.player|查看玩家相关指令|
|/lr role help algorithm|lr.role.help.algorithm|查看职业算法配置指令|


## 全局配置指令

|指令      |权限节点 |说明          |
| ------- | -------- | ------ | ------------ |
|/lr role setDefAlgorithm <职业ID>|lr.role.setDefAlgorithm|将该职业设置为初始职业|

## 职业配置指令

|指令      |权限节点 |说明          |
| ------- | -------- | ------ | ------------ |
|/lr role create <职业ID> <职业名称>|lr.role.create|创建职业|
|/lr role list <页码>|lr.role.list|查看职业详细信息|
|/lr role remove <职业ID>|lr.role.remove|删除职业,该指令会强制清除与之职业对应的玩家转职数据|
|/lr role setName <职业ID> <新职业名>|lr.role.setName|重新设置某职业的职业名称|
|/lr role setIsChecd <职业ID> (true,false)|lr.role.setIsChecd|设置使用技能时是否检测当前主手是否含有职业名称的词条|
|/lr role setLevel <职业ID> <等级值>|lr.role.setLevel|给某职业设置转职所需等级|
|/lr role setImage <职业ID> <图片路径>|lr.role.setImage|设置职业头像路径|
|/lr role addPreRoleId <职业ID> <前置职业ID>|lr.role.addPreRoleId|添加该职业转职所需的前置职业|
|/lr role remPreRoleId <职业ID> <前置职业ID>|lr.role.create|减少该职业转职所需的前置职业|
|/lr role addSkill <职业ID> <技能ID>|lr.role.addSkill|给某职业新增一个技能|
|/lr role remSkill <职业ID> <技能ID>|lr.role.remSkill|给某职业减少一个技能|
|/lr role addProp <职业ID> <道具ID> <数量>|lr.role.addProp|给某职业新增一个转职所需道具,并且给定数量(最大64)|
|/lr role remProp <职业ID> <道具ID>|lr.role.remProp|给某职业减少一个职业所需道具|
|/lr role addCmd <职业ID> <指令>|lr.role.addCmd|给某职业新增一条转职执行指令|
|/lr role remCmd <职业ID> <位置序号>|lr.role.remCmd|给某职业减少一条转职执行指令|
|/lr role addInfo <职业ID> <职业介绍>|lr.role.addInfo|给某职业新增一条职业介绍|
|/lr role remInfo <职业ID> <位置序号>|lr.role.remInfo|给某职业减少一条职业介绍|

## 玩家相关指令

|指令      |权限节点 |说明          |
| ------- | -------- | ------ | ------------ |
|/lr role info <玩家名>|lr.role.info|查看指定玩家的职业信息|
|/lr role upRole <玩家名> <职业ID>|lr.role.upRole|将指定玩家转职成指定职业|
|/lr role setPlayerDefRole <玩家名>|lr.role.setPlayerDefRole|将指定玩家设置为默认职业|

## 职业算法配置指令

|指令      |权限节点 |说明          |
| ------- | -------- | ------ | ------------ |
|/lr role addAlgorithmSwitch <职业ID> <检测的词条> <普攻算法> <技能算法>|lr.role.addAlgorithmSwitch|给某职业增加一条主手lore检测的伤害算法|
|/lr role remAlgorithmSwitch <职业ID> <位置序号>|lr.role.remAlgorithmSwitch|给某职业减少一条主手lore检测的伤害算法|
|/lr role setAlgorithmDef <职业ID> <普攻算法> <技能算法>|lr.role.setAlgorithmDef|设置手持物品时候的默认算法|
|/lr role setAlgorithmEmptyHanded <职业ID> <普攻算法> <技能算法>|lr.role.setAlgorithmEmptyHanded|给某职业设置空手算法|
|/lr role setDefense <职业ID> <算法>|lr.role.setDefense|给某职业设置防御算法|