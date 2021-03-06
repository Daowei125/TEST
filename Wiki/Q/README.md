# README

# *Q List* 

****

# 量子神经网络 Quantum Neural Network / QNN

**量子神经网络** （ QNN ）是由若干个量子神经元按一定的拓扑结构构成的网络。

它是试图将人工神经网络模型与量子信息的优势相结合的一种方法。目前仍处于研究阶段。


### QNN 的研究动因 

量子过程的本体论解释和感知器的脑过程的完全性理论有同样的数学结构,这两个过程的动态方程都包含了一种场, 即量子势或神经势。

基于量子势的量子过程和基于神经势的脑过程的动态方程有惊人的相似之处 。这促进了二者的融合。


### QNN 的主要研究方向

(1) 采用神经网络的连接思想来构造量子计算机，通过神经网络模型来研究量子计算中的问题；
 
(2) 在量子计算机或量子器件的基础上构造神经网络，利用量子计算超高速、超并行、指数级容量的特点，来改进神经网络的结构和性能；
   
(3) 作为一种混合的智能优化算法在传统的计算机上的实现；

(4) 借以对脑科学和认知科学做深入研究。


### QNN 的潜在优势 

基于量子神经网络的量子神经计算 (QNC) 的研究还处于萌芽阶段,其理论远未成熟。

但与传统的神经计算比较, 至少在以下几个方面具有明显的优势: 
 
(1) 指数级的记忆容量和回忆速度;  

(2) 较小的网络规模和简单的网络拓扑结构；
 
(3) 更好的稳定性和有效性；

(4) 快速学习、一次学习和高速处理信息的能力；
  
(5) 消除灾变性失忆的潜力。

##### 相关词：量子，神经网络，量子计算

### 参考来源：

【1】 http://muchong.com/html/200506/93984.html  

【2】 https://en.wikipedia.org/wiki/Quantum_neural_network

【3】 解光军, 庄镇泉. 量子神经网络[J]. 计算机科学, 2001, 28(7):1-6.

【4】 李盼池. 一种量子神经网络模型学习算法及应用[J]. 控制理论与应用, 2009, 26(5):531-534.
 
  
****

# 量子计算 Quantum Computing

**量子计算**是一种基于量子效应的新型计算方式。基本原理是以量子位作为信息编码和存储单元，通过大量量子位的受控演化来完成计算任务。

![](量子计算.png)

### 量子计算和传统计算的对比

(1)  信息表达

在传统计算中，计算机运行的单位是比特，取值为 0 或 1 。量子位与此类似，但除了 0 或 1 ，它还包含了更多复杂信息，甚至是取负值。

量子位在取值之前处于不确定状态（即所谓的“叠加”），可能受到其他量子位的影响（这就是所谓的“纠缠”）。量子位能够以多种方式（电子自旋、光偏振、超导电路等）实现，但量子理论的结果与信息存储和处理的具体机制无关。

(2) 信息处理

在传统计算机中，比特是按顺序处理的，这类似于人们一步步手动解决数学问题的方式。在量子计算中，量子位则纠缠在一起。一个量子位状态的改变，会影响其他量子位的状态。

从本质上来讲，这使量子计算机可以快速地收敛到问题的正确答案。因此，在找到最优解决方案上，量子计算比某些传统方式更有效。

(3) 解释结果

在传统计算中，受算法的设计限制，只可以使用明确定义的结果。量子答案（在数量上称为振幅）具有概率性。这意味着，由于叠加和纠缠，在特定的计算中会考虑多种可能的答案。随着问题的多次出现，不断给出可能答案的样本，并累加对所提供最佳答案的信心。结合统计学可以得到某一答案为正确答案的可能性。能通过调整该置信度阈值来提供最佳的速度和准确度。

##### 相关词：量子计算机 

### 参考来源：

【1】 https://www.ibm.com/developerworks/cn/linux/other/quant/index.html

【2】 https://www.accenture.com/cn-zh/insight-outlook-zhanwang-thinking-beyond-ones-zeros

****

# 量子计算机 Quantum Computer

**量子计算机**是一种使用量子逻辑进行通用计算的设备。是量子计算的具体实现形式

不同于电子计算机（传统计算机），量子计算用来存储数据的对象是量子比特，它使用量子算法来进行数据操作。

### 量子计算机的种类
 
目前常见的有绝热量子计算机和门模型量子计算机，二者各具优缺点：

- 绝热量子计算机（又名“退火炉”）

> 绝热量子计算机是一种特殊的量子退火炉，它最适于解决优化问题这一行业普遍存在的问题。除此以外，该方法还可用来解决抽样和机器学习问题。

- 门模型量子计算机（又名“电路模型”或 “标准模型”）：

> 因为硬件的特殊性，构建门模型量子计算机在技术上具有挑战性。这种量子计算机通过运用量子门（对一些单一量子位进行操作的基本量子线路）控制量子状态，从而进行计算。量子线路构件的方式，与经典逻辑门形成传统数字线路构建的方式相似。


### 量子计算机需要满足的条件

1）量子计算机必须有可识别的定义明确的量子比特；

2）量子计算机必须可以进行可信的初态制备；

3）量子计算机必须具有较弱的退相干效应；

4）量子计算机必须可以进行精确的量子门操；

5）量子计算机必须建立非常强的量子测量机制。

### 量子计算最适用领域

(1) 优化问题。

优化是量子计算目前重点关注的领域，其目标是从大量可能的决定中找出最佳方案。

传统计算机为优化问题、提供高质量的解决方案所需的时间，通常会随问题规模呈指数级增长，但量子计算的高效性将更快的提供答案。

(2) 抽样问题。

这是绝热量子计算机可以执行的另一功能。抽样可以顺利随机生成某些现象的随机样例，而经典计算机却很难有效做到。

然而，如果可以控制复杂的量子状态（本身具有概率性），便可更为有效地从这些状态抽样。

(3) 机器学习。

由于机器学习的基础是抽样和优化方法，所以完善这些技术就可以提高机器学习能力。

量子计算机的抽样技术，可以为机器学习算法提供更多可靠的分布式输入数据。

##### 相关词：量子计算，量子位

### 参考来源：

【1】  https://www.accenture.com/cn-zh/insight-outlook-zhanwang-thinking-beyond-ones-zeros

【2】  https://www.leiphone.com/news/201512/XCHRf7rcS6SwGrxh.html

****

# 拟牛顿法 Quasi Newton method

**拟牛顿法**是一种以牛顿法为基础的优化方法。主要用来求解非线性方程组或连续函数的零点或极大、极小值问题。

当牛顿法中所要求计算的雅可比矩阵或 Hessian 矩阵难以甚至无法计算时，可以用到拟牛顿法。

拟牛顿法是求解非线性优化问题最有效的方法之一，于20世纪50年代由美国 Argonne 国家实验室的物理学家 W.C.Davidon 所提出来。


### 拟牛顿法的思想

拟牛顿法的本质思想是改善牛顿法每次需要求解复杂的 Hessian 矩阵的逆矩阵的缺陷，它使用正定矩阵来近似 Hessian 矩阵的逆，从而简化了运算的复杂度。

### 常见的拟牛顿算法

1）DPF 方法；2）BFGS 方法；3）SR-1 方法。

##### 相关词：牛顿法，优化

### 参考来源：

【1】 https://zh.wikipedia.org/wiki/拟牛顿法

【2】 http://www.cnblogs.com/maybe2030/p/4751804.html

【3】 https://blog.csdn.net/fangqingan_java/article/details/47158115