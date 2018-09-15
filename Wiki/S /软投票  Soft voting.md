# 软投票  Soft voting

**软投票**也称加权平均概率投票。它是使用输出的类概率来进行分类的投票法，通过输入权重，得到每个类的类概率的加权平均值，值大的那一类会被选择。

### 软投票与硬投票

与硬投票相比，软投票将类别标签返回为预测概率之和的 argmax 。

分类的机器学习算法输出有两种类型：一种是直接输出类标签，另外一种是输出类概率，使用前者进行投票叫做硬投票(Majority/Hard voting)，使用后者进行分类叫做软投票(Soft voting)。


##### 父级词：投票分分类器
##### 相关词：多数投票，相对多数投票，硬投票

### 参考来源

【1】  http://sklearn.apachecn.org/cn/stable/modules/ensemble.html#id12

【2】  https://www.cnblogs.com/jiaxin359/p/8777574.html