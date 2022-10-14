# 属性名： schema:description

## 1. 描述
关于数据资源的自由文本描述。

## 2. 数据处理流程

  * <font color="#fc5531">中国科学院冰川冻土沙漠科学数据中心</font>需要按照标准格式进行修改，加入 ___@en___ 以及 ___@zh___ 字段。

```json
原始数据

"schema:description" : [
            "本数据集为1999-2006年青海省玉树州乌丽多年冻土活动层数据,详细记录不同深度的土壤温度数据。SOIL T为土壤温度，单位为摄氏度（℃）WATER为土壤水分，单位为%。数据由布设的活动层观测探头测得，由数采取得原始数据，人工收集整理。",
            "This data set is the active layer data of permafrost in Wuli, Yushu prefecture, Qinghai Province from 1999 to 2006. The unit of soil moisture is centigrade. The data is measured by the active layer observation probe, and the original data is obtained by data acquisition, which is collected manually."
        ],
``` 
* <font color="#fc5531">中国科学院高能物理科学数据中心</font>需要按照标准格式进行修改，加入 ___@en___ 以及 ___@zh___ 字段。
```json
原始数据

    "schema:description" : "大亚湾中微子实验重建数据指从原始（模拟）数据中的电子学信号出发，通过计算还原出事例物理信息（如能量、位置等）的过程，所生成的重建数据用于随后的物理分析。",

``` 

* <font color="#fc5531">中国科学院昆明植物研究所所级中心</font>需要按照标准格式进行修改，加入 ___@en___ 以及 ___@zh___ 字段。
```json
原始数据
"schema:description" : [
        "国家重要野生植物种质资源共享服务平台（以下简称“平台”） 正式成立于2017年，依托中国科学院昆明植物研究所建设和运行，以中国科学院重大科技基础设施——中国西南野生生物种质资源库为核心，在全国范围内积极吸纳从事野生植物种质资源收集保存的相关单位，围绕国家战略需求持续开展重要野生植物种质资源的标准化收集、整理、保存工作；承接科技计划项目实施所形成的科技资源的汇交、整理和保存任务；开展野生植物种质资源的社会共享，面向各类科技创新活动提供公共服务，开展科学普及，根据创新需求整合资源开展定制服务；建设和维护在线服务系统，开展野生植物种质资源管理与共享服务应用技术研究；建立健全国家平台科技资源质量控制体系，保证科技资源的准确性和可用性。开展资源国际交流合作，参加相关国际学术组织，维护国家利益与安全。"
    ],

``` 


* <font color="#fc5531">中国科学院海洋科学数据中心</font>需要按照标准格式进行修改，加入 ___@en___ 以及 ___@zh___ 字段。
```json
原始数据
"schema:description" : "资助信息描述",
``` 

## 3. 标准规范
```json
"schema:description" : [
    {
       "@value" : "古生物化石标本", 
       "@language" : "zh"
    }, 
    {
       "@value" : "paleontology fossil specimen occurrence.", 
       "@language" : "en"
    }
]
``` 