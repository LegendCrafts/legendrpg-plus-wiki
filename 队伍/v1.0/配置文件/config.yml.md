# config.yml

## 配置文件
```yaml
#队伍人数上限 key->队伍类型 , val->最大人数
teamUpperLimit: 
  COMMON: 4
  ELITE: 10
#默认队伍类型,该类型的取值,在'teamUpperLimit'中定义的
defTeamType: COMMON
#开启或关闭全服的队伍杀怪经验共享功能,关闭后,队长均无法再开启
share: true
#经验共享的半径范围, 以玩家为中心,向x,y,z轴延申该数值,并且聚拢成为一个正方体, 玩家坐标位于正方体正中心,在该正方体范围中的队伍玩家,会获取共享经验
shareRange: 200
#是否关闭队友伤害
turnOffTeammateDamage: true
```