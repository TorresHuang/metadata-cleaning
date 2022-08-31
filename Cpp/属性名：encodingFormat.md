# 属性名： schema:encodingFormat

## 1. 描述
数据资源的媒体类型。
                             
## 2. 数据处理流程
1. 读取<font color="#fc5531">中国科学院南海海洋研究所所级中心</font>属性"<font color="#fc5531">schema:encodingFormats</font>"的数据存储在<font color="#fc5531">schema:encodingFormat</font>字段里；   
&ensp;  


2. 其他数据中心数据处理方法：
	  *  如果是list，取出数据，并以英文逗号分割，存入数据库中（例如：[PDF, Excel]）； 
	  *  遇到[正斜杠(/)、反斜杠(\)、中文逗号(，)、英文逗号(,)、顿号(、) 、分号(；)、空格( )]等特殊符号，以这些特殊符号为分割符。 并以英文逗号分割，存入数据库中（例如：JPG/TIF ==》 JPG,TIF）
	  *  如果遇到null、None、undefined都转化为undefined存入数据库中。


## 3. 标准规范
```json
"schema:encodingFormat" : "JPG,TIF",
``` 