# 属性名：schema:publisher

## 1. 描述
为数据资源提供学术审核并支持其获得唯一标识符的出版机构。


## 2. 数据处理流程
### 2.1 新收割来的数据-数据处理流程：

   * <font color="#fc5531">国家基础学科公共科学数据中心</font>、<font color="#fc5531">中国科学院广州生物医药与健康研究所所级中心</font>、<font color="#fc5531">中国科学院化学化工科学数据中心</font>的@id需要进行补全。
```json
中国科学院广州生物医药与健康研究所所级中心数据修改前
{
    '@id': 'http://semweb.casdc.cn/resource/casorgs', 
    'schema:logo': 'http://cytomics.gibh.ac.cn/api/banaer_icoLogo/a5b34672681a48d7ba8e72f481cdf138icoLogo.png', 
    'schema:name': '中国科学院广州生物医药与健康研究院所级中心'
}
```

```json
对照表

中国科学院广州生物医药与健康研究院所级中心   http://semweb.casdc.cn/resource/casorgs#GIBH
中国科学院化学化工科学数据中心 没有对应的@id
国家基础学科公共科学数据中心 没有对应的@id
```

```json
修改后
{
    '@id': 'http://semweb.casdc.cn/resource/casorgs#GIBH', 
    'schema:logo': 'http://cytomics.gibh.ac.cn/api/banaer_icoLogo/a5b34672681a48d7ba8e72f481cdf138icoLogo.png', 
    'schema:name': '中国科学院广州生物医药与健康研究院所级中心'
}

```

  * <font color="#fc5531">中国科学院基因组科学数据中心</font>只给了 ___schema:name___ 这个属性，我们这里需要进行补全。
```json
修改前
{
    'schema:name': 'Beijing Institute of Genomics, Chinese Academy of Sciences / China National Center for Bioinformation'
}
```

```json
修改后
{
    '@id': 'http://semweb.casdc.cn/resource/casorgs#BIG', 
    'schema:logo': 'https://ngdc.cncb.ac.cn:443/static/image/ngdc.png', 
    'schema:name': '中国科学院基因组科学数据中心'
}
```

### 2.2 科学数据中心的数据-数据处理流程：

```json
修改前

中国科学院水生生物研究所科学数据中心
```

```json
修改后

{
    '@id': 'http://semweb.casdc.cn/resource/casorgs#IHB', 
    'schema:name': '中国科学院水生生物研究所科学数据中心'
}
```

## 3. 标准规范
```json
"schema:publisher" : {
    '@id': 'http://semweb.casdc.cn/resource/casorgs#GIBH', 
    'schema:logo': 'http://cytomics.gibh.ac.cn/api/banaer_icoLogo/a5b34672681a48d7ba8e72f481cdf138icoLogo.png', 
    'schema:name': '中国科学院广州生物医药与健康研究院所级中心'
},
``` 