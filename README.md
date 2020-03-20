# Boston-housing-forecast-sklearn-
Seven regression models were used to predict home prices in Boston
使用 scikit-learn（sklearn）机器学习包进行房价预测，sklearn 中已经内
置了波士顿房价数据集，在打乱后去 90%数据作为训练集，10%的数据作为测试集。分别利用
sklearn 提供的线性回归（Linear Regression）、岭回归（Ridge Regression）、鲁棒回归（使
用 Huber Regression）、支持向量回归（SVR）、最近邻回归（Nearest Neighbors Regression）、
决策树回归（Decision Trees）、神经网络回归（Neural Network Regression）共七种回归
算法实现对波士顿房价的预测。并对训练出的七种回归器进行性能评估，利用测试集计算七
种回归器的四项性能指标：解释方差（Explained Variance）、平均绝对误差（MAE，Mean
Absolute Error）、平均平方误差（MSE，Mean Squared Error）和中位绝对误差（MedAE，
Median Absolute Error）。
