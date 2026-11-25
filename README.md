<p align="center"><strong>简体中文</strong> · <a href="README.en.md">English</a></p>

<h1 align="center">你好，我是 ChengYu 👋</h1>

<p align="center"><strong>AI Agent 开发 · 大模型评估 · 心理咨询对话研究</strong></p>

---

### 🧭 关于我

我在学习怎么让 AI 帮人完成更多步骤，也在研究大模型如何处理心理咨询对话。我关心两个问题：让 Agent 查资料、用工具时，怎么检查它做得对不对？一句咨询回应有没有准确复述对方的意思，模型内部又有没有相应的信号？

目前关注 **Agent 工具调用、检索与效果评估**。在模型研究中，我用稀疏自编码器（SAE）分析大模型的内部激活，寻找与反映式倾听相关的候选特征。

### 🚀 公开项目

| 项目 | 做了什么 |
| :--- | :--- |
| **[反映式倾听特征评估](https://github.com/ChengYu117/yanzheng)** | 比较 Llama 3.1 8B 处理有无反映式倾听的咨询话语时的内部激活，筛选候选 SAE 特征。我在项目中校正了 SAE 推理的归一化与反归一化，并加入了因果评估实验。 |
| **[图像与掩码同步增强](https://github.com/ChengYu117/shuju)** | 给语义分割样本做翻转、旋转和形变时，对原图和标注掩码同步应用几何变换，让增强后的图片和标注仍然对齐。 |

### 🛠️ 项目技术栈

- **模型与评估** · `Python` · `PyTorch` · `Hugging Face Transformers` · `scikit-learn`
- **图像处理** · `OpenCV` · `Albumentations` · `NumPy`

<p align="center"><a href="https://github.com/ChengYu117?tab=repositories">查看全部仓库 →</a></p>
