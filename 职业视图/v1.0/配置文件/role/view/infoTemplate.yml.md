# infoTemplate.yml

## 转职页面模板
```yaml
#转职界面的展示模板
#可用内置变量
# #(current_role_name)# -> 当前展示的职业名称
# #(role_info)# -> 职业介绍列表,可能有多行,注意放置的位置
# #(role_need_level)# -> 所需等级
# #(role_need_prop)# -> 所需道具列表,可能有多行,注意放置的位置
info: 
- '职业 : #(current_role_name)#'
- '#(role_info)#'
- ""
- '需要等级: #(role_need_level)# 级'
- '需要道具: '
- '  #(role_need_prop)#'
```