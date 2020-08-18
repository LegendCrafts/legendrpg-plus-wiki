# config.yml

## 配置文件
```yaml
#HUD刷新时间间隔 毫秒值
hudResetTime: 500
#队伍HUD列表每页展示条目数
pageNum: 4
#玩家经验值变量
papiExp: '%lr_exp%'
#玩家当前等级到下个等级共需要多少经验
papiMaxExp: '%lr_next_sum_exp%'
#玩家血量变量
papiHp: '%lr_player_health%'
#玩家最大血量变量
papiMaxHp: '%lr_player_max_health%'
#玩家等级变量
papiLevel: '%lr_level%'
#玩家最大蓝量变量
papiMaxMp: '%lr_max_mp%'
#玩家蓝量变量
papiMp: '%lr_mp%'
#HUD的X轴,支持算法计算
#注意,算法最终的取值是: 0-1之间,超过该范围,会出现问题
#玩家当前客户端窗口宽高变量:
#   #(player_client_window_height)# : 当前玩家客户端高度
#   #(player_client_window_width)# : 当前玩家客户端宽度
teamHudX: '0'
#HUD的X轴,支持算法计算
teamHudY: '0.3'
```