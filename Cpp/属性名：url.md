# 属性名： schema:url

## 1. 描述
统一资源定位符。

## 2. 数据处理流程
### 2.1 新收割来的数据-数据处理流程：
   * 需要将<font color="#fc5531">中国科学院昆明植物研究所所级中心</font>、<font color="#fc5531">中国科学院南京地理与湖泊研究所所级中心</font>属性 ___url___ 中的值转存为 ___schema:url___ 中的值。

### 2.2 科学数据中心的数据-数据处理流程：
   * 直接将t_data_resourcese表内的 ___url___ 属性的数据，转存到  ___schema:url___ 下。

## 3. 标准规范
```json
"schema:url" : "http://www.igadc.cn/info/ufed8",
``` 