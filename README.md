# 北京租金时间序列预测 — Prophet 模型

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Prophet](https://img.shields.io/badge/Prophet-Meta-green)

使用 Meta Prophet 模型预测北京租房市场未来 12 个月的价格走势。

## 📊 项目简介

- 42 个月北京平均租金历史数据（2023.01 — 2026.06）
- 使用 Facebook Prophet 时间序列模型进行预测
- 分解趋势、年度季节性和随机噪声三个成分
- 输出未来 12 个月预测值及置信区间

## 🛠 技术栈

`Python` `Pandas` `NumPy` `Prophet` `Matplotlib` `时间序列分析`

## 🔍 核心发现

- **长期趋势**：北京租金年均上涨约 200 元
- **季节性**：6-8 月毕业季租金最高，12-2 月春节最低
- **模型公式**：实际值 = 趋势 + 季节性 + 噪声

## ▶️ 运行方式

```bash
pip install prophet pandas matplotlib
jupyter notebook forecast.ipynb
```
