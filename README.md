# NLP-知识
#### （1）word2vec
##### 优化方法：
为了提高速度，Word2vec 经常采用 2 种加速方式：Negative Sample（负采样），Hierarchical Softmax
##### 缺点：
（1）由于词和向量是一对一的关系，所以多义词的问题无法解决。  
（2）Word2vec 是一种静态的方式，虽然通用性强，但是无法针对特定任务做动态优化
##### 优点
（1）由于 Word2vec 会考虑上下文，跟之前的 Embedding 方法相比，效果要更好（但不如 18 年之后的方法）  
（2）比之前的 Embedding方 法维度更少，所以速度更快  
（3）通用性很强，可以用在各种 NLP 任务中  

