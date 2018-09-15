# 真负类 True Negative

**真负类**（ TN ）是指二分类问题中被正确判断为负类的那些样本。


对于二分类问题，可将样例根据其真实类别与学习器预测类别的组合划分为真正类（ true positive ）、假正类（ false positive ）、真负类（ true negative ）、假负类（ false negative ）四种情形。

![](混淆矩阵.png)

分类结果的混淆矩阵如上：其中的 true、false 是指判断结果正确与否；positive、negative ：判断为正类还是负类。

显然 TP + FP + TN + FN = 样本总数。

TN 是本来是负类，被正确的判定为负类的样本。


##### 相关词： 假真类，真正类，假反类，ROC 曲线，AUC 曲线。

### 参考来源

【1】 http://bealin.github.io/2017/02/27/机器学习系列—2-模型评估与选择/
