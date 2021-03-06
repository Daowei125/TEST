# 径向基函数 Radial Basis Function

**径向基函数**（RBF）是某种沿径向对称的标量函数。通常定义为空间中任一点 X 到某一中心 X<sub>c</sub> 之间距离的单调函数。可记作 K(||X-X<sub>c</sub>||), 其作用往往是局部的 , 即当 X 远离 X<sub>c</sub> 时函数取值很小。

其中，范数一般为欧几里得距离，不过亦可使用其他距离函数。

### 径向基函数的应用

径向基函数的主要是为了解决多变量插值的问题可以用于许多向函基数的和来逼近某一给定的函数。这一逼近的过程可看作是一个简单的神经网络。

在机器学习中，径向基函数还被用作支持向量机的核函数。在神经网络结构中，可以作为全连接层和 ReLU（线性修正单元）层的主要函数。


### 常见的径向基函数

常见的RBF有： 1）高斯函数； 2）多二次函数； 3）逆二次函数； 4）逆多二次函数； 5）多重调和样条； 6）薄板样条。

### 径向基函数适用条件  

RBF 用于根据大量数据点生成平滑表面。这些函数可为平缓变化的表面（如高程）生成很好的结果。

但在表面值在短距离内出现剧烈变化和/或怀疑样本值很可能有测量误差或不确定性时，这些方法不适用。

### 径向基函数网络

使用径向基函数作为激活函数的人工神经网络称为径向基函数网络（ Radial basis function network ）。

径向基函数网络的输出是输入的径向基函数和神经元参数的线性组合。

径向基函数网络具有多种用途，包括包括函数近似法、时间序列预测、分类和系统控制。

##### 父级词：径向奇函数网络
##### 相关词：高斯核函数     

### 参考来源：

【1】  https://www.cnblogs.com/hxsyl/p/5231389.html

【2】  https://en.wikipedia.org/wiki/Radial_basis_function

【3】  https://blog.csdn.net/dengheCSDN/article/details/78109253?locationNum=2&fps=1