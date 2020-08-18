# hudslot.yml

## 拓展槽图片配置
```yaml
#HUD槽,可自行添加自定义
#ID
11:
  #ID
  id: 11
  #宽
  w: 40
  #高
  h: 40
  #HUD的X轴,支持算法计算
  #注意,算法最终的取值是: 0-1之间,超过该范围,会出现问题
  #玩家当前客户端窗口宽高变量:
  #   #(player_client_window_height)# : 当前玩家客户端高度
  #   #(player_client_window_width)# : 当前玩家客户端宽度
  x: '0.02 + 36 / #(player_client_window_width)# * 4 + 40 / #(player_client_window_width)#'
  #HUD的y轴,支持算法计算
  y: '(#(player_client_window_height)# - 40) / #(player_client_window_height)#'
  #键盘按键ID
  keyId: 
  #是否显示键盘按键文本
  showKeyText: true
  #槽类型
  #可选值: ITEM : 物品槽 | SKILL : 技能槽
  type: ITEM
2: 
  id: 2
  h: 36
  keyId: 48
  showKeyText: true
  type: SKILL
  w: 36
  x: '0.02 + 36 / #(player_client_window_width)#'
  y: '(#(player_client_window_height)# - 36) / #(player_client_window_height)#'
3: 
  id: 3
  h: 36
  keyId: 34
  showKeyText: true
  type: SKILL
  w: 36
  x: '0.02 + 36 / #(player_client_window_width)# * 2'
  y: '(#(player_client_window_height)# - 36) / #(player_client_window_height)#'
4: 
  id: 4
  h: 36
  keyId: 35
  showKeyText: true
  type: SKILL
  w: 36
  x: '0.02 + 36 / #(player_client_window_width)# * 3'
  y: '(#(player_client_window_height)# - 36) / #(player_client_window_height)#'
9: 
  id: 9
  h: 36
  keyId: 47
  showKeyText: true
  type: SKILL
  w: 36
  x: 0.02
  y: '(#(player_client_window_height)# - 36) / #(player_client_window_height)#'
10: 
  id: 10
  h: 40
  keyId: 
  showKeyText: true
  type: ITEM
  w: 40
  x: '0.02 + 36 / #(player_client_window_width)# * 4'
  y: '(#(player_client_window_height)# - 40) / #(player_client_window_height)#'
```