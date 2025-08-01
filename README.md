# Health Care Analysis Project

## 📋 Project Overview

This project contains a comprehensive healthcare dataset analysis with 10,000 patient records spanning from October 2018 to October 2023. The project includes both raw data in CSV format and a Power BI dashboard for interactive visualization and analysis.

## 📊 Dataset Information

### Data Source
- **File**: `Health Care Analysis.csv`
- **Records**: 10,000 patient admissions
- **Time Period**: October 30, 2018 - October 30, 2023 (5 years)
- **File Size**: ~1.4MB

### Data Schema

| Column | Description | Data Type | Sample Values |
|--------|-------------|-----------|---------------|
| Name | Patient full name | String | Tiffany Ramirez, Ruben Burns |
| Age | Patient age at admission | Integer | 18-85 (Avg: 51.5) |
| Gender | Patient gender | String | Male, Female |
| Blood Type | Patient blood type | String | A-, A+, O-, O+ |
| Medical Condition | Primary diagnosis | String | Arthritis, Asthma, Hypertension, Obesity |
| Date of Admission | Admission date | Date | 2018-10-30 to 2023-10-30 |
| Doctor | Attending physician | String | Patrick Parker, Diane Jackson |
| Hospital | Healthcare facility | String | Wallace-Hamilton, Burke, Griffin and Cooper |
| Insurance Provider | Insurance company | String | Medicare, Aetna, UnitedHealthcare, Blue Cross, Cigna |
| Billing Amount | Total charges | Decimal | $1,000 - $50,000 (Avg: $25,517) |
| Room Number | Patient room | Integer | 108-500 |
| Admission Type | Admission category | String | Elective, Emergency, Urgent |
| Discharge Date | Patient discharge date | Date | Various |
| Medication | Prescribed medication | String | Aspirin, Paracetamol, Penicillin |
| Test Results | Laboratory results | String | Normal, Abnormal, Inconclusive |

## 📈 Key Insights

### Patient Demographics
- **Age Range**: 18-85 years
- **Average Age**: 51.5 years
- **Gender Distribution**: Male and Female patients
- **Blood Types**: A-, A+, O-, O+ (4 types represented)

### Medical Conditions
The dataset covers 4 primary medical conditions:
1. **Arthritis** - Joint inflammation and pain
2. **Asthma** - Respiratory condition
3. **Hypertension** - High blood pressure
4. **Obesity** - Weight-related health issues

### Healthcare System Analysis
- **Insurance Providers**: 5 major providers (Medicare, Aetna, UnitedHealthcare, Blue Cross, Cigna)
- **Admission Types**: Elective, Emergency, and Urgent care
- **Billing Range**: $1,000 - $50,000 per admission
- **Average Billing**: $25,517 per admission

### Medications
Three primary medications are prescribed:
- **Aspirin** - Pain relief and blood thinning
- **Paracetamol** - Fever and pain relief
- **Penicillin** - Antibiotic treatment

## 🎯 Power BI Dashboard

### File Information
- **File**: `Health Care Analysis.pbix`
- **Size**: 1.4MB
- **Last Modified**: February 3, 2025

### Dashboard Features
The Power BI dashboard provides interactive visualizations including:
- Patient demographics analysis
- Medical condition distribution
- Insurance provider analysis
- Billing amount trends
- Admission type patterns
- Temporal analysis (time-based trends)
- Hospital performance metrics
- Doctor workload analysis

## 🚀 Getting Started

### Prerequisites
- Microsoft Power BI Desktop (for viewing the dashboard)
- Any CSV viewer or data analysis tool (for raw data)

### Data Access
1. **CSV Data**: Open `Health Care Analysis.csv` in Excel, Python, R, or any data analysis tool
2. **Power BI Dashboard**: Open `Health Care Analysis.pbix` in Power BI Desktop

### Recommended Analysis Tools
- **Python**: pandas, matplotlib, seaborn
- **R**: ggplot2, dplyr
- **Excel**: Pivot tables, charts
- **Power BI**: Interactive dashboards

## 📊 Potential Analysis Areas

### 1. Financial Analysis
- Billing amount trends over time
- Insurance provider cost comparison
- Hospital revenue analysis
- Cost by medical condition

### 2. Operational Analysis
- Admission type patterns
- Length of stay analysis
- Hospital capacity utilization
- Doctor workload distribution

### 3. Clinical Analysis
- Medical condition prevalence
- Medication effectiveness
- Test result patterns
- Age-related health trends

### 4. Quality Metrics
- Readmission rates
- Treatment outcomes
- Patient satisfaction indicators
- Healthcare quality metrics

## 🔍 Data Quality Notes

### Data Completeness
- 10,000 complete records
- No missing values in key fields
- Consistent date formats
- Standardized medical terminology

### Data Validation
- Age range validation (18-85)
- Logical date ranges
- Valid medical conditions
- Appropriate billing amounts

## 📁 Project Structure

```
Health Care Analysis/
├── Health Care Analysis.csv    # Raw patient data (10,000 records)
├── Health Care Analysis.pbix   # Power BI dashboard
└── README.md                  # Project documentation
```

## 🤝 Contributing

This project is designed for healthcare data analysis and can be extended with:
- Additional data sources
- Advanced statistical analysis
- Machine learning models
- Real-time data integration
- Custom visualizations

## 📞 Support

For questions or issues related to this healthcare analysis project, please refer to the data documentation or contact the project maintainer.

## 📄 License

This project is intended for educational and analytical purposes. Please ensure compliance with healthcare data privacy regulations (HIPAA, GDPR, etc.) when working with this data.

---

**Last Updated**: February 3, 2025  
**Data Period**: 2018-2023  
**Total Records**: 10,000 patient admissions 