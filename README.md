# Fusion-CNN-multi-CNN-for-feature-extraction-and-psosvm-for-fault-diagnosis-
python代码，西储大学滚动轴承故障诊断，可以参考我的博客
https://blog.csdn.net/qq_41043389/article/details/103870271
1.利用融合CNN进行特征提取
本文将2D-CNN与1D-CNN融合，同时对轴承数据集进行训练，然后在汇聚层将两者池化层的输出连接成一个向量，送进全连接层。模型训练结束之后，取FC层的输出作为提取到的故障特征信号。数据来源，西储大学滚动轴承故障诊断数据集。
2，利用svm进行分类
最终训练集准确率98.14%，验证集99%，测试集98%。
目前应该还没有人用这个方法发过论文哦，详情可以看我上面的csdn博客了解，或者加我qq2919218574咨询,代码是收费的哦
