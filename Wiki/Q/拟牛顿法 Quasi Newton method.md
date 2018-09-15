# 拟牛顿法 Quasi Newton method

**拟牛顿法**是一种以牛顿法为基础设计的，求解非线性方程组或连续的最优化问题函数的零点或极大、极小值的算法。

当牛顿法中所要求计算的雅可比矩阵或 Hessian 矩阵难以甚至无法计算时，拟牛顿法便可派上用场。

拟牛顿法是求解非线性优化问题最有效的方法之一，于20世纪50年代由美国  Argonne 国家实验室的物理学家 W.C.Davidon 所提出来。


### 拟牛顿法的思想

拟牛顿法的本质思想是改善牛顿法每次需要求解复杂的 Hessian 矩阵的逆矩阵的缺陷，它使用正定矩阵来近似 Hessian 矩阵的逆，从而简化了运算的复杂度。

### 常见的拟牛顿算法

1）DPF 方法；2）BFGS 方法；3）SR-1 方法。

##### 相关词：牛顿法，优化

### 参考来源：

【1】 https://zh.wikipedia.org/wiki/拟牛顿法

【2】 http://www.cnblogs.com/maybe2030/p/4751804.html

【3】 https://blog.csdn.net/fangqingan_java/article/details/47158115