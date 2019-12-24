This the note for：2009Large-Scale Named Entity Disambiguation   

（没懂）2011 Merging domain ontologies based on the WordNet system and Fuzzy Formal Concept Analysis techniques（主要讲了本体对齐，比如利用上下位关系，具体没看懂，好像定义了一些规则）

####问题

将一个实体及其文本对应到wiki中的实体。  

#### 方法

利用上下文单词和目录标签，计算相似度。 

待对齐单词称为entity surface form。  

词袋模型。有两个词袋：tags、contexts。向量（上下文单词向量、主题单词向量）拼在一起，计算待对齐实体的向量和wiki文本向量的内积。 

基于假设：一段文本中同一名词指代同一实体。如果不符合，则缩小上下文。  