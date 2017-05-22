### 项目经理-能力素质集合

|领导能力|管理能力|思维能力|专业素质|个人特质|态度品质|
|----|----|----|----|----|----|
|战略规划|计划执行|信息收集|质量意识(扩展)|积极主动|诚信正直|
|团队领导|组织协调|学习领悟|主动汇报(扩展)|沟通能力|敬业精神|
|      |影响能力|归纳思维|代码规范(扩展)|关注细节|团队合作|
|      |培养指导|创新能力|开发环境统一(扩展)|自控能力|责任心|
|      |决策能力|分析式思维|需求理解能力(扩展)|人际交往|组织承诺|
|      |       |       |模块化思维(扩展)|自信心|全局观念|
|      |       |       |关注整体能力-工作内容(扩展)|灵活性|       |
|      |       |       |关注整体能力-组织结构(扩展)|成就动机|       |
|      |       |       |专业性|坚持不懈|       |
|      |       |       |成本意识|     |       |
|      |       |       |客户导向|     |       |


### 项目经理能力素质-标准雷达图

```chart
{
    "title": {
        "text": "项目经理模型"
    },
    "tooltip": {},
    "color":["#D40200","#91C7AE"],
    "legend": {
        "data": ["最低项目经理能力素质达标", "最高项目经理能力素质达标"]
    },
    "radar": {
        "indicator": [
           { "name": "领导能力", "max": 10},
           { "name": "管理能力", "max": 10},
           { "name": "思维能力", "max": 10},
           { "name": "专业素质", "max": 10},
           { "name": "个人特质", "max": 10},
           { "name": "态度品质", "max": 10}
        ],
        "name": {
            "textStyle": {
                "color":"#000"
            }
        }
    },
    "series": [{
        "name": "项目经理模型",
        "type": "radar",
        "areaStyle": {"normal": { "type":"default"}},
        "data" : [
            {
                "value" : [5, 4, 6, 6, 6, 6],
                "name" : "最低项目经理能力素质达标"
            },
            {
                "value" : [10, 10, 10, 10, 10, 10],
                "name" : "最高项目经理能力素质达标"
            }
        ]
    }]
}
```