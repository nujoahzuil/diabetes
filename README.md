# diabetes
多元统计分析课程作业存档

本文使用来自和鲸网站的电子健康记录公开数据集，对各指标进行因子分析并对血糖值进行预测，从而希望能够分析各指标之间的联系，并探究公共因子对血糖值的影响程度，尝试建立糖尿病预测模型。本文首先介绍了糖尿病的历史背景以及机器学习在糖尿病领域上的应用与发展；其次对数据进行了一系列预处理和统计描述，展现了变量的分布特点；之后基于数据的特点，进行基于主成分和最大方差旋转的因子分析，找到各指标的内在联系；最终对提取出的公共因子和因变量血糖值分别用线性回归、随机森林和XGBoost进行回归分析，找到影响血糖值的关键因素。研究结果表明，血脂、肝功能和肾功能指标是诊断糖尿病最关键的三个因素，可以根据这些指标在糖尿病诊断上进一步提高效率。
