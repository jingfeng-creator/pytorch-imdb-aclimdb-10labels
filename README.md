# 文本分类 情感分析 pytorch imdb/aclimdb

## 应用imdb数据集电影评分的10分类预测

#### 目前网上对imdb的10分类代码很少，几乎都是二分类，不过差别也不大，我这个代码网络结构比较简单，新手可以看一下

#### 本人新手，代码还是有很多不完善的

测试集准确率大约**56%**，因为是10分类且网络简单，二分类很容易达到较高准确率

**预测值在标签值+-1范围内视为预测正确**

##### 文件结构

###### aclimdb:主函数

###### aclimdb_fun:一些函数

###### dataset:数据集，已处理为10分类用



为了达到更好的效果

​	1.仅采用出现频率较高的一部分单词构建词典

​	2.使用weight_decay







