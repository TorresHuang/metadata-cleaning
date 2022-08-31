# 属性名：casdc:sdCreator

## 1. 描述
元数据作者。

## 2. 需要各数据中心自己修改的内容

  * <font color="#fc5531">中国科学院海洋科学数据中心</font>提供的是错误数据，其只是一串数字。
```json
中国科学院海洋科学数据中心数据
"casdc:sdCreator": "1461244441678352380.0"

```

## 2. 数据处理流程
### 2.1 新收割来的数据-数据处理流程：

  * 将<font color="#fc5531">中国科学院冰川冻土沙漠科学数据中心</font>属性里的数据直接存储在 ___casdc:sdCreator___ 字段下。

  * 将<font color="#fc5531">中国科学院南京土壤研究所所级中心</font>根据 ___@id___ list里数据，对 ___casdc:sdCreator___ 里的内容进行补全。

```json
原始数据

"casdc:sdCreator":{
   "@id":[
      "https://orcid.org/0000-0002-2946-0428",
      "https://orcid.org/0000-0001-5122-3579"
  ]
}

```
   


## 3. 标准规范
```json
"casdc:sdCreator" : {
        "@list" : [
            {
                "@identifier" : "8f86e0fb-8136-47f0-81e3-aa3f2f75483f",
                "@type" : "schema:Person",
                "schema:name" : [
                    "何剑锋",
                    {
                        "@value" : "He jianfeng",
                        "@language" : "en"
                    }
                ],
                "schema:worksFor" : "中国科学院西北生态环境资源研究院",
                "schema:telephone" : "021-50352091",
                "schema:nationality" : "",
                "schema:email" : "hejianfeng@pric.org.cn"
            }
        ]
    },
``` 