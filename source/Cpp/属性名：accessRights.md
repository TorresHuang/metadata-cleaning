# 属性名：dcterms:accessRights

## 1. 描述
有关谁可以访问数据资源的指示。

## 2. 数据处理流程
### 2.1 新收割来的数据-数据处理流程：
  * 将<font color="#fc5531">中国科学院南京地理与湖泊研究所所级中心</font>属性 ___accessRights___ 的值存储在 ___dcterms:accessRights___ 下； 

  * 其他数据中心直接将值存储在 ___dcterms:accessRights___ 下。

### 2.2 科学数据中心的数据-数据处理流程：
  * 将属性 ___rightStatement___ 的值以 ___sring___  的格式存储在  ___dcterms:accessRights___ 下； 

```json
原始数据

本平台提供的服务知识产权归平台提供者所有。

在使用数据时，请明显标注“本数据来自波密地质灾害观测研究站

版权属于OMIX数据库，未经授权，不得将从本系统中获取的数据传播给第三方，不得将从本系统中获取的数据用于其他数据库系统或网站。
``` 

## 3. 标准规范
```json
"dcterms:accessRights" : "http://purl.org/coar/access_right/c_abf2"
``` 