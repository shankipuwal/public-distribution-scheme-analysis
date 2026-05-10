# Public Distribution Scheme Analysis

Analyzing transaction volume, quantity movement, and AAY share trends to understand scheme performance across years and states.

## 📋 Project Overview

This project provides comprehensive analysis of India's Public Distribution System (PDS) using data from the NITI Aayog National Data Analytics Platform (NDAP). The analysis focuses on understanding scheme performance, identifying trends, and providing actionable insights across different states and time periods.

## 🎯 Objectives

- **Transaction Volume Analysis**: Track transaction patterns and trends over time
- **Quantity Movement Tracking**: Monitor commodity movement and distribution efficiency
- **AAY Share Analysis**: Analyze Antyodaya Anna Yojana (AAY) penetration and impact
- **State-wise Performance**: Comparative analysis across different states
- **Temporal Trends**: Year-over-year performance evaluation and forecasting

## 📊 Key Features

- **Interactive Power BI Dashboards**: Real-time visualization and exploration of PDS data
- **Multi-dimensional Analysis**: Analysis across states, schemes, and time periods
- **Ration Card Portability Insights**: Deep dive into portability trends and impact
- **Data-driven Insights**: Comprehensive analysis supporting policy decisions

## 📁 Repository Structure

```
public-distribution-scheme-analysis/
├── README.md                                    # This file
├── 7118_source_data.csv                        # Primary transaction data
├── 7118_KEYS.csv                               # Data mapping and keys
├── Ration Card Portability.csv                 # Portability analysis dataset
├── Ration Card Portability Dashboard.pbix      # Main Power BI dashboard
├── Public_Distribution_Power_Bi_Project_Report.docx  # Detailed project report
├── Data Modeling-03.png                        # Data model architecture
├── Overview Page-01.png                        # Dashboard overview screenshot
└── Scheme and Movement Analysis Page-03.png    # Detailed analysis dashboard
```

## 📊 Data Source

**Official Source**: [NITI Aayog National Data Analytics Platform (NDAP)](https://ndap.niti.gov.in)

- **Dataset ID**: 7118
- **Dataset Link**: [https://ndap.niti.gov.in/dataset/7118](https://ndap.niti.gov.in/dataset/7118)
- **Data Owner**: Ministry of Consumer Affairs, Government of India
- **Update Frequency**: Quarterly

## 📈 Data Files Documentation

### 1. **7118_source_data.csv** (226 KB)
Primary transaction-level data containing:
- Transaction records across states
- Commodity details (wheat, rice, etc.)
- Quantity distributed
- AAY and non-AAY beneficiaries
- Temporal data (year, month, quarter)

### 2. **7118_KEYS.csv** (683 KB)
Data dictionary and key mappings:
- Column descriptions and definitions
- State and district codes
- Scheme codes and categorization
- Data validation rules

### 3. **Ration Card Portability.csv** (206 KB)
Specialized dataset tracking:
- Ration card portability across states
- Beneficiary movement patterns
- State-to-state transaction flows
- Portability effectiveness metrics

## 📊 Power BI Dashboards

### Ration Card Portability Dashboard (`Ration Card Portability Dashboard.pbix`)

**Key Visualizations:**
- State-wise portability trends
- Inter-state beneficiary movement
- Transaction success rates
- AAY scheme adoption across states
- Temporal trend analysis

**Interactive Features:**
- State-level filtering
- Date range selection
- Drill-down capabilities
- Real-time metric updates

## 🖼️ Dashboard Visualizations Included

1. **Data Modeling Diagram** (`Data Modeling-03.png`)
   - Entity-relationship overview
   - Data structure and relationships
   - Key dimensions and hierarchies

2. **Overview Page** (`Overview Page-01.png`)
   - High-level KPIs and metrics
   - Overall scheme performance
   - Key statistics and summary cards

3. **Scheme and Movement Analysis Page** (`Scheme and Movement Analysis Page-03.png`)
   - Detailed commodity movement patterns
   - Scheme-wise breakdowns
   - Transaction volume trends

## 🔍 Analysis Dimensions

### 1. **Geographic Dimension**
- State-level analysis
- District-level granularity
- Inter-state portability flows

### 2. **Scheme Dimension**
- AAY (Antyodaya Anna Yojana)
- Non-AAY beneficiaries
- Priority Household (PH) scheme
- Comparative performance analysis

### 3. **Temporal Dimension**
- Year-over-year trends
- Quarterly performance patterns
- Monthly granularity for detailed analysis

### 4. **Commodity Dimension**
- Wheat distribution
- Rice distribution
- Other commodities
- Commodity mix optimization

## 🛠️ Tools & Technologies

- **Data Source**: NITI Aayog NDAP (https://ndap.niti.gov.in)
- **BI Tool**: Microsoft Power BI
- **Data Format**: CSV
- **Analysis Tools**: Power BI Desktop
- **Version Control**: Git/GitHub

## 📊 Key Metrics & KPIs

- **Total Transactions**: Overall PDS transaction volume
- **Commodity Quantity**: Total grain distributed
- **AAY Beneficiaries**: Number of AAY scheme participants
- **Portability Rate**: Cross-state beneficiary movement
- **Distribution Efficiency**: Transaction success and completion rates
- **State Coverage**: Geographic spread and adoption

## 💡 Use Cases

1. **Policy Making**: Data-driven policy formulation for PDS improvements
2. **Performance Benchmarking**: State-wise comparative analysis
3. **Efficiency Monitoring**: Identify bottlenecks in distribution
4. **Beneficiary Insights**: Understanding AAY scheme impact
5. **Inter-state Coordination**: Optimizing portability mechanisms

## 🚀 Getting Started

### Prerequisites
- Microsoft Power BI Desktop (for viewing `.pbix` files)
- CSV viewer or spreadsheet application (Excel, Google Sheets)
- Internet access for NDAP portal

### Steps
1. Clone this repository
2. Download the `.pbix` files to view dashboards
3. Review CSV files for raw data analysis
4. Refer to the project report for detailed insights
5. Access original data from [NDAP Portal](https://ndap.niti.gov.in/dataset/7118)

## 📊 Key Findings Summary

This analysis provides insights into:
- Transaction efficiency improvements needed
- State performance variations
- AAY scheme effectiveness
- Portability impact and adoption
- Regional disparities in distribution

## 📄 Documentation

**Detailed Analysis Report**: See `Public_Distribution_Power_Bi_Project_Report.docx` for comprehensive findings and recommendations.

## 🔗 Related Resources

- [NITI Aayog Official Website](https://niti.gov.in)
- [National Data Analytics Platform](https://ndap.niti.gov.in)
- [Public Distribution System - Ministry of Consumer Affairs](https://consumeraffairs.gov.in)
- [Antyodaya Anna Yojana - Official Info](https://consumeraffairs.gov.in/pages/schemes.html)

## 🤝 Contributing

Contributions are welcome! Please feel free to:
- Fork the repository
- Create a feature branch
- Submit pull requests with improvements
- Report issues or suggestions

## 📝 License

This project uses publicly available data from NITI Aayog NDAP. Please refer to the NDAP terms of use and attribution requirements.

## 👤 Author

**Shanki Puwal**
- GitHub: [@shankipuwal](https://github.com/shankipuwal)
- Repository: [public-distribution-scheme-analysis](https://github.com/shankipuwal/public-distribution-scheme-analysis)

## 📧 Support

For questions or suggestions:
- Open an issue on GitHub
- Visit [NITI Aayog NDAP](https://ndap.niti.gov.in) for data support
- Check [Ministry of Consumer Affairs](https://consumeraffairs.gov.in) for PDS information

## 📅 Last Updated

May 2026

---

**Data Source Attribution**: All data sourced from [NITI Aayog National Data Analytics Platform - Dataset 7118](https://ndap.niti.gov.in/dataset/7118)

© 2026 Shanki Puwal. All rights reserved.
