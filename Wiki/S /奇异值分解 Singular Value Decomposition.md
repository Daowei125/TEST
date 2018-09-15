# 奇异值分解 Singular Value Decomposition

**奇异值分解**（ SVD ）是一种重要的矩阵分解方法，对称阵特征向量分解的基础是谱分析，而奇异值分解则是谱分析理论在任意矩阵上的推广。

### SVD 数学表示

SVD 可表述为：假设 A 是一个 m×n 的实矩阵，

那么，存在 m×m 的酉矩阵 U 和 n×n 的酉矩阵 V 使得：

 ![](奇异值分解.png)

其中 Σ 是 m×n 的非负实数对角矩阵；

 ![](奇异值分解-1.png)

主對角元 σ <sub>i</sub>  > 0，i = 1 , 2 ,..., r ，且 σ <sub>i + 1</sub>= ... = σ <sub> p </sub> = 0 ，p = min { m , n }，称作奇异值 ( singular values )。

SVD 的分解不具有唯一性，通常将奇异值由大至小排序： σ <sub>1</sub> > σ <sub>2</sub> > ... > σ <sub>i</sub> > 0。

### SVD 的图形表示及几何意义

 ![](奇异值分解-2.jpg)
 
 
SVD 可视为 A 的三個分解步驟：旋轉 V<sup>T</sup>，伸縮 Σ ，再旋轉 U 。

### SVD 的应用

1） 求广义逆阵（伪逆）；2） 给出矩阵的列空间、零空间和秩的表示；3）求矩阵近似值，比如求解主成分分析问题。

##### 相关词：酉矩阵，谱分解
##### 父级词：矩阵分解

### 参考来源

【1】  https://liam0205.me/2017/11/22/SVD-for-Human-Beings/

【2】  http://www.cnblogs.com/LeftNotEasy/archive/2011/01/19/svd-and-applications.html

【3】  https:////ccjou.wordpress.com/2009/09/01/奇異值分解-svd/

【4】  https://zh.wikipedia.org/wiki/奇异值分解