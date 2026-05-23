# smart-water-projects

[![MIT License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

> 智慧水利开源项目集合 —— 水文预测 · 洪水模拟 · 水资源管理 · 大坝安全 · 水质监测

---

## 项目总览

| 项目 | 类型 | 核心技术 | 核心指标 | CI/CD |
|------|------|----------|----------|-------|
| [PCCP](https://github.com/LY-muyanshiqi/PCCP) | 科研 | Inception-ResNet-LSTM | R²=0.986 | ✅ |
| [smart-water-demo](https://github.com/LY-muyanshiqi/smart-water-demo) | 技术 | LSTM/GRU + Flask + Streamlit | 洪水预警系统 | ✅ |
| [thermal-peak-shaving](https://github.com/LY-muyanshiqi/thermal-peak-shaving-pumped-storage) | 科研 | NSLDE 多目标优化 | 火电调峰优化 | ✅✅ |
| [pumped-storage-carbon](https://github.com/LY-muyanshiqi/pumped-storage-carbon) | 竞赛 | LSTM + 峰谷电价调度 | 碳减排核算 | ✅ |
| [huazhong-cup-vrp](https://github.com/LY-muyanshiqi/huazhong-cup-vrp) | 竞赛 | Hybrid-ILS 迭代局部搜索 | 278页论文 | ✅ |
| [statistical-modeling-corn](https://github.com/LY-muyanshiqi/statistical-modeling-corn) | 竞赛 | LSTM+CNN+XGBoost | R²=0.82 | — |
| [badao-weiyi](https://github.com/LY-muyanshiqi/badao-weiyi) | 竞赛 | 18种AI算法库 | 92%精度 | — |
| [blog-files](https://github.com/LY-muyanshiqi/blog-files) | 博客 | Markdown 存档 | CSDN 文章 | — |
| [LY-muyanshiqi](https://github.com/LY-muyanshiqi/LY-muyanshiqi) | Profile | GitHub 个人首页 | — | — |

> ✅ = 基础 CI &nbsp;&nbsp; ✅✅ = 完整 CI (测试+部署)

---

## 按主题分类

### 水利工程
- **PCCP** — 管道结构环向变形预测 + 断丝角度计算
- **badao-weiyi** — 大坝安全智能诊断

### 水文预测
- **smart-water-demo** — 洪水预警 (LSTM/GRU)
- **pumped-storage-carbon** — 来水预测 + 抽蓄调度

### 能源优化
- **thermal-peak-shaving** — 火电调峰 + 抽蓄协同 (NSLDE)
- **pumped-storage-carbon** — 碳减排效益核算

### 数学建模
- **huazhong-cup-vrp** — 城市绿色物流 VRP
- **statistical-modeling-corn** — 遥感玉米产量预测

---

## 模块规划

| 模块 | 说明 | 对应仓库 |
|------|------|----------|
| `flood_forecasting/` | 洪水预测：LSTM/GRU 时序建模 | smart-water-demo |
| `dam_safety/` | 大坝安全：监测分析、异常检测 | badao-weiyi |
| `water_resources/` | 水资源管理：水库调度 | pumped-storage-carbon |
| `water_quality/` | 水质监测：趋势预测 | (待开发) |
| `common_libs/` | 公共库：数据处理、可视化工具 | (待提取) |

---

## 作者

**李垚** — 西安理工大学水利水电工程专业 · AI+智慧水利方向

[![GitHub](https://img.shields.io/badge/GitHub-LY--muyanshiqi-181717?style=flat-square&logo=github)](https://github.com/LY-muyanshiqi)
