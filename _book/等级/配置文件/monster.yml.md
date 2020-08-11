# monster.yml

## 经验掉落配置

```  yaml
#ID
monster1:
  #ID
  id: monster1
  #怪物名字
  name: 僵尸
  #怪物死亡后掉落的经验
  #可以配置多个,按照概率进行取经验值
  #例:
  # '100:80' -> 指80%的概率给予100经验值
  exp: 
  - 100:80
  - 200:20
  #是否精准匹配
  #如果为true,则需要怪物名称完全等于'name'的值
  #如果为false,模糊匹配,只要怪物名字中,包含'name'即可
  strict: false
```