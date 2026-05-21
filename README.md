# smart-water-projects

[![MIT License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

> 智慧水利开源项目集合 —— 水文预测 · 洪水模拟 · 水资源管理 · 大坝安全 · 水质监测

---

## 项目模块

| 模块 | 说明 | 独立仓库 |
|------|------|----------|
| `flood_forecasting/` | 洪水预测：LSTM/GRU 时序建模、降雨-径流分析 | [smart-water-demo](https://github.com/LY-muyanshiqi/smart-water-demo) |
| `dam_safety/` | 大坝安全：监测数据分析、异常检测、安全评估 | — |
| `water_resources/` | 水资源管理：水库调度、供需平衡分析 | — |
| `water_quality/` | 水质监测：水质指标分析、趋势预测 | — |
| `common_libs/` | 公共库：数据处理、可视化工具函数 | — |

> 具体实现代码分布在对应的独立仓库中。本仓库用于统一索引和跨项目共享模块。

## 相关项目

- [smart-water-demo](https://github.com/LY-muyanshiqi/smart-water-demo) — 洪水预警演示系统（完整实现）
- [PCCP](https://github.com/LY-muyanshiqi/PCCP) — PCCP-E 环向变形智能预测
- [thermal-peak-shaving-pumped-storage](https://github.com/LY-muyanshiqi/thermal-peak-shaving-pumped-storage) — 抽水蓄能减碳优化
