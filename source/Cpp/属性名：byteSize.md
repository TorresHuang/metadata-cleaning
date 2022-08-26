# 属性名：dcat:byteSize

## 1. 描述
数据资源的文件大小，以kb为单位。

## 2. 数据处理流程
### 2.1 新收割来的数据-数据处理流程：

  * 将<font color="#fc5531">中国科学院海洋科学数据中心</font>和<font color="#fc5531">中国科学院冰川冻土沙漠科学数据中心</font> ___dcat:byteSize___ 属性里的 ___value___ 值取出转存为 ___"dcat:byteSize" : 8305212.0___ 。

```json
需要修改的原始数据：
{
    '@type': 'QuantitativeValue', 
    'value': 8305212.0
}

```

```json
修改后：
"dcat:byteSize" : 8305212.0,

```

  * 将<font color="#fc5531">中国科学院南京地理与湖泊研究所所级中心</font> ___byteSize___ 属性下的值转存到 ___dcat:byteSize___ 下。

### 2.2 科学数据中心的数据-数据处理流程：
  * 将 ___t_data_resources___ 表内属性 ___size___ 字段内的值进行转化存入到 ___dcat:byteSize___ 字段中。

```json
会出现的字段类型：
KB、MB、G、GB、T、TB、约15T/月（转化为16106127360）、待定（转化为0）

```

```json
需要修改的原始数据：
463.4MB

```

```json
修改后：
"dcat:byteSize" : 474521.6,

```

## 3. 标准规范
```json
"dcat:byteSize" : 1319414000000.0,
``` 