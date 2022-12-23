

## 配置文件注释


> [!WARNING]
> [注] 未文字说明的配置项 请勿修改 !
> 创建岛屿后 尽量不要修改配置文件 除非你知道其代表着什么

> plugins \ SkyBlock \ config.json

```javascript
    "Admin": [] // 岛屿管理员
```

```javascript
    "Menu": 1 // 默认菜单是否开启
```

```javascript
    "POS_MARK": {
        "mark": 0,
        "start_x": 0, // 第一个岛屿起始坐标 X
        "start_z": 0, // 第一个岛屿起始坐标 Z
        "island_height": 64, // 岛屿生成高度
        "protection_range": 100, // 岛屿保护范围
        "distance_between_islands": 800, // 岛屿之间的间隔
        "data": { 
            // .. 省略 
        }
    }
```

```javascript
    "isLand": {
        "default_language": "zh_CN",
        "max_team_size": 4,
        "max_wrap_num": 3, // 最大传送点数量
        "level": {
            "interval": 10, // 岛屿查询间隔 (分钟)
            "delay": 80 // 已弃用
        },
        "reset": {
            "reset_limit": 3,
            "kicked_keep_inventory": false
        },
        "file": [ // 岛屿模板文件
            {
                "type": "sky1", // 岛屿模板文件名 (无需后缀) 可自行使用结构方块导出
                "name": "空岛", // 游戏内显示名
                 // 偏移值 玩家的出生点坐标为  长/2  高   宽/2
                "data": {
                    "length": 9,
                    "width": 9,
                    "height": 8
                }
            }
        ],
        "invite": {
            "max": 3 //  岛屿成员最大数量
        }
    }
```

```javascript
// 玩家删除岛屿后会被传送的位置
    "SPAWN": {
        "x": 0,
        "y": 64,
        "z": 0
    }
```

```javascript
    "Dimension": {
        "The_Nether": false, // 是否开放地狱
        "The_End": false // 是否开放末地
    }
```
