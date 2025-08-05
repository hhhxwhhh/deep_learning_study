时间序列预测学习路线
1. 基础阶段
数学基础
统计学基础：均值、方差、协方差、相关系数等
概率论基础：概率分布、条件概率、贝叶斯定理
线性代数：矩阵运算、特征值和特征向量
微积分基础：导数、偏导数、梯度
编程基础
从您现有的文件看，您已经掌握了：

Python基础语法
PyTorch张量操作
数据处理（pandas）
建议补充：

NumPy数组操作
Matplotlib/Seaborn数据可视化
时间序列数据处理
2. 时间序列分析基础
理论知识
时间序列基本概念（趋势、季节性、周期性、噪声）
平稳性检验（ADF检验、KPSS检验）
自相关和偏自相关函数
白噪声检验
经典方法
移动平均法（MA）
指数平滑法（Exponential Smoothing）
ARIMA模型（自回归积分滑动平均模型）
季节性分解（STL分解）
3. 机器学习方法
特征工程
滞后特征（Lag Features）
滚动窗口统计特征（Rolling Window Statistics）
时间相关特征（节假日、季节等）
传统机器学习模型
线性回归
支持向量机（SVM）
随机森林
XGBoost/LightGBM
4. 深度学习方法
循环神经网络（RNN）
基础RNN
LSTM（长短期记忆网络）
GRU（门控循环单元）
注意力机制和Transformer
Seq2Seq模型
Attention机制
Transformer架构
图神经网络（可选）
GCN（图卷积网络）
GAT（图注意力网络）
5. 实践项目
初级项目
股票价格预测
销售额预测
天气预测
中级项目
多变量时间序列预测
多步预测
异常检测
高级项目
大规模时间序列预测
实时预测系统
不规则时间序列处理
6. 工具和框架
Python库
statsmodels（经典统计方法）
scikit-learn（机器学习）
PyTorch（深度学习）
TensorFlow/Keras（深度学习）
Prophet（Facebook开源工具）
评估指标
MAE（平均绝对误差）
MSE（均方误差）
RMSE（均方根误差）
MAPE（平均绝对百分比误差）
7. 学习建议
循序渐进：先掌握经典统计方法，再学习机器学习和深度学习方法
理论结合实践：每个阶段都要动手实践，通过项目巩固知识
关注领域知识：不同领域的时间序列有其特定规律，需要结合领域知识
持续学习：时间序列预测是一个活跃的研究领域，需要持续关注最新进展
8. 学习资源推荐
书籍：
《时间序列分析》（James D. Hamilton）
《Forecasting: principles and practice》（Rob J Hyndman）
在线课程：
Coursera上的时间序列分析课程
Udacity的机器学习纳米学位
开源项目：
Facebook Prophet
Amazon's DeepAR
Google's Temporal Fusion Transformer