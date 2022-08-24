# 属性名： dct:fundingReferences

## 1. 描述
以资金支持和研究活动推动数据资源产生的科技项目或课题等。




8）genome [{'@id': 'XDB13000000', '@type': '', 'schema:funder': 'Strategic Priority Research Program of Chinese Academy of Sciences (CAS)', 'schema:name': 'casdc:other', 'schema:description': 'casdc:other'}]

9）glacier  [{'@id': '2013FY111400', '@type': '国家科技基础性工作专项', 'schema:name': '中国西部主要冰川作用中心冰量变化调查'}]

10）health

11）kunmingPlant

12）lake

13）nanhaiSea
 
14）qingzang [{'schema:name': '第二次青藏高原综合科学考察研究', '@type': '第二次青藏高原综合科学考察研究', '@id': ''}]

15）regenerativeMedicine 

16）sea {'@type': '', 'schema:description': '略。。。', 'schema:funder': 'zhongkeyuan', '@id': '', 'schema:accountablePerson': {}, 'schema:name': '', 'http://purl.org/cerif/frapo/ResearchInstitute': {'@type': 'casdc:Organization', '@id': '', 'schema:name': '中国科学院海洋研究所', 'schema:email': 'sjzx@qdio.ac.cn'}}

projectNmae  示例(化学学科领域重点数据库建设与应用服务)     
projectCategories 示例（国家科技重大专项）      
projectNumber  示例(XDA11000000)      



## 2. 需要各数据中心自己修改的内容
  * <font color="#fc5531">中国科学院基因组科学数据中心</font>需要从新提交数据内容，其中@type--项目类型是空值，schema:name是空值，
  。
```json
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
   * <font color="#fc5531">中国科学院南海海洋研究所所级中心</font>提供的类型是一串数字，不知道什么类型，需要进行修改。
```json
{
	'@value': ['物理海洋'], 
	'@type': '1706010'
}
``` 

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
1.将属性 ___category___ 中的数值统一存储在 ___dct:Subject___ 字段下，并修改格式为[标准规范](#jump1)的格式。

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