# 替代损失函数 Surrogate Loss Function

**替代损失函数**是原本的损失函数不便计算时使用的函数。


如果最优化代理损失函数的同时我们也最优化了原本的损失函数，就称校对性(calibration)或者一致性(consistency)。这个性质与我们所选择的代理损失函数相关。

一个重要的定理是，如果代理损失函数是凸函数，并且在 0 点可导，其导数小于 0 ，那么它一定是具有一致性的。这也是为什么我们通常选择凸函数作为我们的 loss function 的原因之一。

### 常用的替代函数

1） hinge损失：f ( x ) = max ( 0 , 1-x )；

2） 指数损失函数：f ( x ) = exp ( - x )；

3） 对数损失函数，f ( x ) = log ( 1 + exp ( -x ))；


##### 相关词： 代替函数，损失函数。

### 参考来源

【1】  http://sofasofa.io/forum_main_post.php?postid=1000605

【2】  https://blog.csdn.net/Touch_Dream/article/details/70171935