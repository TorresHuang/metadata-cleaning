# 属性名： schema:keywords

## 1. 描述
描述数据资源内容的自由关键词或标签，多个条目间以英文逗号分隔。

## 2. 数据处理流程
### 2.1 新收割来的数据-数据处理流程：
  * 将<font color="#fc5531">中国科学院东北地理与农业生态研究所所级中心</font>、<font color="#fc5531">中国科学院昆明植物研究所所级中心</font>、<font color="#fc5531">中国科学院南海海洋研究所所级中心</font>、<font color="#fc5531">中国科学院干细胞与再生医学科学数据中心</font>中的数据是存储在一个list内的，按照 ___标准规范___ 进行修改。
```json
原始数据

[
	{
		'@value': '黑龙江省，各地区，农业，第一产业增加值，农产品产量，畜产品产量',
		'@language': 'zh'
	}
]
``` 

```json
修改后的数据

[
    {
        "@value" : "黑龙江省",
        "@language" : "zh"
    },
    {
        "@value" : "各地区",
        "@language" : "zh"
    },
    {
        "@value" : "农业",
        "@language" : "zh"
    },
    {
        "@value" : "第一产业增加值",
        "@language" : "zh"
    },
    {
        "@value" : "农产品产量",
        "@language" : "zh"
    },
    {
        "@value" : "畜产品产量",
        "@language" : "zh"
    }
]
``` 

  * 将<font color="#fc5531">中国科学院南京地理与湖泊研究所所级中心</font>、<font color="#fc5531">中国科学院干细胞与再生医学科学数据中心</font>属性 ___keywords___ 的值转存在 ___schema:keywords___ 字段内； 

  * 将<font color="#fc5531">中国科学院地球大数据科学数据中心</font>的数据是以分号相隔的，按照 ___标准规范___ 进行修改。

```json
原始数据

[
    {
        '@value': 'SAR;海浪;海浪积分参数;有效波高;平均波周期', 
        '@language': 'zh'
    }
]
``` 

```json
修改后的数据

[
    {
        "@value" : "SAR",
        "@language" : "en"
    },
    {
        "@value" : "海浪",
        "@language" : "zh"
    },
    {
        "@value" : "海浪积分参数",
        "@language" : "zh"
    },
    {
        "@value" : "有效波高",
        "@language" : "zh"
    },
    {
        "@value" : "平均波周期",
        "@language" : "zh"
    }
]
``` 

### 2.2 科学数据中心的数据-数据处理流程：
  * 将属性 ___keywords___ 字段内的值按照分号进行分割。

```json
原始数据

城市生活垃圾;填埋场;物质存量;组成组分;环境影响;粤港澳大湾区
``` 

```json
修改后的数据

[
    {
        "@value" : "城市生活垃圾",
        "@language" : "zh"
    },
    {
        "@value" : "填埋场",
        "@language" : "zh"
    },
    {
        "@value" : "物质存量",
        "@language" : "zh"
    },
    {
        "@value" : "组成组分",
        "@language" : "zh"
    },
    {
        "@value" : "环境影响",
        "@language" : "zh"
    },
    {
        "@value" : "粤港澳大湾区",
        "@language" : "zh"
    },
]
``` 
  



## 3. 标准规范
```json
"schema:keywords" : [
        {
            "@value" : "湖相沉积",
            "@language" : "zh"
        },
        {
            "@value" : "古环境",
            "@language" : "zh"
        },
        {
            "@value" : "孢粉学",
            "@language" : "zh"
        },
        {
            "@value" : "同位素",
            "@language" : "zh"
        },
        {
            "@value" : "Isotope",
            "@language" : "en"
        },
        {
            "@value" : "isotope",
            "@language" : "en"
        },
        {
            "@value" : "Palaeoenvironment",
            "@language" : "en"
        },
        {
            "@value" : "Lacustrine Sediments",
            "@language" : "en"
        }
    ],
``` 