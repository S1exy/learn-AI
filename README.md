# west2-online AI考核指南

这里是西二在线工作室人工智能方向的考核指南，旨在为初学者提供一个循序渐进的人工智能学习路线。

## 版权

本项目遵循GPL-3.0 License，转载请注明本项目仓库地址。

## 概览
人工智能方向的考核现在细分为计算机视觉和自然语言处理两个方向。

基础阶段主要培养各位的Python编程能力，并针对性地考核图表、爬虫、数据预处理等与人工智能有关的方面。  
基础阶段的前两轮考核与python后端组一起，第三轮mnist数据集是人工智能入门。

进阶阶段会根据各位的意愿分流为计算机视觉（CV）和自然语言处理（NLP）两个细分方向，提供从易到难层层递进的、项目驱动式的考核任务。

各位在通过所有考核后方可成为西二在线网络工作室的正式成员，均会发放实习证明和成员证书，可使用工作室内的资源组队参与相关的算法比赛，~~或者来玩无人机~~ 同时还有外包、实习等福利。
### 基础

| 阶段 | 学习内容               | 预期时长 | 提交形式       |
| ---- | ---------------------- | -------- | -------------- |
| 1    | Python基础语法         | 一个月      | 代码         |
| 2    | 爬虫                   | 一个月      | 代码         |
| 3    | mnist数据集            | 一个月      | 代码+学习笔记 |

### 进阶
#### 计算机视觉
| 阶段 | 学习内容            | 预期时长 | 提交形式      |
| ---- | ------------------- | -------- | ------------- |
| 1    | CIFAR100数据集      | 3周      | 代码+学习笔记 |
| 2    | 验证码自动识别      | 2周      | 代码+吹逼大会 |
| 3    | 仿写YOLO            | 4周      | 代码+学习笔记 |
| 4    | 图像分割            | 待定     | 代码+学习笔记 |
| 5    | Vit网络及其迁移应用 | 待定     | 代码+吹逼大会 |
#### 自然语言处理
| 阶段 | 学习内容                | 预期时长 | 提交形式      |
| ---- | ----------------------- | -------- | ------------- |
| 1    | IMDB数据集（LSTM、Cov） | 2周      | 代码+学习笔记 |
| 2    | 自制transformer完成MLM  | 1个月    | 代码+吹逼大会 |
| 3    | 预训练模型benchmark     | 4周      | 代码+吹逼大会 |
| 4    | 小说续写Finetune        | 3周      | 代码+吹逼大会 |
| 5    | 语义相似度及推荐算法    | 待定     | 代码+吹逼大会 |
| 6    | 问答模型Finetune        | 待定     | 代码+吹逼大会 |

## 考核设计
考核的主要方法是要求各位在某一数据集上训练出具有一定精度的人工智能模型，为防止走捷径套用网上现成代码，需要各位在进阶阶段的考核末期提交有内容的学习笔记或参与吹逼大会展示和剖析自己的模型。根据任务的不同考核往往会限制模型的参数数量，以便各位在自己的机器上进行训练，到需要强大算力的后几期考核时，工作室会为各位提供一定金额的算力补助以便各位租用GPU服务器进行训练。
