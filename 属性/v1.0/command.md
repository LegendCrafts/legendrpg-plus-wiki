# 指令

## 指令索引

|指令      |权限节点 |说明          |
| -------- | ------ | ------------ |
|/lr atr help|lr.atr.help|查看当前模块的分类|
|/lr atr set help|lr.atr.set.help|查看属性配置指令帮助|
|/lr atr p help|lr.atr.p.help|查看玩家技能指令帮助|


## 属性配置指令帮助

|指令      |权限节点 |说明          |
| ------- | -------- | ------ | ------------ |
|/lr atr list <页码>|lr.atr.list|分页查看已创建的属性列表|
|/lr atr info <属性ID>|lr.atr.info|根据ID查看属性详情|
|/lr atr create <属性ID> <属性名>|lr.atr.create|创建一个属性|
|/lr atr setName <属性ID> <属性名称>|lr.atr.setName|设置属性名称|
|/lr atr setAdditional <属性ID> <附加值>|lr.atr.setAdditional|设置属性附加值|
|/lr atr setLore <属性ID> <文本Lore>>|lr.atr.setLore|设置增益检测词条|
|/lr atr setRemLore <属性ID> <文本Lore>|lr.atr.setRemLore|设置减益检测词条|
|/lr atr setMaxLevel <属性ID> <数值>|lr.atr.setMaxLevel|设置属性加点的等级上限|
|/lr atr setUpAtr <属性ID> <数值>|lr.atr.setUpAtr|设置属性成长值|
|/lr atr setPoint <属性ID> <数值>|lr.atr.setPoint|设置升级所需点数|
|/lr atr setImg <属性ID> <图片路径>|lr.atr.setShow|设置属性图片路径|
|/lr atr setSort <属性ID> <数值>|lr.atr.setSort|设置属性排序|
|/lr atr setLvAdded <属性ID> <数值>|lr.atr.setLvAdded|设置属性等级附加值算法|
|/lr atr setEnable <属性ID> (true,false)|lr.atr.setEnable|设置属性是否启用|
|/lr atr setUpgrade <属性ID> (true,false)|lr.atr.setUpgrade|设置属性是否可加点|
|/lr atr setRate <属性ID> (true,false)|lr.atr.setRate|设置属性是否以百分比显示|
|/lr atr addUpCmd <属性ID> <指令>|lr.atr.addUpCmd|增加一条属性升级执行指令|
|/lr atr remUpCmd <属性ID> <序号>|lr.atr.remUpCmd|根据指令序号删除一条指令|
|/lr atr addUpMaxCmd <属性ID> <指令>|lr.atr.addUpMaxCmd|增加一条属性升级到满级时的执行指令|
|/lr atr remUpMaxCmd <属性ID> <序号>|lr.atr.remUpMaxCmd|根据指令序号删除一条满级执行指令|
|//lr atr addInfo <属性ID> <属性介绍>|lr.atr.addInfo|增加一条属性描述|
|/lr atr remInfo <属性ID> <序号>|lr.atr.remInfo|根据指令序号删除一条属性描述|
|/lr atr checkAtr <属性ID>|lr.atr.checkAtr|检测某条属性是否为配置必填项完整并且可用的|


## 玩家技能指令帮助

|指令      |权限节点 |说明          |
| ------- | -------- | ------ | ------------ |
|/lr atr p info <玩家名>|lr.atr.p.info|查看某玩家的所有属性|
|/lr atr p addAtr <玩家名> <属性ID> <数值>|lr.atr.p.addAtr|为一位玩家的增加指定数值的属性值|
|/lr atr p addBuff <玩家名> <属性ID> <数值> <秒值>|lr.atr.p.addBuff|为一位玩家的添加指定属性的Buff|
|/lr atr p upAtrLv <玩家名> <属性ID> <数值>|lr.atr.p.upAtrLv"|升级一位玩家的属性|
|/lr atr p remAtrLv <玩家名> <属性ID> <数值>|lr.atr.p.remAtrLv|降级一位玩家的属性|
|/lr atr p removeBuff <玩家名>|lr.atr.p.removeBuff|清除一位玩家身上的所有BUFF|
|/lr atr p cleanDownBuff <玩家名>|lr.atr.p.cleanDownBuff|清除一位玩家身上的所有减益BUFF|
|/lr atr p cleanUpBuff <玩家名>|lr.atr.p.cleanUpBuff|清除一位玩家身上的所有的增益BUFF|
|/lr atr p addPoint <玩家名> <数值>|lr.atr.p.addPoint|增加玩家点数|
|/lr atr p remPoint <玩家名> <数值>|lr.atr.p.remPoint|减少玩家点数|
|/lr atr p reset <玩家名> <是否返还属性点数true,false> <属性ID,不填写则重置全部>|lr.atr.p.reset|属性等级洗点|