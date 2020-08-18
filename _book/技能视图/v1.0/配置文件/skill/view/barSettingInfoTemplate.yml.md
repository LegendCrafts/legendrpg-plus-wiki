# barSettingInfoTemplate.yml

## 按键展示模板
```yaml
#技能案件设置GUI界面展示模板
#可用内置变量
# #(skill_name)# -> 技能名称
# #(skill_level)# -> 技能等级
# #(skill_info)# -> 技能介绍,可能有多行,注意放置的位置
# #(skill_key_name)# -> 快捷键
info: 
- '技能名称: #(skill_name)#'
- '快捷键: #(skill_key_name)#'
- '技能描述: '
- '  #(skill_info)#'
```