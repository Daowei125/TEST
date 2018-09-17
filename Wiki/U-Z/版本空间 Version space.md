# 版本空间 Version Space

**版本空间**是概念学习中与已知数据集一致的所有假设的子集，通常用于对内容进行收敛。


版本空间学习是机器学习的逻辑方法，特别是二进制分类。版本空间学习算法搜索预定空间的假设，被视为一组逻辑语句。

对于二维空间中的“矩形”假设（右图），绿色加号代表正类样本，红色小圈代表负类样本。 GB 是最大泛化正假设边界(maximally General positive hypothesis Boundary), SB 是最大精确正假设边界(maximally Specific positive hypothesis Boundary). GB与SB所围成的区域中的矩形即为版本空间中的假设，也即GB与SB围成的区域就是版本空间。

在一些需要对假设的泛化能力排序的情形下，就可以通过GB与SB这两个上下界来表示版本空间。在学习的过程中，学习算法就可以只在GB、SB这两个代表集合上操作。


### 参考来源

【1】  https://www.jishux.com/p/1eaaad466795eb5c