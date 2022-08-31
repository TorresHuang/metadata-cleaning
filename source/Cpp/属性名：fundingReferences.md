# 属性名： dct:fundingReferences

## 1. 描述
以资金支持和研究活动推动数据资源产生的科技项目或课题等。

## 2. 需要各数据中心自己修改的内容
  * <font color="#fc5531">中国科学院基因组科学数据中心</font>需要从新提交数据内容，其中 ___schema:funder___ 的值应该是 ___@type___ 属性的值。并且需要从新提交 ___schema:name___ 、 ___schema:description___ 以及 ___schema:funder___ 的值。
```json
原始数据

[
  {
    '@id': 'XDB13000000', 
    '@type': '', 
    'schema:funder': 'Strategic Priority Research Program of Chinese Academy of Sciences (CAS)', 
    'schema:name': 'casdc:other', 
    'schema:description': 'casdc:other'
  }
]
 ``` 

   * <font color="#fc5531">中国科学院青藏高原科学数据中心</font>需要从新提交数据内容，其中 ___@type___ 需要添加，___@type___ 具体是指项目的类型。还需要提交 ___@id___ 的数据，就是具体的项目id号。

``` json
原始数据

[
  {
    'schema:name': '第二次青藏高原综合科学考察研究', 
    '@type': '第二次青藏高原综合科学考察研究', 
    '@id': ''
  }
]
 ``` 

   * <font color="#fc5531">中国科学院海洋科学数据中心</font>需要从新提交数据内容，包括 ___@type___ 属性、 ___schema:description___ 属性、 ___@id___ 属性、 ___schema:name___ 属性、 ___schema:funder___ 属性以及 ___schema:accountablePerson___ 属性。


``` json
原始数据

 "dct:fundingReferences" : {
        "@type" : "",
        "schema:description" : "略。。。",
        "schema:funder" : "zhongkeyuan",
        "@id" : "",
        "schema:accountablePerson" : {

        },
        "schema:name" : "",
        "http://purl.org/cerif/frapo/ResearchInstitute" : {
            "@type" : "casdc:Organization",
            "@id" : "",
            "schema:name" : "中国科学院海洋研究所",
            "schema:email" : "sjzx@qdio.ac.cn"
        }
    },
 ``` 

   * <font color="#fc5531">中国科学院南京土壤研究所所级中心</font>需要从新提交项目的具体描述信息，即 ___schema:description___ 字段。


``` json
原始数据

 "dct:fundingReferences":[
  {
    "@id":"32071588",
    "@type":"国家自然科学基金资助项目",
    "schema:funder":"国家自然科学基金委",
    "schema:name":"荒漠植物白沙蒿种子粘液物质的微生物降解机制及其在种群更新中的作用",
    "schema:description":"略。。。"
  }
],
 ``` 

   * <font color="#fc5531">中国科学院冰川冻土沙漠科学数据中心</font>的数据可以直接存储在数据库中。

## 3. 数据处理流程
### 3.1 新收割来的数据-数据处理流程：
  * 将<font color="#fc5531">国家基础学科公共科学数据中心</font>属性 ___schema:fundingReferences___ 下的内容转存到 ___dct:fundingReferences___ 内，其中@type是项目类型， @id是项目号，schema:name是项目名。
```json
 [
    {
        '@type': '科技部-国家重点研发计划-科技助力经济2020', 
        '@id': 'SQ2020YFF0426440', 
        'schema:name': '柔性直流换流阀控制与监测性能提升技术研究与应用'
    }
]
 ``` 


### 3.2 科学数据中心的数据-数据处理流程：
  * 从 ___t_data_resources___ 表中取出属性 ___projectName___、 ___projectCategories___ 以及 ___projectNumber___ 分别对应属性 ___schema:name___、 ___@type___ 以及 ___@id___。

```json
原始数据

"projectName" : "化学学科领域重点数据库建设与应用服务",
"projectCategories" : "国家科技重大专项",
"projectNumber" : "XDA11000000"
 ``` 

 ```json
修改后的数据

"schema:name" : "化学学科领域重点数据库建设与应用服务",
"@type" : "国家科技重大专项",
"@id" : "XDA11000000"
 ``` 

<a id="jump1"></a>
## 4. 标准规范
```json
"dct:fundingReferences" : 
[
    {
        "@id" : "2013FY111400",
        "@type" : "国家科技基础性工作专项",
        "schema:name" : "中国西部主要冰川作用中心冰量变化调查"
    }
],
``` 