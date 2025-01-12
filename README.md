# 基于华为昇腾Mindspore框架的CIFAR10图像分类实验

### Intro
本实验为<span style="color:#006600ff">SYSU ECE</span>电子专业必修课：<em>ECE372模式识别与人工智能</em>课程作业，仅作**存档和参考**使用。
本实验利用了[华为云ModelArts](https://github.com/huaweicloudDocs/modelarts)平台上Notebook搭建实验环境,实验目的为改进网络使得测试集准确度尽可能高，本方案采用对ResNet进行改造，并采用预训练模型进行finetune的两种方案。采用预训练模型的方案测试集最高准确率达97.6%

### 实验环境
- Mindspore 1.7.0
- Python 3.7.10
- Ubantu 18.04
- Cuda 10.1
- GPU: Tesla P100 16G (Aka Pnt) 实验兼容其他GPU以及Ascend GPU

---
