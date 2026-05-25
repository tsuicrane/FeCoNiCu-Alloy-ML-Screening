# 🚀 Fe-Co-Ni-Cu Alloy OER Electrocatalyst ML Screening

本项目致力于利用**材料信息学 (Materials Informatics)** 与机器学习技术，解决传统电解水 (OER) 催化剂研发中“试错法”成本高、周期长的问题。

## 📊 项目亮点 (Highlights)
* **海量数据清洗**：基于开源 DFT 数据库，自动化清洗并构建了包含 **470+** 条高价值吸附能数据的 Fe-Co-Ni-Cu 多主元合金数据集。
* **物理特征工程**：引入了原子电负性 (Electronegativity)、原子半径 (Radius) 及价电子数等关键先验物理描述符。
* **高精度模型预测**：采用 Random Forest 回归算法，$R^2$ 评分达到 **0.814**，平均绝对误差 (MAE) 仅为 **0.170 V**。
* **虚拟高通量筛选**：穷举全成分空间，成功筛选出理论过电位极低 (0.165V) 的潜在优质配方 (如 `Fe0.1Co0.1Ni0.1Cu0.7`)。

## 📁 核心文件说明
* `Ultimate_FeCoNiCu_Dataset.csv`: 经过特征清洗与合并的完整机器学习训练集。
* `FeCoNiCu_ML_Project_FactSheet.pdf`: 单页版项目技术简报（附详细指标与最佳配方 Top 5）。
* `*.ipynb`: 包含数据清洗、模型训练与虚拟筛选的完整可复现代码。

---
*Created by: [你的名字] - 探索数字化冶金与传统材料的结合*
