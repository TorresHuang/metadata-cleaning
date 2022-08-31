# 属性名： schema:identifier

## 1. 描述
数据资源的唯一标识符。


## 2.需要各数据中心自己修改的内容
* <font color="#fc5531">中国科学院海洋科学数据中心</font>需要从新提交数据，现在的格式都是 ___CSTRnull___ ，@id为空的时候需要从新提交数据; 
```json
错误示例

[
    {'@type': 'dct:DOI', '@id': ''}, 
    {'@type': 'casdc:CSTR', '@id': 'https://casdc.cn/CSTRnull'}
]
``` 


## 3. 数据处理流程
### 3.1 新收割来的数据-数据处理流程：
  * 将<font color="#fc5531">中国科学院化学化工科学数据中心</font>、<font color="#fc5531">中国科学院地球大数据科学数据中心</font>、<font color="#fc5531">中国科学院生态科学数据中心</font>里的 ___http://:___ 变为  ___http://___   ; 
```json
错误示例

http://:doi.org/10.12199/nesdc.ecodb.mod.20200001.04
``` 

```json
修改后的数据

http://doi.org/10.12199/nesdc.ecodb.mod.20200001.04
``` 

  * 去掉<font color="#fc5531">中国科学院冰川冻土沙漠科学数据中心</font> ___CSTR:___ ； 
```json
错误示例

https://cstr.escience.org.cn/CSTR:CSTR:11738.11.ncdc.nieer.2020.1411
``` 

```json
修改后的数据

https://cstr.escience.org.cn/CSTR:11738.11.ncdc.nieer.2020.1411
``` 

   * 去掉<font color="#fc5531">中国科学院中国科学技术大学所级中心</font>  ___@type___ 字段里包含cstr的内容进行修改 ； 


```json
修改前的数据

"schema:identifier":[
    {
      "@type":"dct:DOI",
      "@id":"https://doi.org/10.57841/casdc.0000003"
    },
    {
      "@type":"https://www.iana.org/assignments/uri-schemes/prov/cstr",
      "@id":"https://cstr.cn/38458.11.USTC.yqlbiRnR"
    }
],
``` 

```json
修改后的数据

"schema:identifier":[
    {
      "@type":"dct:DOI",
      "@id":"https://doi.org/10.57841/casdc.0000003"
    },
    {
      "@type":"casdc:CSTR",
      "@id":"https://cstr.cn/38458.11.USTC.yqlbiRnR"
    }
],
``` 


    

  * 其他数据中心的 ___schema:identifier___ 字段保持原状态不变。 

## 4. 标准规范
```json
[
    {
        '@id': 'http://:doi.org/10.12199/nesdc.ecodb.mod.20200001.04', 
        '@type': 'dct:DOI'
    }, 
    {
        '@id': 'https://cstr.cn/15732.11.nesdc.ecodb.mod.20200001.04', 
        '@type': 'casdc:CSTR'
    }
]
``` 