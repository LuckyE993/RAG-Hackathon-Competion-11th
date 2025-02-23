# NVIDIA 第11届 Sky Hackathon大赛 芝士雪豹队代码仓库

# 部署教程

本文档说明如何部署并运行该项目。

## 前置条件
- 已安装 Git、Anaconda/Miniconda
- 项目使用 Python 3.11（通过 my_env.yaml 提供环境）

## 部署步骤

1. **克隆仓库**  
   在终端中运行以下命令：
   ```bash
   git clone https://github.com/LuckyE993/RAG-Hackathon-Competion-11th
   cd RAG-Hackathon-Competion-11th
   ```

2. **创建 Conda 环境**  
   使用项目根目录下的环境文件创建环境：
   ```bash
   conda env create -f my_env.yaml
   ```

3. **激活环境**  
   ```bash
   conda activate RAG-Proj
   ```

4. **运行项目**  
   项目包含 Jupyter Notebook 和 Gradio 接口：
   - 若通过 Notebook 进行探索：
     ```bash
     jupyter notebook
     ```
   - 若启动 Gradio Web 应用（如已将最后一部分代码保存为 app.py）：
     ```bash
     python app.py
     ```
     请根据实际文件名替换 `app.py`。

5. **使用说明**  
   - **Article Understanding Tab**：上传 PDF 并提问了解文章内容  
   - **Podcast Generate Tab**：上传 PDF 后生成播客文稿和音频  
   - **Chart & Table Description Tab**：上传图表图片并生成分析范文

## 其他说明
- 请确保配置文件中涉及的路径正确无误  
- 如有需要，可根据部署环境调整启动命令
