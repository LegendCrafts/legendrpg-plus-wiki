# formula.yml

## 升级所需经验值的算法配置

```  yaml
#ID
stage2: 
  #ID
  id: stage2
  #升级所需经验值的算法
  expression: 30 * (#(level)#*#(level)#*#(level)#+5*#(level)#)-80
  #等级在这个范围区间,则使用该算法
  #适用的等级(起点)
  levelEnd: 60
  #适用的等级(终点)
  levelStart: 21
stage1: 
  id: stage1
  expression: 28 * (#(level)#*#(level)#*#(level)#+5*#(level)#)-80
  levelEnd: 20
  levelStart: 1
```