# 平滑 Smoothing

**平滑**是常用的一种数据处理方式。

在统计学和图像处理中，通过建立近似函数尝试抓住数据中的主要模式，去除噪音、结构细节或瞬时现象，来平滑一个数据集。

在平滑过程中，信号数据点被修改，由噪音产生的单独数据点被降低，低于毗邻数据点的点被提升，从而得到一个更平滑的信号。

### 平滑的方式

平滑可以两种重要形式用于数据分析：

一、若平滑的假设是合理的，可以从数据中获得更多信息；

二、提供灵活而且稳健的分析。有许多不同的算法可用于平滑。数据平滑通常通过最简单的密度估计或直方图完成。

### 平滑算法

最常用的一种算法是“移动平均”，通常被用于在重复的统计调查中捕获重要趋势。在图像处理和计算机视觉中，平滑被用于尺度空间的表示。 

最简单的平滑算法是“直角平滑”或“无加权滑动平均平滑”。 此方法用 m 个邻接点的平均值替换信号中的每个点， m 是称为“平滑宽度”的正整数，通常是奇数。三角平滑类似直角平滑，但实现了加权平滑函数。

### 平滑的具体应用

- Additive smoothing。
- Good-Turing estimate。
- Jelinek-Mercer smoothing ( interpolation )。
- Katz smoothing ( backoff )。
- Witten-Bell smoothing。
- Absolute discounting。
- Kneser - Ney smoothing。


### 参考来源

【1】  https://zh.wikipedia.org/wiki/平滑

【2】  https://ask.julyedu.com/question/175

【3】  http://www.shuang0420.com//2017/03/24/NLP%20笔记%20-%20平滑方法(Smoothing)小结/