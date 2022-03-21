## 基于机器学习的心脏疾病预测

### 成员

- 宋策 （3220211062）
- 王国宇（3220211071）
- 吴凌云（3220211085）
- 曹鑫杰（3220210985）
 
### 问题描述

#### 1、问题背景及分析

<br/>

心脏病是人类健康的头号杀手，全世界1/3的人口死亡是心脏病引起的。而我国每年有几十万人死于心脏病。如果可以通过提取人体相关的体测指标，通过数据挖掘的方式来分析不同特征对于心脏病的影响，这将对心脏病预防起到至关重要的作用。

本次项目基于数据挖掘课程所学知识，根据疾病的特征组合来预测心脏病发生的概率。


<br/>

#### 2、问题描述
<br/>


2.1 数据准备

<br/>

选题来自于kaggle，[数据集地址-Heart Attack Analysis & Prediction Dataset](https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset)

<br/>

数据集中给定训练数据为13维，示例值如下表所示：

|Age|Sex|cp|trtbps|chol|fbs|restecg|thalachh|exng|oldpeak|slp|caa|thall|
|---|---|---|---|---|---|---|---|---|---|---|---|---|
|63|1|3|145|233|1|0|150|0|2.3|0|0|1|

<br/>

数据解释如下：


- Age：病人的年龄
- Sex：病人的性别
- exang：是否由运动引起心绞痛
- ca：血管容量
- cp：心脏疼痛类型
- trtbps：舒缓血压（单位为mm Hg）
- chol：通过BMI传感器检测到的类固醇含量
- fbs：运动血糖含量是否高于120 mg/dl
- rest_ecg：休息心电图结果
- thalach：最高心率

<br/>

输出标签为1代表很可能患心脏病，标签为0代表健康

<br/>

2.2 准备采用的方法或模型

<br/>

本次课程项目利用数据集中给定的训练数据划分训练集和测试集，测试不同模型以及集成模型在数据集上的分类效果，通过评价指标选取最优模型进行分类。

<br/>

2.3 预期的挖掘结果

<br/>

$$\text{AUC}\ge0.9$$

<br/>

### 项目评估

$$\text{True Positive Rate}=\frac{TP}{TP+FN}$$
$$\text{False Positive Rate}=\frac{FP}{FP+TN}$$

通过结合真阳率和假阳率，可以得到ROC曲线，ROC曲线进行积分即AUC分数

<br/>

### 项目分工

<br/>

- 宋策：数据处理、模型搭建
- 王国宇：数据分析、模型调整
- 吴凌云：
- 曹鑫杰：

<br/>

### 项目代码仓库地址

<br/>

[https://github.com/yuhaishenedc/DataMining](https://github.com/yuhaishenedc/DataMining)





