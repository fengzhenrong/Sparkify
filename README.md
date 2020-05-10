# Sparkify Project
Udacity项目：这是一个音乐服务数据集，项目里有个小型的数据集。该数据集记录艺术家，歌曲，时长，包括一些人口统计和地理数据，时间戳，性别，用户等级，用户操作记录信息（即具体操作如主页、升级、降级、播放歌曲、添加歌单，添加好友等）；这些数据很重要，可以数据中发现用户的喜好；本次项目的目的是预测用户的流失；本次项目通过一系列的数据分析，观察留存用户和流失用户的行为，寻找他们的共同特征，然后通过机器学习预测客户的流失；
[我的博客地址](https://www.jianshu.com/p/0e67747f2d14).

### 运行环境
Python3.7

PySpark 2.4.5

Jupyter notebook

### 依赖库
pandas

numpy

pyspark

matplotlib

seaborn

## 工程目录
Sparkify-zh.ipynb:ipynb格式文件，详细记录了数据集的处理，分析，特征工程和模型建立

Sparkify-zh.html:html格式文件，详细记录了数据集的处理，分析，特征工程和模型建立

## 分析流程
-数据探索

-定义客户流失

-建模

## 使用到的模型
-Logistic Regression

-Gradient Boosted Trees

-Support Vector Machine

-Random Forest

## 评价指标
Accuracy：准确率

F1 score：分数

## 结论
在这里我们使用F1 score作为指标，在训练中几个方法分数差别不大，可能数据量少的导致预测不是很准确，还有超参数调优是比较困难的，项目运行的时间较久；

对于哪一个模型更适用于本次项目，个人认为使用SupportVectorMachine(SVM)的模型比较好，时间上，分数都有不错的表现；

## 参考文献
[F1 score](https://en.wikipedia.org/wiki/F1_score).

[ROC 和 AUC](https://blog.csdn.net/otengyue/article/details/89426004).

[CrossValidator](https://spark.apache.org/docs/latest/ml-tuning.html).


### 最后，谢谢大家查看我的项目，如果大家有什么好的建议及有哪些可以改进的地方，可以提出来；谢谢！

