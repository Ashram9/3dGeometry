# 3dGeometry
三维立体几何模型的构建和处理

**CW1**
- 半边网络数据结构的构建。
- ICP算法实现（点-点 & 点-面）两两点云配准。

**CW2**
- 计算并可视化三维模型的平均曲率(两种实现: uniform Laplace & un-uniform Discrete Laplace-Beltrami)与高斯曲率；
- 计算参数化模型的第一和第二基本形式；
- 模态分析(Model Analysis)和光谱网格(Spectral Mesh)重建：使用离散Laplace-Beltrami算子的最小k个特征向量执行光谱网格重建。
- 拉普拉斯网络平滑(显式&隐式算法实现)与去噪。

**CW3**
- 论文 "Simultaneous Registration of Multiple Corresponding Point Sets" 中的算法复现，可对多个点集进行同时配准。
- 引入四分位距（IQR）方法进行离群点检测；通过计算每个点上的法线向量为对应点对分配权重。
- 与标准ICP算法实验结果进行对比分析。
