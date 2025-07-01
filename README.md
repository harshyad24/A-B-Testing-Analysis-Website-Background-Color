# A/B Testing Analysis: Website Background Color Impact on Conversion Rates

## 📊 Overview

This repository contains a comprehensive A/B testing analysis examining the impact of website background color on user conversion rates. The study compares a white background (control group) versus a black background (treatment group) to determine which design leads to better user engagement and conversion performance.

## 🎯 Experiment Details

### Hypothesis
**"Does changing the website background color from white to black improve user conversion rates?"**

### Test Setup
- **Control Group (A)**: White background (default)
- **Treatment Group (B)**: Black background (new design)
- **Sample Size**: 5,000 users
- **Group Distribution**: Balanced (50.4% vs 49.6%)
- **Duration**: Single session analysis
- **Geographic Scope**: United Kingdom

### Key Metrics Analyzed
- **Primary**: Conversion Rate (Yes/No)
- **Secondary**: Page Views, Time Spent on Site
- **Segmentation**: Device Type, Geographic Location

## 🔍 Key Findings

### 🎉 Primary Results
| Metric | Group A (White) | Group B (Black) | Improvement | P-value | Significance |
|--------|-----------------|-----------------|-------------|---------|--------------|
| **Conversion Rate** | 5.4% | 14.1% | **+160.5%** | <0.0001 | ✅ Highly Significant |
| Page Views | 7.58 | 7.49 | -1.2% | 0.436 | ❌ Not Significant |
| Time Spent | 241.7s | 243.3s | +0.7% | 0.642 | ❌ Not Significant |

### 📈 Statistical Robustness
- **Effect Size**: Medium (Cohen's h = 0.30)
- **Statistical Power**: 100% (well-powered study)
- **Odds Ratio**: 2.87x (Group B users are 2.87 times more likely to convert)
- **Confidence**: 99.99% (p < 0.0001)

### 🎯 Segment Analysis
#### Device Performance
- **Desktop**: 13.9% vs 5.9% (+135% improvement)
- **Mobile**: 14.2% vs 4.9% (+190% improvement)

#### Geographic Performance
- **England**: 14.7% vs 6.9% (+113% improvement)
- **Scotland**: 15.1% vs 4.9% (+208% improvement)
- **Wales**: 15.1% vs 4.8% (+215% improvement)
- **Northern Ireland**: 11.5% vs 5.0% (+130% improvement)

## 🗂️ Repository Structure

```
├── ab_testing_analysis.py      # Complete analysis script
├── ab_testing.csv             # Dataset (5,000 user records)
├── README.md                  # This file
├── requirements.txt           # Python dependencies
└── results/
    ├── visualizations/        # Generated plots and charts
    ├── analysis_report.txt    # Detailed statistical output
    └── recommendations.md     # Business recommendations
```

## 🛠️ Technical Implementation

### Dependencies
```python
pandas>=1.5.0
numpy>=1.21.0
matplotlib>=3.5.0
seaborn>=0.11.0
scipy>=1.9.0
```

### Dataset Schema
| Column | Type | Description |
|--------|------|-------------|
| User ID | Integer | Unique user identifier |
| Group | String | A (Control) or B (Treatment) |
| Page Views | Integer | Number of pages viewed in session |
| Time Spent | Integer | Session duration in seconds |
| Conversion | String | Yes/No conversion outcome |
| Device | String | Desktop/Mobile/Tablet |
| Location | String | UK geographic region |

## 📋 Analysis Steps

The analysis follows a comprehensive 9-step process:

1. **Data Loading & Exploration** - Initial data validation and overview
2. **Data Quality Check** - Missing values, duplicates, balance verification
3. **Exploratory Data Analysis** - Visual comparisons and distributions
4. **Statistical Preparation** - Group separation and summary statistics
5. **Hypothesis Testing** - Chi-square, t-tests, Mann-Whitney U tests
6. **Effect Size Calculation** - Cohen's d, odds ratios
7. **Segment Analysis** - Device and location breakdowns
8. **Statistical Power Analysis** - Power calculation and sample size adequacy
9. **Recommendations** - Business decision framework

## 📊 Visualizations

The analysis generates comprehensive visualizations including:
- Group distribution comparisons
- Conversion rate comparisons
- Box plots for continuous metrics
- Segment performance breakdowns
- Statistical test results

## 🎯 Business Recommendations

### ✅ **STRONG RECOMMENDATION: IMPLEMENT BLACK BACKGROUND**

**Rationale:**
- **160.5% conversion rate improvement** (highly significant)
- **Consistent improvement across all segments**
- **No negative impact on engagement metrics**
- **Robust statistical evidence with large sample size**

### 💰 **Expected Business Impact**
For a website with 1,000 daily visitors:
- **Current daily conversions**: ~54
- **Projected daily conversions**: ~141
- **Additional daily conversions**: +87 (+160.5%)

### 🚀 **Implementation Strategy**
1. **Immediate**: Deploy black background design
2. **Monitor**: Track conversion rates for 2-4 weeks post-implementation
3. **Validate**: Ensure sustained improvement
4. **Expand**: Consider testing other dark theme elements

## ⚠️ **Important Considerations**

- **Effect Persistence**: Monitor long-term performance to ensure the effect doesn't diminish
- **Seasonal Factors**: Consider if results might vary by season or user demographics
- **Technical Implementation**: Ensure proper A/A testing to validate implementation
- **User Experience**: Gather qualitative feedback on the new design

## 📈 **Success Metrics**

Post-implementation tracking should focus on:
- **Conversion rate sustainability** (target: maintain >12% conversion rate)
- **User satisfaction scores**
- **Bounce rate changes**
- **Long-term revenue impact**

## 🔬 **Statistical Methods Used**

- **Chi-square test** for conversion rate comparison
- **Independent t-test** for page views comparison
- **Mann-Whitney U test** for time spent comparison (non-parametric)
- **Effect size calculations** (Cohen's d, Cohen's h, Odds Ratio)
- **Power analysis** for sample size validation

## 📝 **Citation**

If you use this analysis methodology, please cite:
```
A/B Testing Analysis: Website Background Color Impact on Conversion Rates
Dataset: Synthetic retail website user behavior data (n=5,000)
Analysis Date: [JUNE 2025]
```

## 🤝 **Contributing**

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add some improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Create a Pull Request

## 📞 **Contact**

- **LinkedIn**: https://www.linkedin.com/in/harshyadav577/
- **GitHub**: https://github.com/harshyad24

---

## 🏆 **Key Takeaways**

> **This A/B test demonstrates the significant impact that simple design changes can have on business metrics. The 160.5% improvement in conversion rates from changing the background color represents a substantial business opportunity with minimal implementation cost.**

**Status**: ✅ **IMPLEMENTATION RECOMMENDED**  
**Confidence Level**: 99.99%  
**Business Impact**: High  
**Implementation Difficulty**: Low  

