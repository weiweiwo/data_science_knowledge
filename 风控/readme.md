## 风控类
| 标题 | 相关内容|
| --- | --- |
|[反欺诈资料](https://github.com/safe-graph/graph-fraud-detection-papers)| 消费金融相关反欺诈论文模型|
|[评分卡case2](https://github.com/finlytics-hub/credit_risk_model)|对于case2的详细案例 |
|[optbinning](http://gnpalencia.org/optbinning/tutorials.html#optimal-binning-tutorials)|分类目标、连续目标的分箱记分卡模型整合工具|

model casel 1\
1、此处模型验证以1代表好客户，0代表坏客户\
2、分别对train与test数据集根据woe图进行分类与连续变量分箱\
3、分割出每个特征最低的woe值作为参考(不拉如模型计算)\
4、训练模型求得系数，同时检查P值，保留显著性的特征多的（小于0.05保留）\
5、再根据剩下特征进行训练模型，再预测test求得概率，转换成分数\
6、根据最大化tpr、最小化fpr,分割出 拒绝与通过的分数

model casel 2\
1、在训练模型之前，进行特征的显著性赛选，分类特征利用卡方检验Chi-squared，数值特征利用方差检验ANOVA F-Statistic\
2、其它同 case 1
