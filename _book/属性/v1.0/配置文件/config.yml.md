# config.yml

## 全局配置文件

```yaml
#玩家的默认攻击算式
algorithm:
  #普通攻击算法(手持物品,或者空手)
  #看到这个配置,你可能会有疑惑,这个'?'问号, 是什么意思
  #这里使用到了 "三元运算符表达式", 在这里我简单教一下
  #三元表达式的统一格式为: '判断内容 ? 返回A : 返回B'
  #判断内容的最终返回值必须是布尔值(true|false). 如果为是（ture）则得到结果a 如果为否（f）则得到结果为b
  #如果还是不清楚,请打开浏览器,百度搜索: 三元表达式教学视频 , 当然不学这个也没关系, #我们的算法配置文件,只是支持三元表达式而  已, 不学的话,不使用三元表达式即可
  #
  #有一定基础后,我们可以看到下方 '#(other_party_is_player)# ? 5 : 10'
  # 条件: #(other_party_is_player)# , 这是一个变量, 程序将变量值返回后, 这个变量会返回 true|false
  # #(other_party_is_player)# 变量含义为: 攻击者是否是玩家
  #
  #内置特殊变量: 
  #    #(other_party_is_player)# : 对方是否是玩家
  generalAttackAlgorithm: '#(other_party_is_player)# ? 5 : 10'
  #技能攻击算法
  skillAlgorithm: '#(other_party_is_player)# ? 2 : 5'
#buff持久化阈值(buff时长超出才会保存到本地，否则存在缓存) 单位:秒
buffThreshold: 1800
#玩家的默认防御算法
#该算法计算出的最后值,即为玩家最终受到的伤害
#
#内置特殊变量: 
#   #(damage_value)# : 该玩家即将收到的伤害值
#   #(other_party_is_player)# : 对方是否是玩家
defense: '#(other_party_is_player)# ? #(damage_value)# - 1 : #(damage_value)# - 2'
#默认血量算法
#这里取值的变量, #(生命值)# ,是从自定义属性中定义的属性
hpFormula: '#(生命值)#'
#默认血量回复算法
hpReplyFormula: '#(血量恢复)#'
#默认移动速度算法
moveFormula: '#(移动速度)#'
#玩家血条压缩率,20代表一排红心,40代表两排红心
playerHealthScale: 40.0
```

