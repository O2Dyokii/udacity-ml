# Udacity-MLND

Projects for udacity machine learning nanodegree  
优达学城机器学习进阶项目

### [Project0](https://github.com/jameszhou89/udacity-ml/blob/master/Project0-James/titanic_survival_exploration.ipynb)    
泰坦尼克号生还者分析  
创建简单的决策树分类器，并根据泰坦尼克号海难的乘客特征，如：性别、年龄等，对乘客生还结果进行预测，并使得准确率在80%以上。

### [Project1](https://github.com/jameszhou89/udacity-ml/blob/master/Project1-James/boston_housing.ipynb)  
预测房价    
对波士顿地区的房价数据集使用 Python的NumPy 和 Scikit-Learn等库，预测新房屋的销售价格。
- 利用K-Fold,Gridsearch等方法选取机器学习模型的不同参数；
- 分析机器学习算法的性能图表，考察不同模型在不同参数下的variance和accuracy
- 选取最优模型,其在测试集的R^2达到0.84。

### [Project2](https://github.com/jameszhou89/udacity-ml/blob/master/Project2/finding_donors.ipynb)    
为慈善机构寻找捐助者  
为硅谷慈善机构CharityML构建一个高效筛选潜在捐款者的机器学习算法，以降低发送广告邮件的成本。
- 利用归一化、独热编码等方法对数据进行预处理；
- 分别训练高斯朴素贝叶斯、SVM、集成学习等监督学习模型，筛选出最优的机器学习模型（集成学习，F-score=0.7645）；
- 对高斯朴素贝叶斯、SVM、集成学习这三个不同模型的优劣和特色进行讨论；
- 利用Sklearn的feature_importance_评估不同特征的重要性。

### [Project3](https://github.com/jameszhou89/udacity-ml/blob/master/Project3/customer_segments.ipynb)  
创建客户细分  
分析葡萄牙里斯本的一家批发经销商的数据，找出数据背后的客户群体。  
- 应用预处理技术进行特征相关性分析、异常值检测以及特征缩放；
- 使用主成分分析（PCA）来对批发商客户数据进行降维分析；
- 使用高斯混合模型聚类算法（EM）来发现数据中隐藏的客户分类，发现了客户群主要分为餐饮用户和超市用户两大类，与实际情况吻合。

### [Project4](https://github.com/jameszhou89/udacity-ml/blob/master/Project4/smartcab.ipynb)  
训练智能车学会驾驶   
运用强化学习技术让一个自动驾驶智能车在一个简化的世界中，并且在有限时间内高效地抵达目的地。
- 通过分析安全性和可靠性两项指标，来确定这个智能车的状态空间（state）,同时还需要考虑状态空间的状态总数（计算量）以进行优化；
- 使用Q-Learning算法，训练人工智能体，使它能够对周围环境做出最佳选择；
- 改进探索因子的衰减函数和学习率，以及其他参数，使得智能车在安全性和可靠性上获得都是A+的评分；
- 探讨未来奖励gmma在此问题上没有效果的原因（主要考虑到该交通问题并非一个MDP问题）。




### 更新记录  
版本号  1.1       更新时间 2018/1/31       更新内容： 增加了每个项目的简单说明,并添加了链接    
