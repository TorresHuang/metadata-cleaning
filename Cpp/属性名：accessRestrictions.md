# 属性名：http://www.re3data.org/schema/3-1/accessRestrictions

## 1. 描述
数据资源受限访问的类型。如果访问权限设置为受限访问，则必须进一步说明限制类型。


## 2. 数据处理流程
### 2.1 新收割来的数据-数据处理流程：

  * 各数据中心直接将该字段的数据以 ___string___ 的格式存储在数据库的 ___http://www.re3data.org/schema/3-1/accessRestrictions___ 字段中。 

### 2.2 科学数据中心的数据-数据处理流程：
  * 将 ___t_data_resources___ 表内属性 ___share___ 字段内的值按照 ___string___ 的格式存入到 ___http://www.re3data.org/schema/3-1/accessRestrictions___ 字段中。

## 3. 标准规范
```json
"http://www.re3data.org/schema/3-1/accessRestrictions" : "开放式共享",
``` 