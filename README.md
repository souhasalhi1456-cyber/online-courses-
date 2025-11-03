# online-courses-
Project Overview
This project analyzes an online courses dataset from Kaggle to identify e-learning market trends and course performance metrics. The analysis includes data cleaning, interactive dashboard creation, and strategic insights generation.
## 📁 File Structure
project/

│
├── Cleaning and Preparing the Kaggle Online Courses Dataset.ipynb

├── Online_Courses_Cleaned.csv

├── online courses dashboard.pbix

└── rapport vf.pdf

## 📋 Files Description

### 1. Data Cleaning Script
**File**: `Cleaning and Preparing the Kaggle Online Courses Dataset.ipynb`

**Purpose**: Python script for comprehensive data cleaning and preprocessing

**Features**:
- Handles missing values using median (numeric) and mode (categorical) imputation
- Converts data types and standardizes formats
- Extracts key attributes for analysis
- Removes completely empty columns
- Prepares data for Power BI visualization

**Technologies**: Python, Pandas, NumPy

### 2. Cleaned Dataset
**File**: `Online_Courses_Cleaned.csv`

**Purpose**: Processed dataset ready for analysis

**Dataset Details**:
- **Records**: 8,092 courses
- **Columns**: 8 key attributes
- **Quality**: 0 missing values, optimized data types

**Key Columns**:
- `Title`, `Category`, `Rating`, `Price`
- `Duration`, `Skills`, `Number of viewers`, `Instructors`

### 3. Interactive Dashboard
**File**: `online courses dashboard.pbix`

**Purpose**: Power BI dashboard for interactive data exploration

**Dashboard Pages**:
- **Main Dashboard**: Overview with KPIs and category analysis
- **Detailed Analysis**: Correlation studies and trend identification
- **Skills Analysis**: Market demand and skills distribution

**Visualizations**:
- KPI cards (Total courses, Average rating, Median price, etc.)
- Top 10 categories by course count and rating
- Price vs Rating scatter plots
- Duration analysis charts
- Instructor performance metrics
- Skills popularity treemaps

**Interactive Features**:
- Category filters
- Price range selectors
- Rating sliders
- Duration controls
- Skills multi-select

### 4. Analysis Report
**File**: `rapport vf.pdf`

**Purpose**: Comprehensive report with business insights and recommendations

**Report Sections**:
- Executive summary
- Methodology description
- Key findings and insights
- Strategic recommendations
- Technical implementation details

## 🎯 Key Insights

### Market Trends
- **Data Science Dominance**: 65% of top-rated courses belong to Data Science category
- **Price-Quality Correlation**: No strong correlation between course price and rating
- **Duration Preference**: Shorter courses (2-4 months) show higher engagement

### Performance Metrics
- **Average Rating**: 4.7/5 across all courses
- **Median Price**: $855 per course
- **Free Courses**: Only 2% of courses are completely free

### Skills Analysis
- **High Demand**: Python, Machine Learning, Data Analysis
- **Emerging Trends**: AI, Deep Learning, Cloud Computing

## 🛠️ Technical Requirements

### Software
- Python 3.8+
- Jupyter Notebook
- Power BI Desktop
- Pandas, NumPy libraries

### Data Sources
- Primary: Kaggle Online Courses Dataset
- Processed: Cleaned dataset with enhanced features

## 🚀 Quick Start

1. **Explore Data**: Open `Online_Courses_Cleaned.csv` in your preferred tool
2. **Run Analysis**: Execute the Jupyter notebook to understand data cleaning process
3. **View Dashboard**: Open `online courses dashboard.pbix` in Power BI Desktop
4. **Read Insights**: Review `rapport vf.pdf` for strategic findings

## 📊 Metrics Overview

| Metric | Value | Description |
|--------|-------|-------------|
| Total Courses | 8,092 | Number of courses analyzed |
| Average Rating | 4.7/5 | Overall course quality score |
| Median Price | $855 | Middle price point |
| Average Duration | 5 months | Typical course length |
| Free Courses | 2% | Percentage of no-cost courses |

## 👥 Target Audience

- **Product Managers**: Course development and pricing strategies
- **Content Strategists**: Market trend identification and content planning
- **Data Analysts**: Methodology reference and analysis techniques
- **Business Leaders**: Strategic decision-making insights

## 📈 Business Applications

- **Market Analysis**: Understand e-learning landscape and competition
- **Product Development**: Identify high-demand skills and categories
- **Pricing Strategy**: Optimize course pricing based on market data
- **Content Strategy**: Focus on trending topics and skills

## 🔧 Customization

The project can be extended by:
- Adding new data sources
- Creating additional visualizations
- Implementing predictive analytics
- Integrating with real-time data feeds
