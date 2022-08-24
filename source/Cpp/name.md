# 属性名： schema:name

## 1. 描述
数据资源的名称。

## 2. 数据处理流程
### 2.1 新收割来的数据-数据处理流程：
  * 将<font color="#fc5531">中国科学院生态科学数据中心</font>、<font color="#fc5531">中国科学院南京地理与湖泊研究所所级中心</font>中的 ___@value___ 为空的字段删除；
```json
 [
 	{'@value': '全球湖泊面积-水位长时序数据产品(2000-2020)', '@language': 'zh'},
 	{'@value': '', '@language': 'en'}
 ] 
``` 
  * 其他数据中心数据可以直接存储在数据库中。

### 2.2 科学数据中心的数据-数据处理流程：
  * 将属性 ___title___ 字段内的值按照 ___标准规范___ 进行修改，将title的值放入@value中，并添加@language字段。

## 3. 标准规范
```json
[
	{'@value': '祁连山地区基于MODIS的逐日地表蒸散发数据（2018)（ETHi-merge V1）', '@language': 'zh'},
	{'@value': 'Daily MODIS-based land surface evapotranspiration dataset in Qilian Mountain Area (ETHi-merge V1) (2018)', '@language': 'en'}
]
``` 