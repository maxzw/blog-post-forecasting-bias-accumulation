# 📈 Small Bias, Big Problems: How Bias Emerges Through Aggregation

This repository contains code to create the results displayed in the blog post.

## 📦 Installation

1. Create a Python environment:
   ```bash
   conda create -n blogpost-bias python=3.12
   conda activate blogpost-bias
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 📁 Data Setup

1. Download the competition dataset from the [Kaggle competition page](https://www.kaggle.com/competitions/nexar-collision-prediction/data).
2. Place the downloaded ZIP file in the `data/` directory:
   ```
   data/
   └── nexar-collision-prediction.zip
   ```
3. Unzip the data:
   ```bash
   unzip data/nexar-collision-prediction.zip -d data/
   ```

## 🚀 Usage

Run `notebooks/example.ipynb` using the created python environment
