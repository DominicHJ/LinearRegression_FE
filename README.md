## LinearRegression_FE

### 1 简介  
本项目主要对不同数据集进行特征工程，然后训练不同线性回归模型对数据进行拟合，最终用于预测。  
- **特征工程**  
  数据探索和数据预处理，具体包括各数据含义解析、数据可视化、数据归一化标准化、特征相关性探索、特征剔除、特征合并、缺失值处理、离群点检测等  
- **线性回归模型**  
  在处理好的数据集上建立线性回归模型，包括无正则的线性模型（缺省参数）、随机梯度下降模型、岭回归（L2正则）、Lasso（L1正则），以及对各模型超参数进行调优和分析  

### 2 工具包  
**数据处理工具包**  
- NumPy  
- SciPy  
- Pandas  
  
**数据可视化工具包**  
- Matplotlib  
- Seaborn  
  
**机器学习工具包**  
- Scikit Learn  

### 3 数据集介绍  
**Boston house price**  
该数据集来自UCI机器学习知识库。波士顿房屋这些数据于1978年开始统计，共506个数据点，涵盖了麻省波士顿不同郊区房屋13种特征和房价的信息，需要根据房屋特征预测房价信息。  

**Capital BikeShare**  
Capital Bikeshare是由美国Washington, D.C.的一个共享单车公司提供的自行车数据集，训练数据为2011年的数据，要求预测2012年每天的单车共享数量。  
原始数据集地址：http://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset  

**Ames House——Kaggle平台竞赛数据集**  
Ames房价预测是Kaggle平台上的一个竞赛任务，需要根据房屋的特征来预测亚美尼亚州洛瓦市（Ames，Lowa）的房价。其中房屋的特征x共有79维，响应值y为每个房屋的销售价格（SalePrice）。  
Kaggle官网上的任务说明： https://www.kaggle.com/c/house-prices-advanced-regression-techniques  
