# 算子
 ​HuggingFists的相关算子，用于读、写以及处理数据。安装时，先安装descriptor结尾的zip包，再安装oyez结尾的zip包。
## moo
 ​moo目录下存放了模型相关的算子
### deepseek
 ​deepseek模型相关的算子。内含：
 
 **DeepseekTextGenerator**：Deepseek文本生成
 
 **DeepseekTextConversation**：Deepseek对话

 **DeepseekInferencer**：Deepseek推理

## process
​	process目录下存放了数据处理相关的算子。
### lang
​	编程语言插件算子。包含：

  **Javascript**：Javascript算子
  
  **Python**：Python算子
  
### row
​	针对行的数据处理算子。包括：特征统计、条件过滤、布隆过滤、分组、去重、排序、集合计算、采样及列集拆分相关算子。
### struct
​	影响数据结构的数据处理算子。包含：

  **Json2KVTable**：Json转KV对
  
  **JsonFlatter**：Json扁平化
  
  **ObjectFlatter**：对象扁平化
  
  **XmlFlatter**：Xml扁平化  


