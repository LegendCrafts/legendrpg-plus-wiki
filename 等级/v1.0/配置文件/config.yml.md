# config.yml

## 全局配置文件

```  yaml
#升级所需经验算法
#如果当前等级值,不在formula.yml配置文件中所配置,则取该配置文件的defFormula值
defFormula: 30 * (level*level*level+5*level)-80
#最高等级
maxLevel: 60
#升级执行的指令
upCmd: 
- '/lr atr p addPoint #(player)# 5'
- '/lr sk p addPoint #(player)# 5'
#满级时执行的指令,满级时,"upCmd"也会执行
upMaxCmd: 
- '/say #(player)# 满级了'
```