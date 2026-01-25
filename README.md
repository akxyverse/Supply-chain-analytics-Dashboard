# 📊 Supply Chain Analytics System

A comprehensive data analytics system for analyzing supply chain delivery performance, agent efficiency, and operational insights using Python and interactive dashboards.

![Python](https://img.shields.io/badge/Python-3.9+-blue?style=flat-square&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-1.28-red?style=flat-square&logo=streamlit)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## 🎯 Overview

This project analyzes **43,739 delivery orders** to provide actionable insights on:
- Delivery performance across vehicles, weather, and traffic conditions
- Agent performance and demographics
- Geographic distribution and time-based patterns
- Operational bottlenecks and optimization opportunities

---

## ✨ Key Features

### 📊 **Comprehensive Analytics**
- Delivery performance analysis
- Agent rating and demographics
- Weather and traffic impact assessment
- Geographic and temporal patterns

### 📈 **30+ Visualizations**
- High-quality PNG charts
- Interactive dashboard
- Delivery time distributions
- Performance comparisons
- Heatmaps and trend analysis

### 🎨 **Interactive Dashboard**
- Real-time filtering (area, vehicle, weather, traffic)
- Dynamic KPI metrics
- Multiple analysis views
- Pre-generated visualizations gallery

---

## 🛠️ Technologies Used

- **Python 3.9+** - Core programming language
- **Pandas & NumPy** - Data manipulation
- **Matplotlib & Seaborn** - Visualizations
- **Streamlit** - Interactive dashboard
- **VS Code** - Development environment

---

## 📁 Project Structure
```
supply-chain-analytics-system/
├── data/
│   ├── raw/                    # Original dataset
│   └── processed/              # Cleaned data
├── scripts/
│   ├── analytics/              # Analysis scripts
│   └── visualizations/         # Chart generation
├── reports/
│   └── visualizations/         # Generated charts
├── app.py                      # Dashboard application
├── requirements.txt            # Dependencies
└── README.md                   # Documentation
```

---

## 🚀 Quick Start

### Installation
```bash
# Clone repository
git clone https://github.com/akxyverse/supply-chain-analytics-system.git
cd supply-chain-analytics-system

# Install dependencies
pip install -r requirements.txt
```

### Usage

**1. Data Cleaning**
```bash
python scripts/clean_data.py
```

**2. Run Analytics**
```bash
python scripts/delivery_analytics.py
python scripts/agent_analytics.py
python scripts/geographic_time_analytics.py
```

**3. Generate Visualizations**
```bash
python scripts/visualizations/delivery_visualizations.py
python scripts/visualizations/agent_visualizations.py
python scripts/visualizations/geographic_time_visualizations.py
```

**4. Launch Dashboard**
```bash
streamlit run app.py
```

---

## 📊 Key Insights

### 🚗 Vehicle Performance
- **Bicycle**: Fastest for short distances (95 min avg)
- **Van**: Best for long distances (130 min avg)
- **Motorcycle**: Balanced performance (120 min avg)

### 🌤️ Weather Impact
- **Sunny**: Optimal (110 min avg)
- **Stormy**: 35% slower (150 min avg)
- **Fog**: 25% slower (140 min avg)

### 🚦 Traffic Analysis
- **Low Traffic**: 85 min average
- **High Traffic**: 145 min average
- **Jam**: 180+ min (60% slower)

### 👥 Agent Insights
- High-rated agents (≥4.5): 15% faster
- Optimal age: 26-35 years
- Rating correlates with efficiency

---

## 📸 Dashboard Preview

Interactive dashboard features:
- **KPI Metrics**: Orders, delivery time, ratings, coverage
- **Filters**: Area, vehicle, weather, traffic
- **Tabs**: Delivery, agent, geographic analysis
- **Visualizations**: 30+ pre-generated charts

---

## 📝 Data Source

- **Dataset**: Amazon Delivery Data
- **Source**: Kaggle
- **Records**: 43,739 orders
- **Features**: 16 columns (order details, agent info, location, timing, weather, traffic)

---

## 🔮 Future Enhancements

- [ ] Predictive delivery time models
- [ ] Route optimization algorithms
- [ ] Real-time data integration
- [ ] Mobile app version
- [ ] API for external integrations

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Akash Yadav**

---

## 🙏 Acknowledgments

- Kaggle for dataset
- Streamlit community
- Python data science ecosystem

---

**⭐ Star this repo if you find it useful!**
