# restrictionsUse.yml

## 使用限制配置
```yaml
#使用限制配置文件 (可自己新增)
#ID
needRole:
  #使用条件的表达式,判断后,如果是true则可以使用,false,为不能使用
  #变量#(need_role_name)#是在, 下方lore内定义的
  #如果#(need_role_name)#变量的值不是数值, 则需要用""包起来
  condition: '"#(need_role_name)#" == "#(role_name)#"'
  #lore检测
  #定义的变量#(need_role_name)#,为当前装备lore中的值
  #例如: 
  #装备lore: [需要职业]: 剑士
  #玩家当前职业: 魔法师
  #那么: #(need_role_name)#变量的取值为: 剑士
  #      #(role_name)# 魔法师
  # 'condition' 条件解析出来后为: '"剑士" == "魔法师"'
  # 结果为false , 则不能使用
  lore: '[需要职业]: #(need_role_name)#'
needLevel: 
  condition: '#(need_level)# <= #(level)#'
  lore: '[需要等级]: #(need_level)#'
playerBind: 
  condition: '"#(乱写的,这是当前装备上的这个变量值)#" == "#(player)#"'
  lore: '[灵魂绑定] #(乱写的,这是当前装备上的这个变量值)#'
```