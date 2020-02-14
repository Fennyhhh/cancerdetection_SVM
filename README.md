# cancerdetection_SVM
## 项目简介
### 问题描述
二分类问题
###  数据描述
数据集来自美国威斯康星州的乳腺癌诊断数据集,医疗人员采集了患者乳腺肿块经过细针穿刺 (FNA) 后的数字化图像，并且对这些数字图像进行了特征提取，这些特征可以描述图像中的细胞核呈现。肿瘤可以分成良性和恶性。
![字段描述]()
mean 代表平均值，se 代表标准差，worst 代表最大值（3 个最大值的平均值）。每张图像都计算了相应的特征，得出了这 30 个特征值（不包括 ID 字段和分类标识结果字段 diagnosis），实际上是 10 个特征值（radius、texture、perimeter、area、smoothness、compactness、concavity、concave points、symmetry 和 fractal_dimension_mean）的 3 个维度，平均、标准差和最大值。这些特征值都保留了 4 位数字。字段中没有缺失的值。在 569 个患者中，一共有 357 个是良性，212 个是恶性。
### 方法
svm
## 安装
* 环境：python 3
* 相关库：
  * seaborn,matplotlib ———— 可视化，帮助我们分析特征
  * pandas————数据清洗
  * sklearn————数据挖掘
### 使用
运行det.py
### 声明
如有问题，请联系fennyh@csu.edu.cn
