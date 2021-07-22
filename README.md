# data_science

jupyter notebook在线打开[jupyter notebook online open](https://nbviewer.jupyter.org/)
## 资料类
| 标题 | 相关内容|
| --- | --- |
|[算法文档](http://www.huaxiaozhuan.com/) | 机器学习、深度学习、数学基础文档|
|[ML-foundation](https://github.com/jonkrohn/ML-foundations)| 使用python进行数学知识验证 |
|[动手深度学习](https://d2l.ai/)|在线阅读《动手深度学习》与社区讨论|

模型度量 36



## 风控类
| 标题 | 相关内容|
| --- | --- |
|[反欺诈资料](https://github.com/safe-graph/graph-fraud-detection-papers)| 消费金融相关反欺诈论文模型|

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


## 可视化类
| 标题 | 相关内容|
| --- | --- |
|[可视化描述](https://datavizcatalogue.com/ZH/index.html)| 对各种可视化应用场景的解释与概述|


## 工具
|标题 |相关内容|
|---|---|
|[online epub](https://www.ofoct.com/viewer/epub-reader-online.html)| 在线打开epub |
|[github文档](https://docs.github.com/cn/github/writing-on-github/basic-writing-and-formatting-syntax#headings)|github在线使用手册|
|[pymysql](https://www.cnblogs.com/liwenzhou/p/8032238.html)|pymysql数据库操作文档|
|[AppliedAi](https://github.com/jessxphil/AppliedAiCourse-AssignmentAndNotes)|所有笔记|
