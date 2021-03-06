### 团队职能集合

|目标系统|执行系统|沟通系统|职位系统|激励系统|知识管理系统|培训系统|
|----|----|----|----|----|----|----|
|      |       |信息收集|质量意识(扩展)|积极主动|诚信正直|诚信正直|
|      |       |学习领悟|主动汇报(扩展)|沟通能力|敬业精神|诚信正直|
|      |       |       |            |      |团队合作|诚信正直|
|      |       |       |            |       |责任心|诚信正直|

### 团队职能-标准雷达图

```chart
{
    "title": {
        "text": "团队职能模型"
    },
    "tooltip": {},
    "color":["#D40200","#91C7AE"],
    "legend": {
        "data": ["最低团队职能达标", "最高团队职能达标"]
    },
    "radar": {
        "indicator": [
           { "name": "目标系统", "max": 10},
           { "name": "执行系统", "max": 10},
           { "name": "沟通系统", "max": 10},
           { "name": "职位系统", "max": 10},
           { "name": "激励系统", "max": 10},
           { "name": "知识管理系统", "max": 10},
           { "name": "培训系统", "max": 10}
        ],
        "name": {
            "textStyle": {
                "color":"#000"
            }
        }
    },
    "series": [{
        "name": "团队职能模型",
        "type": "radar",
        "areaStyle": {"normal": { "type":"default"}},
        "data" : [
            {
                "value" : [5, 5, 6, 6, 6, 6, 6],
                "name" : "最低团队职能达标"
            },
            {
                "value" : [7, 5, 10, 9, 8.5, 9, 9.5],
                "name" : "最高团队职能达标"
            }
        ]
    }]
}
```