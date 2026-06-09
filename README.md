# 项目名称
基于 Kaggle 数据集的建模任务（K折交叉验证 + Adam 优化器）

## 简介
本项目针对 Kaggle 竞赛数据集搭建模型，使用 PyTorch 实现深度学习训练，采用 **K 折交叉验证** 提升模型泛化能力，优化器选用 Adam。

## 环境依赖
```bash
pip install pandas numpy torch scikit-learn

数据集
数据来源：Kaggle 竞赛链接
训练集：train.csv
测试集：test.csv
运行方式
