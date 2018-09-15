# Sigmoid 函数 Sigmoid function

**Sigmoid函数**是一个常见的 S 型函数，也称为 S 型生长曲线。由于其单增以及反函数单增等性质，Sigmoid 函数常被用作神经网络的阈值函数，将变量映射到 0,1 之间。

### Sigmoid 函数的基本性质：

Sigmoid 函数形式及图像：

![] (Sigmoid 函数公式.png)

![] (Sigmoid 函数图像.png)

- 定义域：( −∞ , +∞ )；

- 值域：(− 1 , 1 )；

- 函数在定义域内为连续和光滑函数；

- 处处可导，导数为：f′ ( x ) = f ( x ) ( 1 − f ( x ) )。

- 函数的取值在 0-1 之间，且在 0.5 处为中心对称，并且越靠近 x = 0 的取值斜率越大。

### Sigmoid 函数与逻辑回归

从 逻辑回归（ LR ）的目的上来看，在选择函数时，有两个条件是必须要满足的： 

1） 取值范围在 0~1 之间。 

2） 对于一个事件发生情况， 50% 是其结果的分水岭，选择函数应该在 0.5 中心对称。

从这两个条件来看， Sigmoid 很好的符合了 LR 的需求。

##### 相关词：逻辑回归，阀至函数。

### 参考来源

【1】  https://blog.csdn.net/saltriver/article/details/57531963

【2】  https://zh.wikipedia.org/wiki/邏輯函數

【3】  http://www.voidcn.com/article/p-ayyohasr-nh.html