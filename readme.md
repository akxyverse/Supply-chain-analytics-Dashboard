# 📊 Supply Chain Analytics System

A comprehensive data analytics system for analyzing supply chain delivery performance, agent efficiency, and operational insights using Python and interactive dashboards.

![Dashboard Preview](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.9+-blue?style=for-the-badge&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-1.28-red?style=for-the-badge&logo=streamlit)

---

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Analytics Insights](#analytics-insights)
- [Dashboard Preview](#dashboard-preview)
- [Future Enhancements](#future-enhancements)

---

## 🎯 Overview

This project analyzes **43,739 delivery orders** from Amazon delivery data to provide actionable insights on:
- Delivery performance across different vehicles, weather conditions, and traffic scenarios
- Agent performance and demographics
- Geographic distribution and time-based patterns
- Operational bottlenecks and optimization opportunities

**Key Achievement:** Identified that traffic conditions cause up to 45% variation in delivery times, enabling data-driven route optimization strategies.

---

## ✨ Features

### 📊 **Data Analytics**
- Comprehensive delivery performance analysis
- Agent rating and age demographic analysis
- Weather and traffic impact assessment
- Geographic and temporal pattern discovery

### 📈 **30+ Visualizations**
- High-quality PNG charts for reports
- Delivery time distributions and comparisons
- Agent performance metrics
- Hourly and daily pattern analysis
- Weather-traffic impact heatmaps

### 🎨 **Interactive Dashboard**
- Real-time data filtering by area, vehicle, weather, and traffic
- Dynamic KPI metrics
- Interactive charts and graphs
- Multiple analysis views (Delivery, Agent, Geographic)
- Gallery of all pre-generated visualizations

### 🔍 **Key Insights**
- Vehicle efficiency comparison
- Weather impact quantification
- Peak hours identification
- Agent performance correlations
- Geographic distribution patterns

---

## 🛠️ Technologies Used

### **Core Technologies:**
- **Python 3.9+** - Primary programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations

### **Visualization:**
- **Matplotlib** - Static visualization creation
- **Seaborn** - Statistical data visualization
- **Streamlit** - Interactive web dashboard

### **Development Tools:**
- **VS Code** - Code editor
- **Git** - Version control
- **Jupyter Notebooks** - Exploratory analysis

---

## 📁 Project Structure
```
AI-SUPPLY-CHAIN-ANALYTICS/
│
├── data/
│   ├── raw/
│   │   └── amazon_delivery.csv          # Original dataset
│   └── processed/
│       └── cleaned_data.csv             # Cleaned dataset
│
├── scripts/
│   ├── explore_data.py                  # Initial data exploration
│   ├── clean_data.py                    # Data cleaning pipeline
│   ├── delivery_analytics.py           # Delivery performance analysis
│   ├── agent_analytics.py               # Agent performance analysis
│   ├── geographic_time_analytics.py     # Geographic & time analysis
│   │
│   └── visualizations/
│       ├── delivery_visualizations.py   # Delivery charts generation
│       ├── agent_visualizations.py      # Agent charts generation
│       └── geographic_time_visualizations.py  # Geographic charts
│
├── reports/
│   └── visualizations/
│       ├── delivery_performance/        # 8 delivery charts
│       ├── agent_performance/           # 7 agent charts
│       └── geographic_time_analysis/    # 8 geographic charts
│
├── app.py                               # Streamlit dashboard application
├── requirements.txt                     # Python dependencies
└── README.md                            # Project documentation
```

---

## 🚀 Installation

### **Prerequisites:**
- Python 3.9 or higher
- pip (Python package manager)

### **Step 1: Clone Repository**
```bash
git clone <repository-url>
cd AI-SUPPLY-CHAIN-ANALYTICS
```

### **Step 2: Create Virtual Environment (Optional)**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### **Step 3: Install Dependencies**
```bash
pip install -r requirements.txt
```

---

## 💻 Usage

### **1. Data Exploration**
```bash
python scripts/explore_data.py
```
View basic dataset statistics and structure.

### **2. Data Cleaning**
```bash
python scripts/clean_data.py
```
Clean and preprocess the raw data.

### **3. Run Analytics**
```bash
# Delivery performance analysis
python scripts/delivery_analytics.py

# Agent performance analysis
python scripts/agent_analytics.py

# Geographic and time analysis
python scripts/geographic_time_analytics.py
```

### **4. Generate Visualizations**
```bash
# Generate delivery performance charts
python scripts/visualizations/delivery_visualizations.py

# Generate agent performance charts
python scripts/visualizations/agent_visualizations.py

# Generate geographic analysis charts
python scripts/visualizations/geographic_time_visualizations.py
```

### **5. Launch Interactive Dashboard**
```bash
streamlit run app.py
```
Open browser to `http://localhost:8501`

---

## 📊 Analytics Insights

### **Key Findings:**

#### 🚗 **Vehicle Performance**
- **Bicycle**: Fastest for short distances (avg: 95 min)
- **Van**: Best for long distances (avg: 130 min)
- **Motorcycle**: Balanced performance (avg: 120 min)

#### 🌤️ **Weather Impact**
- **Sunny**: Optimal conditions (avg: 110 min)
- **Stormy**: 35% longer delivery times (avg: 150 min)
- **Fog**: 25% increase in delays (avg: 140 min)

#### 🚦 **Traffic Conditions**
- **Low Traffic**: 85 min average
- **High Traffic**: 145 min average
- **Jam**: 180+ min (60% slower)

#### 👥 **Agent Performance**
- **High-rated agents (≥4.5)**: 15% faster deliveries
- **Optimal age range**: 26-35 years
- **Experience matters**: Rating correlates with efficiency

#### ⏰ **Peak Hours**
- **Busiest**: 12 PM - 2 PM
- **Slowest**: 8 PM - 10 PM
- **Optimal**: 6 AM - 8 AM

---

## 🖼️ Dashboard Preview

### **Interactive Filters**
- Area selection
- Vehicle type filter
- Weather condition filter
- Traffic condition filter

### **KPI Metrics**
- Total Orders
- Average Delivery Time
- Average Agent Rating
- Coverage Areas
- Product Categories

### **Analysis Tabs**
1. **Delivery Performance**: Vehicle comparison, weather impact, time distribution
2. **Agent Analytics**: Rating distribution, age demographics, performance correlation
3. **Geographic Analysis**: Area distribution, category preferences, hourly patterns
4. **Visualizations Gallery**: All 30+ pre-generated charts

---

## 🔮 Future Enhancements

### **Potential Improvements:**
- [ ] Real-time data integration
- [ ] Predictive delivery time models (Machine Learning)
- [ ] Route optimization algorithms
- [ ] Customer satisfaction analysis
- [ ] Cost-benefit analysis
- [ ] Mobile app version
- [ ] API for external integrations
- [ ] Automated reporting via email

### **Advanced Features:**
- [ ] Prophet/ARIMA for time series forecasting
- [ ] Clustering analysis for delivery zones
- [ ] A/B testing framework for operational changes
- [ ] Integration with Google Maps API
- [ ] Real-time tracking dashboard

---

## 📝 Data Source

**Dataset**: Amazon Delivery Data  
**Source**: Kaggle  
**Records**: 43,739 delivery orders  
**Features**: 16 columns including order details, agent info, locations, timing, weather, and traffic conditions

---

## 👨‍💻 Author

**Akash Yadav**  
*Data Analytics Project*

---

## 📄 License

This project is for educational purposes.

---

## 🙏 Acknowledgments

- Kaggle for providing the dataset
- Streamlit community for dashboard framework
- Python data science community
- Open-source contributors

---

## 📞 Contact

For questions or collaboration:
- **Email**: akashyadav110502@gmail.com
- **LinkedIn**:https://www.linkedin.com/in/akash-yadav-122a75288/
- **GitHub**:https://github.com/akxyverse

---

**⭐ If you find this project useful, please consider giving it a star!**