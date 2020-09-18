# 指令

## 指令索引

|指令      |权限节点 |说明          |
| -------- | ------ | ------------ |
|/lr prop help|lr.prop.help|查看当前模块的分类|
|/lr prop help os|lr.prop.help.os|查看全局配置指令|
|/lr prop help setting|lr.prop.help.setting|查看道具配置指令|
|/lr prop help lore|lr.prop.help.lore|查看lore指令|


## 全局配置指令

|指令      |权限节点 |说明          |
| ------- | -------- | ------ | ------------ |
|/lr prop updateProp|lr.prop.updateProp|将所有玩家的道具进行更新|

## 道具配置指令

|指令      |权限节点 |说明          |
| ------- | -------- | ------ | ------------ |
|/lr prop create <道具ID>|lr.prop.create|使用手上物品创建道具|
|/lr prop list <页码>|lr.prop.list|查看道具列表|
|/lr prop info <道具ID>|lr.prop.info|查看道具详细信息|
|/lr prop get <玩家名> <道具ID> <数量>|lr.prop.get|根据ID将指定数量的道具给予指定玩家|
|/lr prop remove <道具ID>|lr.prop.remove|删除道具|
|/lr prop setConsume <道具ID> (true|false)|lr.prop.setConsume|设置物品是否为消耗物品|
|/lr prop setSquat <道具ID> (true|false)|lr.prop.setSquat|设置物品是否只能蹲下才能使用|
|/lr prop setAction <道具ID> (left,right)|lr.prop.setAction|设置物品的点击类型,取值: left(左) | right(右)|
|/lr prop setCooling <道具ID> <毫秒值>|lr.prop.setCooling|设置使用冷却时间|
|/lr prop setImageUrl <道具ID> <图片地址>|lr.prop.setImageUrl|设置这个道具的图片地址|
|/lr prop addCmd <道具ID> <指令>|lr.prop.addCmd|为这个物品增加使用的指令|
|/lr prop remCmd <道具ID> <序号>|lr.prop.remCmd|为这个物品减少使用指令|


## LORE相关的指令

|指令      |权限节点 |说明          |
| ------- | -------- | ------ | ------------ |
|/lr prop lore name <新名称>|lr.prop.lore.name|为手中的道具修改名称|
|/lr prop lore addLore <文本LORE>|lr.prop.lore.addLore|为手中的道具的lore的末尾增加一条Lore|
|/lr prop lore addLore <文本LORE> <行数>|lr.prop.lore.addLore|为手中的道具的lore的第几行插入一条Lore|
|/lr prop lore setLore <文本LORE> <行数>|lr.prop.lore.setLore|为手中的道具修改一条lore|
|/lr prop lore remLore <行数>|lr.prop.lore.remLore|为手中的道具减少一条Lore|