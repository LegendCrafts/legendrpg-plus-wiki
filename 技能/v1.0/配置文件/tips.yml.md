# tips.yml

## 提示信息
```yaml
#这里2个局部变量只能这个提示配置文件中"mpInsufficient" 这个项能够使用
#   #(mp)# : 当前蓝量
#   #(need_mp)# : 所需蓝量
mpInsufficient: '蓝量不足,当前蓝量: #(mp)#,所需蓝量: #(need_mp)#'
NotLearningSkill: 未学习该技能
pointInsufficient: 技能点数不足
#这里1个局部变量只能这个提示配置文件中"skillCooling" 这个项能够使用
#   #(cooling)# : 还需冷却时间
skillCooling: '技能冷却中还需 #(cooling)# 毫秒'
skillMax: 技能已满级
skillNotFund: 技能不存在
```