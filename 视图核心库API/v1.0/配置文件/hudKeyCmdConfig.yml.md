# hudKeyCmdConfig.yml

## 自定义HUD快捷键配置
```yaml
#ID
队伍菜单: 
  #ID
  id: 队伍菜单
  #快捷键按下后执行的指令(玩家身份执行)
  cmd: 
  - /lr view team open
  #宽
  w: 25
  #高
  h: 25
  #HUD的X轴,支持算法计算
  #注意,算法最终的取值是: 0-1之间,超过该范围,会出现问题
  #玩家当前客户端窗口宽高变量:
  #   #(player_client_window_height)# : 当前玩家客户端高度
  #   #(player_client_window_width)# : 当前玩家客户端宽度
  x: '(#(player_client_window_width)# - 25)  / #(player_client_window_width)#'
  #HUD的y轴,支持算法计算
  y: '0.3 + 25 / #(player_client_window_height)#'
  #HUD图片
  image: '[local]LegendRpgImage/custom/队伍HUD.png'
  #键盘按键ID,参考VV按键ID
  keyCode: 20
  #HUD的权重,该值谁大,谁在上方
  z: 1
个人: 
  id: 个人
  cmd: 
  - /lr view atr openPlayerInfo
  h: 25
  image: '[local]LegendRpgImage/custom/个人HUD.png'
  keyCode: 25
  w: 25
  x: '(#(player_client_window_width)# - 25)  / #(player_client_window_width)#'
  y: 0.3
  z: 1
RPG背包: 
  id: RPG背包
  cmd: 
  - /lr view inv open
  h: 25
  image: '[local]LegendRpgImage/custom/背包HUD.png'
  keyCode: 23
  w: 25
  x: '(#(player_client_window_width)# - 25)  / #(player_client_window_width)#'
  y: '0.3 + 25* 2 / #(player_client_window_height)#'
  z: 1
```
