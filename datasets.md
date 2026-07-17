# OpenQuality 相关数据集清单

本文件整理与 OpenQuality“大质量”主题相关的公开数据集，覆盖工业质量、制造质量、缺陷检测、半导体良率分析、设备健康监测与故障诊断等方向。

## 数据集总览

| 序号 | 数据集名称 | 数据类型 | 质量主题 | 适合任务 | 简介 | 链接 |
|---|---|---|---|---|---|---|
| 1 | SECOM | 表格数据 | 半导体制造质量 | 质量预测、二分类、特征选择 | 来自半导体制造过程，包含大量工艺与传感器特征，标签表示产品是否合格，适合质量预测和高维特征分析。 | https://archive.ics.uci.edu/dataset/179/secom |
| 2 | Steel Plates Faults | 表格数据 | 钢板表面质量 | 缺陷分类、多分类 | 包含钢板缺陷相关统计特征和缺陷类别，适合传统机器学习方法进行质量缺陷分类。 | https://archive.ics.uci.edu/dataset/198/steel%2Bplates%2Bfaults |
| 3 | Bosch Production Line Performance | 表格数据 | 生产线质量预测 | 故障预测、异常检测、二分类 | 来自 Bosch 生产线的多工位测量数据，用于预测产品是否会出现内部失效，是制造质量大数据的典型案例。 | https://www.kaggle.com/c/bosch-production-line-performance |
| 4 | MVTec AD | 图像数据 | 工业视觉质量检测 | 异常检测、缺陷定位、图像分割 | 工业异常检测经典数据集，包含多类工业物体和纹理图像，提供正常样本、异常样本和像素级标注。 | https://www.mvtec.com/company/research/datasets/mvtec-ad |
| 5 | VisA | 图像数据 | 工业异常检测 | 缺陷检测、异常定位 | 包含多个真实工业对象类别，可用于视觉异常检测、缺陷定位和少样本工业检测研究。 | https://github.com/amazon-research/spot-diff |
| 6 | Real-IAD | 图像数据 | 真实工业异常检测 | 异常检测、多视角检测 | 大规模真实工业异常检测数据集，覆盖多个工业对象类别，适合更接近实际场景的视觉质量检测研究。 | https://github.com/Real-IAD/Real-IAD |
| 7 | NEU Surface Defect / NEU-DET | 图像数据 | 钢材表面质量 | 缺陷检测、图像分类 | 面向热轧钢带表面缺陷检测，包含多类典型钢材缺陷，如划痕、夹杂、斑块等。 | https://github.com/Charmve/Surface-Defect-Detection/tree/master/NEU-DET |
| 8 | Severstal Steel Defect Detection | 图像数据 | 钢铁表面质量 | 缺陷分割、图像检测 | Kaggle 钢铁表面缺陷检测竞赛数据，常用于工业缺陷分割和钢材质量检测研究。 | https://www.kaggle.com/c/severstal-steel-defect-detection |
| 9 | KolektorSDD | 图像数据 | 表面缺陷检测 | 小样本缺陷分割 | 来自真实工业场景的表面缺陷数据集，适合研究小样本工业缺陷检测与分割方法。 | https://www.vicos.si/resources/kolektorsdd/ |
| 10 | DeepPCB | 图像数据 | PCB 制造质量 | PCB 缺陷检测 | PCB 缺陷检测数据集，包含模板图、测试图和多类缺陷标注，适合电子制造质量检测研究。 | https://github.com/tangsanli5201/DeepPCB |
| 11 | WM-811K | 晶圆图数据 | 半导体良率分析 | 晶圆缺陷模式识别 | 常用于晶圆缺陷图谱识别、半导体良率分析和制造过程异常模式挖掘。 | https://www.kaggle.com/datasets/qingyi/wm811k-wafer-map |
| 12 | NASA C-MAPSS | 时间序列数据 | 设备健康与可靠性 | 剩余寿命预测、故障预测 | 航空发动机退化仿真数据集，常用于设备健康管理、可靠性分析和预测性维护研究。 | https://data.nasa.gov/dataset/C-MAPSS-Aircraft-Engine-Simulator-Data/xaut-bemq |
Add OpenQuality dataset list
