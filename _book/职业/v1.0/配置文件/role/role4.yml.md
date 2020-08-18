# role4.yml

## 职业示例

```yaml
#职业ID
id: role4
#职业名称
name: 羽芒
#使用技能时是否检测当前主手是否含有职业名称的词条 (模糊匹配)
#检测时机始终在当前主手物品完全可使用的情况下进行检测
checdMainItem: false
#转职执行的指令
cmd: []
#职业头像
image: '[local]LegendRpgImage/custom/lr_arrow.png'
#职业介绍
info: 
- '使用武器 : 弓,剑,斧'
- '战斗范围 : 远/近程'
- '定位 : 物理输出,远攻的战士'
- 羽芒拥有精湛的箭术和敏捷的身手,百步穿
- 杨对他们来说仅仅是形容入门菜鸟而已
#转职所需等级
level: 1
#该职业转职所需职业
#可以是多个, 含义为: 只要你是: 职业A 或者 职业B 都可以转职为这个职业
preRoleIdList: 
- role1
- role3
#转职所需道具的ID
#例如:
# props: 
#   propId: 2
#propId -> 道具ID
#2 -> 数量
props: 
  职业转职道具: 2
#职业算法
#攻击算法中
#   内置特殊变量: 
#       #(other_party_is_player)# : 对方是否是玩家
#防御算法中
#   内置特殊变量: 
#       #(damage_value)# : 该玩家即将收到的伤害值
#       #(other_party_is_player)# : 对方是否是玩家
roleAlgorithm: 
  #词条选择池
  switchs: 
    #如果当前主手武器的lore带有"弓"这个字, 则取该算法
    弓: 
      #普通攻击算法
      generalAttackAlgorithm: '#(攻击力)# * 1.5'
      #技能攻击算法
      skillAlgorithm: '#(攻击力)# * 2'
  #词条选择池中没有后的默认选择
  def: 
    #普通攻击算法
    generalAttackAlgorithm: '#(攻击力)# * 1.2'
    #技能攻击算法
    skillAlgorithm: '#(攻击力)# * 1.7'
  #空手算法
  emptyHanded: 
    #普通攻击算法
    generalAttackAlgorithm: '#(攻击力)#'
    #技能攻击算法
    skillAlgorithm: '#(攻击力)# * 1.5'
  #职业防御算法
  defense: '#(damage_value)# - #(防御力)#'
#该职业所拥有的技能
#如果A职业转职为B职业,两个职业相同的技能等级将被保留,且A职业中如果有B职业没有的技能,该技能等级将被清0,并将技能加点返还给玩家
skillIdList: 
- 身轻如燕
- 血液汲取
- 回旋斩
- 影袭
- 炎舞
- 暴击
- 反击风暴
- 雷霆之力
- 吸星大法
- 伤敌一千自损五百
- 寒冰箭
- 毒箭
- 爆炸箭
- 万箭齐发
- 聚能射击
```