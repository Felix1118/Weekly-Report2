# 工作总结

## 1）我做了什么
- **复现Spatio-Temporal Hypergraph Attention Networks for Brain Disease Analysis论文**

框架图:
  <img width="1742" height="603" alt="image" src="https://github.com/Felix1118/Weekly-Report2/blob/main/framework.png" />

  

## 2）存在的问题
- 复现结果较论文指标差距明显，需用表格搜索超参数方式，选取最佳超参数。
- 时空特征提取方式需改进

## 3）接下来要干啥
- **系统搜一波 DFBN 相关论文**。看他们怎么解决“**更有效提取时空拓扑特征**”这个问题（例如：时空耦合建模、拓扑演化、跨窗口依赖、高阶结构等方向）。
-  选几篇代表性工作，分析借鉴代码，参考他们提取时空拓扑特征的思路。
-  采用网格搜索方式，选取最佳超参数，将指标提上去。
