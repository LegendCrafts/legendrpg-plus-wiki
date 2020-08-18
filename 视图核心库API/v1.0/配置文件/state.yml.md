# state.yml

## HUD状态栏配置
```yaml
#这个配置文件中的xy轴均支持算法
#注意,算法最终的取值是: 0-1之间,超过该范围,会出现问题
#玩家当前客户端窗口宽高变量:
#   #(player_client_window_height)# : 当前玩家客户端高度
#   #(player_client_window_width)# : 当前玩家客户端宽度
#
#最大行数
row: 2
#最大列数
column: 6
#状态栏刷新间隔(毫秒)
hudResetTime: 500
#如果当前最大只有一页的时候，是否展示分页按钮
usePage: true
#分页按钮的HUD配置
pageBtn: 
  #左翻页按钮图片路径
  leftPageUrl: '[local]LegendRpgImage/viewApi/invLeftBtn.png'
  #左翻页按钮图片按下路径
  leftPageClikeUrl: '[local]LegendRpgImage/viewApi/invLeftSelectedBtn.png'
  #左翻页按钮宽
  leftPageW: 5
  #左翻页按钮高
  leftPageH: 10
  #左翻页按钮X轴
  leftPageX: 0.51
  #左翻页按钮Y轴
  leftPageY: 0.76 + 17 * 2 /#(player_client_window_height)#
  #右翻页按钮图片路径
  rightPageUrl: '[local]LegendRpgImage/viewApi/invRightBtn.png'
  #右翻页按钮图片按下路径
  rightPageClikeUrl: '[local]LegendRpgImage/viewApi/invRightSelectedBtn.png'
  #右翻页按钮宽
  rightPageW: 5
  #右翻页按钮高
  rightPageH: 10
  #右翻页按钮X轴
  rightPageX: '0.51 + 100 / #(player_client_window_width)# - 0.03'
  #右翻页按钮Y轴
  rightPageY: 0.76 + 17 * 2 /#(player_client_window_height)#
#主背景HUD配置
mainBackground: 
  #主背景图片URL
  mainBackgroundUrl: '[local]LegendRpgImage/viewApi/translucent.png'
  #状态图标背景的宽度
  mainBackgroundW: 100
  #状态图标背景的高度
  mainBackgroundH: 50
  #状态图标背景的X轴
  mainBackgroundX: 0.5
  #状态图标背景的Y轴
  mainBackgroundY: 0.75
#状态图标背景HUD配置
stateIocBackGround: 
  #状态图标的背景的图片地址
  url: '[local]LegendRpgImage/viewApi/skillBar.png'
  #状态图标背景的宽度
  w: 10
  #状态图标背景的高度
  h: 10
  #各个状态图标背景的左右间距
  aboutSpacing: 5
  #各个状态图标背景的上下间距
  upAndDownSpacing: 5
  #状态图标背景与状态图标的上下间距
  iocAboutSpacing: 2
  #状态图标背景与状态图标的左右间距
  iocUpAndDownSpacing: 2
```