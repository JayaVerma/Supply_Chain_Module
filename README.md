# 📦 Supply Chain Intelligence Toolkit

This repository contains two essential modules for **data-driven decision-making in supply chain management**:

1. 📈 **Demand Forecasting using Adaptive Exponential Smoothing**  
2. 🚚 **Multi-Objective Transportation Optimization using Linear Programming**

These models are lightweight, interpretable, and ideal for educational purposes or as a foundation for larger supply chain analytics systems.

---

## 🧠 Module 1: Adaptive Demand Forecasting

### 📌 Description
Implements **adaptive exponential smoothing** for forecasting demand. Unlike traditional smoothing with fixed alpha, this model dynamically adjusts the smoothing factor based on recent forecast errors — making it more responsive to shifts in demand trends.

### ⚙️ Key Features
- Automatically adjusts smoothing factor (`alpha`)
- Handles noisy or volatile demand patterns
- Includes forecast error evaluation: **MAE**, **MSE**, and **MAPE**
- Visualization of forecast vs. actual demand

## 🚚 Module 2: Multi-Objective Transportation Optimization
### 📌 Description
Solves the classical transportation problem with a multi-objective linear programming model using PuLP. The objective is to minimize a weighted combination of transportation cost and delivery time, offering a realistic trade-off often faced in supply chain logistics.

### ⚙️ Key Features
- Uses linear programming via pulp
- Supports multiple sources and destinations
- User-defined weights for cost vs. time
- Output includes optimal shipping plan and total objective value
