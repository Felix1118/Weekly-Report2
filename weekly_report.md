# 工作总结

## 1）我做了什么
- **复现Spatio-Temporal Hypergraph Attention Networks for Brain Disease Analysis论文**

框架图:
  <img width="1742" height="603" alt="image" src="https://github.com/Felix1118/Weekly-Report2/blob/main/framework.png" />

## 2）存在的问题
- 复现结果较论文指标差距低了几个点，需用表格搜索超参数方式，选取最佳超参数。

## 3）接下来要干啥
-  对代码中的时空拓扑特征提取模块改进，目前想法是借用LSTM处理序列数据的思路，前一时刻输出影响后一时刻输入。
-  采用网格搜索方式，选取最佳超参数，将指标提上去。
