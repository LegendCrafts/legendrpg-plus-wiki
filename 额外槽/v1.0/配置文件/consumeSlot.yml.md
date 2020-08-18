# consumeSlot.yml

## 消耗槽配置

```yaml
#消耗品槽
#唯一ID
slot2: 
  #ID
  id: slot2
  #VV核心库API模块中配置的HUDSlotID值
  #该配置将这个背包内的快捷槽与HUD上的快捷栏进行绑定
  hudSlotId: 11
  #槽内图片
  image: '[local]LegendRpgImage/custom/M键_消耗品槽内图片.png'
  #键盘按键码, 与VV的按键码一致
  key: 50
  #排序
  sort: 2
slot1: 
  id: slot1
  hudSlotId: 10
  image: '[local]LegendRpgImage/custom/N键_消耗品槽内图片.png'
  key: 49
  sort: 1
```