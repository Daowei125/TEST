# 同策略 On Policy


**同策略**是指生成样本的策略跟网络更新参数时使用的策略相同。同策略方法的典型如 SARAS 算法。

同策略是基于当前的策略直接执行下一次动作选择，然后用这个样本更新策略，其生成样本的策略和学习时的策略相同。

### SARSA 算法

SARSA （State-Action-Reward-State-Action）是一个学习马尔可夫决策过程策略的算法，通常使用在机器学习领域的增强学习上。

- SARSA 算法的要点

1） 在状态 s' 时，就知道了要采取哪个 a' ，并真的采取了这个动作；

2） 动作 a 的选取遵循 e-greedy 策略，目标 Q 值的计算也是根据 e-greedy 策略得到的动作 a' 计算得来，因此是 on-policy 学习。

### 同策略的优缺点

优点：

1） 每一步都可以更新，这是显然，学习速度快；
 
2） 可以面对没有结果的场景，应用范围广。

缺点：

1） 会遭遇探索-利用的矛盾，只利用目前已知的最优选择，可能学不到最优解，收敛到局部最优，而加入探索又降低了学习效率。

### 同策略和异策略

与同策略相对应的是异策略，同策略和异策略的区别在于：更新 Q 值时，是沿用既定的策略还是使用新的策略。


### 参考来源

【1】  https://blog.csdn.net/weixin_37895339/article/details/74937023

【2】  http://www.voidcn.com/article/p-mjyycpfx-bpe.html
