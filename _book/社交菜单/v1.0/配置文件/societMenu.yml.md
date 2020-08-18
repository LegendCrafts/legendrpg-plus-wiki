# societMenu.yml

## 社交菜单

```yaml
#菜单ID
1: 
  #菜单ID  
  id: 1
  #菜单名称
  name: 查看信息
  #点击菜单后执行的指令(玩家身份执行)
  cmds: 
  - 'lr view atr openPlayerInfo #(player2)#'
2: 
  id: 2
  name: 邀请加入队伍
  cmds: 
  - 'lr team invite #(player2)#'
3: 
  id: 3
  name: 加入他的队伍
  cmds: 
  - 'lr team apply #(player2)#'
4: 
  id: 4
  name: 让服务器说句hi
  cmds: 
  - op:say 我是#(player)#,准备跟#(player2)#进行交互
5: 
  id: 5
  name: 让服务器说句hi
  cmds: 
6: 
  id: 6
  name: 让服务器说句hi
  cmds: 
7: 
  id: 7
  name: 让服务器说句hi
  cmds: 
```