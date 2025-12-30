# 超级商店销售仪表盘

## 项目概述
基于 Kaggle 经典 Superstore 数据集的完整 Power BI 实践项目。  
数据包含订单、产品、客户、地区等多维度信息。

## 技术亮点
- **数据清洗（Power Query）**  
  处理缺失值、拆分地址列、创建日期表，自定义 M 函数等
- **数据建模**  
  星型模型，多表关系设置
- **DAX 关键度量值**  
  - 销售、利润、订单量  
  - 同比、环比、YTD 累计（DATEADD、DATESYTD 等）  
  - 动态 Top N 与贡献率（VAR + HASONEVALUE）  
  - 动态标题
- **交互设计**  
  多页面布局、同步切片器、钻取、书签、条件格式

## 仪表盘预览

![概览](screenshots/01_Overview.png)
![趋势](screenshots/02_Sales_Trend.png)
![利润分析](screenshots/03_Profit_Analysis.png)
![Top N](screenshots/04_TopN.png)

## 数据来源
原始数据集来自 Kaggle：  
[Sample - Superstore Sales Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)  

（本仓库不包含原始数据文件，可从上方链接直接下载）
