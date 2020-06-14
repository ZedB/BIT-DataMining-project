# BIT-DataMining-Project

北京理工大学2020年数据挖掘课程项目-算法1部分

## 选题名称：二手车交易价格预测（阿里天池比赛）

### 数据集
* [训练数据：data/train_data_v1.csv](https://github.com/Zening-Li/BIT_DataMining_project/tree/master/process_data)
* [测试数据：data/test_data_v1.csv](https://github.com/Zening-Li/BIT_DataMining_project/tree/master/process_data)
* [提交数据：output/submit.csv](./output)

### 算法1实现
* [algorithm1_linear_regression.ipynb](./algorithm1_linear_regression.ipynb)

### 说明
* 算法1使用的训练模型为线性回归模型，评测标准为MAE(Mean Absolute Error)
* 将数据集data/train_data_v1.csv中的数据拆分为训练集与测试集两部分，进行训练与评测
* 使用数据集data/test_data_v1.csv进行比赛结果预测
* 比赛预测结果按照指定格式生成output/submit.csv文件以便提交

