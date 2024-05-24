# 算子
​HuggingFists的相关算子，用于读、写以及处理数据。安装时，先安装descriptor结尾的zip包，再安装oyez结尾的zip包。
## moo
​moo目录下存放了模型相关的算子
### google
​Google相关的模型算子。内含：
**VertexAITextEmbedding**：文本向量化算子
**VertexAIGeminiTextGenerator**：基于Gemini模型的文本生成
**VertexAITextGenerator**：基于Bard模型的文本生成
### moonshot
​月之暗面相关的模型算子。包含：
**MoonShotConversation**：月之暗面对话算子
### prompt
​大语言提示算子。包括：
**CommonPrompt**：大语言模型提示算子
**LargeTextPrompt**：大语言模型复杂文本提示算子
### zhipu
​	智谱相关的模型算子。包含：
  **ZhiPuConversation**：智谱对话算子
  **ZhiPuTextEmbedding**：智谱文本嵌入算子
  **ZhiPuTextGenerator**：智谱文本生成算子
## process
​	process目录下存放了数据处理相关的算子。
### row
​	针对行的数据处理算子。包括：特征统计、条件过滤、布隆过滤、分组、去重、排序、集合计算、采样及列集拆分相关算子。
### struct
​	影响数据结构的数据处理算子。包含：
  **Json2KVTable**：Json转KV对
  **JsonFlatter**：Json扁平化
  **ObjectFlatter**：对象扁平化
  **XmlFlatter**：Xml扁平化  


