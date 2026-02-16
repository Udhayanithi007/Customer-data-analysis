# 🛍️ Customer Data Analysis - Shopping Mall Analytics

<img width="960" height="480" alt="image" src="https://github.com/user-attachments/assets/370e1ed1-53e7-4ffa-a9f8-705ba1e8f716" />


![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-02569B?style=for-the-badge&logo=databricks&logoColor=white)

## 📊 Project Overview

This project presents a comprehensive analysis of customer shopping behavior across multiple shopping malls in Istanbul, Turkey. The dataset contains **98,749 transactions** spanning from 2021 to 2023, providing valuable insights into customer demographics, purchasing patterns, and revenue trends.

As a Data Analyst, I've utilized Power BI to create interactive dashboards that visualize key business metrics and customer behavior patterns to support data-driven decision-making.

## 🎯 Key Findings

### 💰 Revenue Insights
- **Total Revenue Generated**: $68.05 Million
- **Average Transaction Value**: $689.12
- **Time Period**: January 2021 - February 2023

### 🛍️ Category Performance

| Category | Transactions | Revenue | % of Total |
|----------|--------------|---------|------------|
| **Clothing** | 34,236 (34.7%) | $30.84M | 45.3% |
| **Shoes** | 9,963 (10.1%) | $18.01M | 26.5% |
| **Technology** | 4,959 (5.0%) | $15.66M | 23.0% |
| **Cosmetics** | 14,994 (15.2%) | $1.84M | 2.7% |
| **Toys** | 10,017 (10.1%) | $1.08M | 1.6% |

**Key Insight**: While Clothing dominates transaction volume, Technology and Shoes contribute disproportionately high revenue due to premium pricing.

### 👥 Customer Demographics

#### Gender Distribution
- **Female Customers**: 59,071 (59.8%)
- **Male Customers**: 39,678 (40.2%)

Female customers represent the majority of shoppers, indicating targeted marketing opportunities.

#### Age Analysis
- **Average Customer Age**: 43.4 years
- **Age Range**: 18-69 years

**Age Group Breakdown**:
```
18-25 years: 15.4%
26-35 years: 19.2%
36-45 years: 19.6% (Largest segment)
46-55 years: 19.1%
56-65 years: 19.1%
65+ years:   7.6%
```

**Key Insight**: The customer base is evenly distributed across middle age groups (26-65), with strong representation from the 36-45 demographic.

### 💳 Payment Methods

| Payment Type | Transactions | Percentage |
|--------------|--------------|------------|
| Cash | 44,127 | 44.7% |
| Credit Card | 34,662 | 35.1% |
| Debit Card | 19,960 | 20.2% |

**Key Insight**: Cash remains the most popular payment method, though digital payments (Credit + Debit) collectively account for 55.3% of transactions.

### 🏢 Shopping Mall Performance

**Top 5 Shopping Destinations**:

1. **Mall of Istanbul** - 19,805 transactions (20.1%)
2. **Kanyon** - 19,709 transactions (20.0%)
3. **Metrocity** - 14,901 transactions (15.1%)
4. **Metropol AVM** - 10,085 transactions (10.2%)
5. **Istinye Park** - 9,702 transactions (9.8%)

**Key Insight**: Mall of Istanbul and Kanyon dominate market share with nearly identical transaction volumes, collectively capturing 40% of all shopping activity.

## 📁 Repository Contents

```
Customer-data-analysis/
│
├── customer_data.pbix           # Power BI Dashboard (Main Analysis)
├── CUSTOMER_DATA_.json          # Raw dataset (98,749 transactions)
├── README.md                    # Project documentation
└── visualizations/              # (Optional) Dashboard screenshots
```

## 🔍 Analysis Methodology

1. **Data Collection**: Transaction data from 10 major shopping malls in Istanbul
2. **Data Processing**: Cleaned and structured 98,749 customer transactions
3. **Visualization**: Created interactive Power BI dashboards
4. **Insights Extraction**: Analyzed patterns in demographics, purchasing behavior, and revenue

## 📊 Dashboard Features

The Power BI dashboard includes:

- **Revenue Overview**: Total revenue, average transaction value, trends over time
- **Category Analysis**: Sales and revenue breakdown by product category
- **Customer Demographics**: Age and gender distribution analysis
- **Payment Methods**: Preferred payment channel analysis
- **Mall Performance**: Comparative analysis of shopping mall traffic
- **Temporal Trends**: Monthly and yearly sales patterns
- **Interactive Filters**: Dynamic filtering by date, category, mall, and demographics

## 🛠️ Tools & Technologies

- **Power BI Desktop** - Data visualization and dashboard creation
- **Python** - Data preprocessing and analysis
- **CSV/JSON** - Data storage and exchange format
- **Git** - Version control

## 📈 Business Recommendations

Based on the analysis:

1. **Focus on High-Value Categories**: Technology and Shoes offer the highest revenue per transaction - consider expanding these categories
2. **Target Female Demographics**: With 60% of customers being female, tailor marketing campaigns accordingly
3. **Optimize Payment Infrastructure**: Despite digital payment growth, maintain robust cash handling systems
4. **Peak Mall Strategy**: Prioritize resources at Mall of Istanbul and Kanyon during peak hours
5. **Age-Specific Marketing**: Develop targeted campaigns for the 36-45 age group (largest segment)

## 🚀 Getting Started

### Prerequisites
- Power BI Desktop ([Download here](https://powerbi.microsoft.com/desktop/))
- Windows 10 or later

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Udhayanithi007/Customer-data-analysis.git
cd Customer-data-analysis
```

2. Open the Power BI file:
```bash
# Double-click customer_data.pbix or open with Power BI Desktop
```

3. Refresh data (if needed):
- Navigate to **Home** → **Refresh**

## 📊 Data Schema

The dataset includes the following fields:

| Field | Type | Description |
|-------|------|-------------|
| invoice_no | String | Unique transaction identifier |
| customer_id | String | Unique customer identifier |
| gender | String | Customer gender (Male/Female) |
| age | Integer | Customer age (18-69) |
| category | String | Product category |
| quantity | Integer | Number of items purchased |
| price | Float | Total transaction amount |
| payment_method | String | Payment type used |
| invoice_date | Date | Transaction date |
| shopping_mall | String | Mall location |

## 🎓 Skills Demonstrated

- Data Analysis & Visualization
- Power BI Dashboard Development
- Statistical Analysis
- Business Intelligence
- Customer Segmentation
- Data Storytelling
- Revenue Analysis

## 📸 Dashboard Previews

*Screenshots of the Power BI dashboard would be included here*

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/Udhayanithi007/Customer-data-analysis/issues).

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💼 About the Analyst

**Data Analyst** | Passionate about transforming data into actionable insights

- **GitHub**: [@Udhayanithi007](https://github.com/Udhayanithi007)
- **LinkedIn**: [Connect with me](https://www.linkedin.com/in/udhayanithi007)

## 📧 Contact

For questions or collaboration opportunities:
- Open an issue on GitHub
- Email: your.email@example.com

## 🌟 Acknowledgments

- Shopping mall data providers
- Power BI community for visualization inspiration
- All contributors and data enthusiasts

---

**⭐ If you find this project useful, please consider giving it a star!**

*Last Updated: February 2026*
