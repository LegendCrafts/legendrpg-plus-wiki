# tips.yml

## 提示文件
```yaml
#这是玩家受到伤害时的提示信息
#这里4个局部变量只能这个提示配置文件中"damageInfo","attackedInfo" 两个项能够使用
#   #(player)# : 玩家名称
#   #(other_party_player)# : 对方的名称
#   #(damage_value)# : 伤害值
#   #(damage_type)# : 攻击类型
damageInfo: '你: #(player)# 攻击了：#(other_party_player)# , 造成了：#(damage_value)# 伤害 ,攻击类型：#(damage_type)#'
attackedInfo: '你: #(player)# 受到了来自：#(other_party_player)# , 的：#(damage_value)# 伤害 ,攻击类型：#(damage_type)#'
asynExecute: 正在异步执行中...
commandNotFound: 指令不存在
createSuccess: 创建成功
executeSuccess: 执行成功
idNotFound: ID不存在
idRepeat: ID重复
indexNotFound: 序号不存在
levelDeficiency: 等级不足
notPlaceholder: 该服务暂未提供变量
nullPlayer: 玩家不存在或不在线
paramError: 参数错误
playerDataNotInit: 玩家配置文件未初始化
propNoUse: '§a物品: %s §a的使用条件不足,无法使用'
reloadAllSuccess: 重载所有服务成功
reloadSuccess: 重载成功
removeSuccess: 删除成功
serviceNotFound: 服务不存在
shortageInNumber: 数量不足
```