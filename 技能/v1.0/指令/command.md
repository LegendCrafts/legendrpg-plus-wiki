# 指令

## 指令索引

|指令      |权限节点 |说明          |
| -------- | ------ | ------------ |
|/lr sk help|lr.sk.help|查看当前模块的分类|
|/lr sk set help|lr.sk.set.help|查看技能配置指令帮助|
|/lr sk p help|lr.sk.p.help|查看玩家技能指令帮助|


## 技能配置指令帮助

|指令      |权限节点 |说明          |
| ------- | -------- | ------ | ------------ |
|/lr sk create <技能ID> <技能名称>|lr.skill.create|创建技能|
|/lr sk remove <技能ID>|lr.skill.remove|删除一个技能|
|/lr sk list <页码>|lr.skill.list|根据页码查询技能列表|
|/lr sk info <技能ID>|lr.skill.info|查看技能配置详情|
|/lr sk setName <技能ID> <技能名称>|lr.skill.set|设置技能技能名称|
|/lr sk setImg <技能ID> <图片路径>|lr.skill.set|设置技能图标|
|/lr sk setCooling <技能ID> <算法>|lr.skill.set|设置该技能的技能冷却算法|
|/lr sk setMp <技能ID> <算法>|lr.skill.set|设置该技能的技能耗蓝算法|
|/lr sk setPoint <技能ID> <算法>|lr.skill.set|设置技能升级消耗点数算法|
|/lr sk setMaxLevel <技能ID> <等级>|lr.skill.set|设置技能封顶等级|
|/lr sk setLvAdded <技能ID> <算法>|lr.skill.set|设置技能的等级附加值算法|
|/lr sk isDef <技能ID> \<true,false\>|lr.skill.set|是否默认习得|
|/lr sk asyn <技能ID> <true,false>|lr.skill.set|设置技能是否异步执行|
|/lr sk passive <技能ID> <true,false>|lr.skill.set|设置是否作为被动技能展示|
|/lr sk addInfo <技能ID> <描述>|lr.skill.set|给该技能添加一条描述|
|/lr sk remInfo <技能ID> <序号>|lr.skill.set|根据序号删除一条描述|
|/lr sk addUpCmd <技能ID> <指令>|lr.skill.set|给该技能添加一条升级执行指令|
|/lr sk remUpCmd <技能ID> <序号>|lr.skill.set|根据序号删除一条升级执行指令|
|/lr sk addUpMaxCmd <技能ID> <指令>|lr.skill.set|给该技能添加一条满级执行指令|
|/lr sk remUpMaxCmd <技能ID> <序号>|lr.skill.set|根据序号删除一条满级执行指令|
|/lr sk addEvent <技能ID> <事件名>|lr.skill.set|给该技能添加一个触发事件|
|/lr sk remEvent <技能ID> <事件名>|lr.skill.set|给该技能删除一个触发事件|


## 玩家技能指令帮助

|指令      |权限节点 |说明          |
| ------- | -------- | ------ | ------------ |
|/lr sk p info <玩家名>|lr.sk.p.info|获取玩家相关信息|
|/lr sk p runSk <玩家名> <技能ID>|lr.skill.run|让玩家释放技能(无视蓝量和冷却)|
|/lr sk p useSk <玩家名> <技能ID>|lr.skill.use|让玩家释放技能|
|/lr sk p opupSklv <玩家名> <技能ID> <数值>|lr.sk.p.opupSklv|给玩家技能提升指定等级(OP执行)|
|/lr sk p upSklv <玩家名> <技能ID> <数值>|lr.sk.p.upSklv|给玩家技能提升指定等级(玩家执行)|
|/lr sk p downSklv <玩家名> <技能ID> <数值>|lr.sk.p.downSklv|给玩家技能减少指定等级|
|/lr sk p addMp <玩家名> <数值>|lr.sk.p.addMp|给玩家恢复指定数值的蓝量|
|/lr sk p remMp <玩家名> <数值>|lr.sk.p.remMp|给玩家扣除指定数值的蓝量|
|/lr sk p addPoint <玩家名> <数值>|lr.sk.p.addPoint|增加玩家技能点数|
|/lr sk p remPoint <玩家名> <数值>|lr.sk.p.remPoint|减少玩家技能点数|
|/lr sk p reset <玩家名> <是否返还点数> <技能ID,不填写则默认全部>|lr.sk.player.reset|技能等级洗点|