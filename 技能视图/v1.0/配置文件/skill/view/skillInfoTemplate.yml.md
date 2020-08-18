# skillInfoTemplate.yml

## 展示模板
```yaml
#展示模板
#可用内置变量
# #(skill_point)# -> 剩余技能加点
# #(skill_name)# -> 技能名称
# #(skill_level)# -> 技能等级
# #(skill_max_level)# -> 技能最大等级
# #(skill_info)# -> 技能介绍,可能有多行,注意放置的位置
# #(skill_level)# -> 技能等级
info: 
- '               #(skill_name)##c(#(skill_max_level)#!=-1 && #(skill_level)#>=#(skill_max_level)# ? ''(满级)''
  : '''')c#'
- '技能描述: '
- '  #(skill_info)#'
- ""
- '剩余技能点: #(skill_point)#'
```