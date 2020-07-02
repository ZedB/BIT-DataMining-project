# BIT-DataMining-Project

北京理工大学2020年数据挖掘课程项目-算法1部分

## 选题名称：二手车交易价格预测（阿里天池比赛）

### 数据集
* [训练数据：data/train_data_v1.csv](https://github.com/Zening-Li/BIT_DataMining_project/tree/master/process_data)
* [测试数据：data/test_data_v1.csv](https://github.com/Zening-Li/BIT_DataMining_project/tree/master/process_data)
* [提交数据（2020.7.2已更新）：output/submit.csv](./output)

### 算法1（2020.7.2已更新）
* [algorithm1_linear_regression.ipynb](./algorithm1_final.ipynb)

### 说明（2020.7.2已更新）
* 将数据集data/train_data_v1.csv中的数据拆分为训练集与测试集两部分，以便进行多模型的训练与评测比较
* 使用数据集data/test_data_v1.csv进行比赛结果预测
* 算法1使用了5种算法，分别对经过划分的数据集进行训练，并使用评测标准MAE(Mean Absolute Error)比较模型结果
* 最终根据5种算法训练的模型，选出最优的算法，在原始数据集上进行训练与预测，得出比赛预测结果
* 比赛预测结果按照指定格式生成output/submit.csv文件以便提交
