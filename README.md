# 项目名称： 基于可解释人工智能的机器学习糖尿病预测框架

作者： 李熙蕊 (Li Xirui)

指导老师： Dr. Ifede Parfait T ebe

摘要：

本项目旨在开发一个基于机器学习的糖尿病预测框架，该框架集成了两个基础模型和一个可解释人工智能 (XAI) 技术，以提高预测性能并增强预测结果的可解释性。该框架使用 stacking 方法将 CatBoost 和 XGBoost 两个基础模型结合，并使用 Logistic Regression 作为元分类器。SHAP 被用作 XAI 技术，以提供对预测结果的解释。

### 主要成果：

提高预测性能： 集成模型在测试集上实现了 88.93% 的准确率，优于所有基础模型，证明了其在处理复杂医疗数据集方面的有效性。
增强可解释性： SHAP 分析揭示了 HbA1c 水平和血糖水平是影响糖尿病风险的最关键特征，其次是年龄和 BMI。这为医疗保健专业人员和患者提供了对预测结果的理解，并增强了 AI 在医疗领域的可信度。

### 数据集：

本项目使用了来自 Kaggle 的公开糖尿病数据集，包含 100,000 个样本和 8 个特征：

性别
年龄
高血压
心脏病
吸烟史
BMI
HbA1c 水平
血糖水平
技术栈：

 编程语言：Python (3.9.19)
 开发环境：Visual Studio Code
 库：Pandas, Scikit-learn, Imblearn, Matplotlib, Seaborn, Joblib, Shap
##文件结构：
3069898(CSCU9Z7)_2024-25 Final Dissertation.docx： 本项目的最终论文，包含研究背景、方法、结果和讨论等内容。
### 运行环境：
操作系统：Windows 11
处理器：Intel Core i9
内存：至少 16GB
### 运行步骤：
安装所需的 Python 库：pip install pandas scikit-learn imblearn matplotlib seaborn joblib shap
导入数据集并执行预处理步骤。
训练基础模型和集成模型。
使用测试集评估模型的性能。
使用 SHAP 进行可解释性分析。
### 未来工作：

探索贝叶斯优化等高级技术进行超参数调优，以避免过拟合并提高模型性能。
进一步调整正则化参数，以在保持模型泛化的同时受益于超参数调优。
应用“提前停止”等技术，以增强模型稳定性。
### 联系方式：

如果您有任何问题或建议，请联系作者 Li Xirui
