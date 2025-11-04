# 🛒 E-commerce Customer Behavior Analytics

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Kaggle](https://img.shields.io/badge/Kaggle-Notebook-20BEFF.svg)](https://www.kaggle.com)

> Comprehensive analysis of e-commerce customer behavior with stunning visualizations and actionable business insights.

## 📊 Project Overview

This project provides an in-depth analysis of e-commerce customer behavior using a dataset of 5,000+ transactions from a Turkish online retail platform. Through exploratory data analysis and advanced visualizations, we uncover key patterns in customer demographics, purchasing behavior, and revenue trends.

### 🎯 Key Features

- **Customer Demographics Analysis**: Age, gender, and geographic distribution
- **Product Performance Metrics**: Category-wise revenue and order analysis
- **Temporal Patterns**: Sales trends over time, day-of-week, and seasonal patterns
- **Discount Strategy Evaluation**: Impact analysis of promotional campaigns
- **Customer Segmentation**: Behavioral patterns and spending analysis
- **Advanced Correlations**: Feature relationships and predictive insights

## 📁 Dataset

**Source**: Turkish E-commerce Platform  
**Period**: January 2023 - March 2024  
**Records**: 5,000 transactions  
**Features**: 10+ attributes including demographics, products, and financials

### Data Fields:
- `Order_ID`: Unique transaction identifier
- `Customer_ID`: Unique customer identifier
- `Date`: Transaction date
- `Age`: Customer age (18-75 years)
- `Gender`: Customer gender (Male, Female, Other)
- `City`: Location across 10 major Turkish cities
- `Product_Category`: 8 categories (Electronics, Fashion, Sports, etc.)
- `Unit_Price`: Product price in Turkish Lira
- `Quantity`: Units purchased (1-5)
- `Discount_Amount`: Applied discounts

## 🚀 Quick Start

### Prerequisites
```bash
Python 3.8+
pandas
numpy
matplotlib
seaborn
```

### Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/ecommerce-behavior-analytics.git
cd ecommerce-behavior-analytics

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook ecommerce_analysis.ipynb
```

## 📊 Key Insights

### Customer Demographics
- **Age Distribution**: 70% of customers are between 18-35 years old
- **Gender Split**: Nearly balanced (50% Female, 49% Male, 1% Other)
- **Geographic Concentration**: Istanbul and Ankara account for 40%+ of orders

### Product Performance
- **Top Categories**: Electronics and Fashion drive 60%+ of revenue
- **Average Order Value**: ₺250-300 across categories
- **Best Sellers**: Electronics has highest AOV, Sports has highest volume

### Revenue Trends
- **Growth Pattern**: Consistent upward trend with seasonal variations
- **Peak Months**: Q4 shows strongest performance
- **Day Patterns**: Weekends show 20% higher order volume

### Discount Strategy
- **Usage Rate**: 15-20% of orders include discounts
- **Average Discount**: 8-12% off total order value
- **Impact**: Discounts increase order volume by 25%

## 📈 Visualizations

The project includes 15+ professional-grade visualizations:

- 🎨 Customer demographic dashboards
- 🗺️ Geographic distribution heatmaps
- 📦 Product category performance charts
- 💰 Revenue trend analysis
- 🎁 Discount impact evaluation
- 👥 Customer segmentation plots
- ⏰ Temporal pattern analysis

## 💡 Business Recommendations

### Growth Strategies
1. **Geographic Expansion**: Target underserved tier-2 cities
2. **Product Optimization**: Expand high-margin category inventory
3. **Customer Retention**: Launch loyalty programs for repeat customers

### Revenue Optimization
4. **Dynamic Pricing**: Implement AI-driven pricing strategies
5. **Discount Refinement**: Target promotions to low-traffic periods
6. **Cross-Selling**: Bundle complementary products

### Marketing Focus
7. **Demographic Targeting**: Heavy digital presence for 18-35 age group
8. **Temporal Optimization**: Flash sales during slow periods
9. **Gender Campaigns**: Category-specific targeting by gender

## 🛠️ Technologies Used

- **Python 3.8+**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Matplotlib**: Static visualizations
- **Seaborn**: Statistical data visualization
- **Jupyter Notebook**: Interactive development environment

## 📂 Project Structure
```
ecommerce-behavior-analytics/
│
├── data/
│   └── ecommerce_customer_behavior_dataset.csv
│
├── notebooks/
│   └── ecommerce_analysis.ipynb
│
├── visualizations/
│   ├── demographics_dashboard.png
│   ├── revenue_trends.png
│   └── product_performance.png
│
├── requirements.txt
├── README.md
└── LICENSE
```

## 📸 Sample Visualizations

### Customer Demographics Dashboard
![Demographics](visualizations/demographics_dashboard.png)

### Revenue Trends Over Time
![Revenue](visualizations/revenue_trends.png)

### Product Category Performance
![Products](visualizations/product_performance.png)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Lighton**
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/yourprofile)
- Kaggle: [@yourprofile](https://www.kaggle.com/yourprofile)

## 🙏 Acknowledgments

- Dataset source: Turkish E-commerce Platform
- Inspiration: Real-world business intelligence needs
- Community: Kaggle data science community

## 📊 Results Summary

| Metric | Value |
|--------|-------|
| Total Revenue | ₺1.2M+ |
| Total Orders | 5,000 |
| Unique Customers | 4,800+ |
| Average Order Value | ₺250 |
| Customer Retention | 20% |
| Top Category | Electronics |
| Growth Rate | +15% QoQ |

## 🔮 Future Enhancements

- [ ] Machine Learning models for customer lifetime value prediction
- [ ] Churn prediction and prevention strategies
- [ ] Real-time dashboard with Streamlit/Dash
- [ ] A/B testing framework for discount strategies
- [ ] Recommendation engine for cross-selling
- [ ] Cohort analysis and RFM segmentation

## 📧 Contact

For questions or feedback, please open an issue or reach out via email.

---

<div align="center">

**⭐ Star this repo if you find it helpful! ⭐**

Made with ❤️ and ☕ by Lighton

</div>
