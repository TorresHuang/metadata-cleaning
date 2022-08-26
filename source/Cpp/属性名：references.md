# 属性名：dcterms:references

## 1. 描述
数据资源引用或以其他方式指向的参考资源，如论文，数据集等，符合相应的参考文献书写格式。

## 2. 数据处理流程
### 2.1 新收割来的数据-数据处理流程：

   * 将<font color="#fc5531">中国科学院冰川冻土沙漠科学数据中心</font>的数据直接按照原始格式进行存储。

## 3. 标准规范
```json
"dcterms:references" : {
        "@id" : "",
        "@type" : "http://purl.org/coar/resource_type/c_ddb1",
        "schema:name" : {
            "@value" : "1999-2000年南极长城湾水样抽滤记录",
            "@language" : "zh"
        },
        "schema:keywords" : [
            {
                "@value" : "极地",
                "@language" : "zh"
            },
            {
                "@value" : "CTD",
                "@language" : "zh"
            },
            {
                "@value" : "水样记录",
                "@language" : "zh"
            },
            {
                "@value" : "Polar",
                "@language" : "en"
            },
            {
                "@value" : "CTD",
                "@language" : "en"
            },
            {
                "@value" : "Water sample record",
                "@language" : "en"
            }
        ],
        "schema:identifier" : {
            "@id" : "http://www.ncdc.ac.cn/portal/metadata/11b778bc-ffe0-4c17-9694-91cb7e082295",
            "@type" : "dct:DOI"
        },
        "schema:description" : [
            "长城站建于1985年2月20日，坐落在南设得兰群岛乔治王岛；地理坐标为：南纬62度12分59秒，西经58度57分52秒。59秒，西经58度57分52秒。长城站位于乔治岛的菲尔德斯半岛上，它面临民防湾中的一条小湾，这条小湾已被中国南极考察队命名为长城湾。本数据集为南极长城湾1999-2000年水样抽滤记录观测数据。",
            "TheGreatWallStationwasbuiltonFebruary20,1985,andislocatedonKingGeorgeIslandintheSouthShetlandIslands.Thegeographicalcoordinatesare:62°12:59southlatitude,58°57:52westlongitude.59seconds,58degrees,57minutesand52seconds.ThisdatasetistheobservationdataofwatersamplingandfiltrationinGreatWallBay,Antarctica,1999-2000"
        ],
        "schema:publisher" : {
            "@type" : "casdc:Organization",
            "schema:name" : "NIEER",
            "schema:datePublished" : {
                "@value" : "2020-12-30T17:05:56+08:00",
                "@type" : "xsd:date"
            }
        },
        "schema:creator" : {
            "@type" : "schema:Person",
            "schema:name" : "何剑锋"
        }
    },
``` 