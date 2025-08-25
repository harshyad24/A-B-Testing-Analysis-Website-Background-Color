# A/B Testing Analysis: Website Background Color Impact Study

## 📊 Executive Summary

This project analyzes the impact of website background color changes on user engagement and conversion rates through a comprehensive A/B testing framework. Using Python for statistical analysis and Power BI for business intelligence visualization, we tested two variants across 5,000 users to determine the optimal background color strategy.

## 🎯 Business Problem

**Primary Question:** Does changing the website background color (Variant B) improve conversion rates compared to the current design (Variant A)?

**Success Metrics:**
- Conversion Rate (Primary KPI)
- User Engagement (Time Spent, Page Views)
- Device-specific Performance
- Geographic Performance Variations


## 📊 Power BI Dashboard Components

### **Dashboard A - Variant Performance Analysis**
![Dashboard A](https://github.com/harshyad24/A-B-Testing-Analysis-Website-Background-Color/blob/main/A%20Test.png)
**📊 Dashboard A (Control Group):** Shows baseline performance metrics for the original design
**Key Components:**
- **Performance Overview Panel:** Conversion rate comparison by device (Mobile: 4.94%, Desktop: 5.87%)
- **User Metrics Table:** Individual user tracking with Page Views, Time Spent, and Conversion status
- **Flow Analysis:** Group → Device → Conversion → Location user journey
- **Geographic Distribution:** England (21), Scotland (16), Northern Ireland (13), Wales (13)

### **Dashboard B - Optimized Variant Results**
![Dashboard B](https://github.com/harshyad24/A-B-Testing-Analysis-Website-Background-Color/blob/main/B%20Test.png)
**📊 Dashboard B (Test Group):** Displays optimized performance results for the new background color
**Key Components:**
- **Enhanced Performance Panel:** Significantly improved conversion rates (Mobile: 14.24%, Desktop: 13.91%)
- **User Journey Visualization:** Same flow structure showing improved conversion paths
- **Regional Performance:** Enhanced geographic distribution with better conversion rates
- **Statistical Validation:** Clear evidence of performance improvement across all segments
This analysis includes two comprehensive Power BI dashboards that provide complete visibility into the A/B test performance:


*Both dashboards follow identical layouts for easy comparison and feature real-time filtering capabilities.*

## 📈 Key Business Insights

### 1. **Primary Performance Comparison**
| Metric | Variant A | Variant B | Improvement |
|--------|-----------|-----------|-------------|
| **Conversion Rate** | 4.94% | 14.24% | **+188% lift** |
| **Mobile Conversion** | 4.94% | 14.24% | **+188% lift** |
| **Desktop Conversion** | 5.87% | 13.91% | **+137% lift** |

### 2. **Statistical Significance**
- **Result:** Statistically significant at α = 0.05
- **Confidence:** 95% confidence interval
- **Effect Size:** +9.3 percentage points improvement

### 3. **Engagement Metrics Analysis**
- **Average Time Spent:** Consistent across variants (~243 seconds)
- **Page Views:** Minimal difference (7.44-7.64 avg)
- **Key Finding:** Conversion improvement driven by design optimization, not engagement duration

## 🔍 Detailed Analysis Results

### **Question 1: Primary Conversion Performance**
**Answer:** Yes, Variant B significantly outperforms Variant A
- Variant A: 4.94% conversion rate
- Variant B: 14.24% conversion rate
- **Business Impact:** 188% relative improvement

### **Question 2: Effect Size Quantification**
**Answer:** +9.3 percentage points absolute improvement
- **Absolute Lift:** +9.3 percentage points
- **Relative Lift:** +188%
- **Statistical Power:** High confidence in results

### **Question 3: Engagement-Conversion Correlation**
**Answer:** Conversion improvement is independent of engagement metrics
- Time spent remains consistent (240-243 seconds)
- Page views show minimal variation (7.44-7.64)
- **Insight:** Design change directly impacts conversion decision-making

### **Question 4: Funnel Analysis**
**Answer:** Primary drop-off occurs at final conversion stage
- Users engage similarly across variants
- Conversion decision point shows significant difference
- **Recommendation:** Focus on conversion-focused design elements

### **Question 5: Segment Performance**
**Answer:** B outperforms A across all segments

| Segment | Variant A | Variant B | Lift |
|---------|-----------|-----------|------|
| **Mobile** | 4.94% | 14.24% | +188% |
| **Desktop** | 5.87% | 13.91% | +137% |
| **Scotland** | - | - | Positive |
| **Wales** | - | - | Positive |
| **England** | - | - | Positive |
| **N. Ireland** | - | - | Positive |

### **Question 6: Statistical Significance**
**Answer:** Yes, highly significant (p < 0.05)
- Confidence Level: 95%
- Sample Size: 5,000 users (2,519 A, 2,481 B)
- Power Analysis: Sufficient sample size for reliable conclusions

### **Question 7: Business Impact Projection**
**Answer:** Expected +930 additional conversions per 10,000 users
- Current baseline (A): 494 conversions per 10,000 users
- Projected performance (B): 1,424 conversions per 10,000 users
- **Net Gain:** 930 additional conversions (+188% improvement)

## 🛠️ Technical Implementation

### **Data Analysis Stack**
- **Python Libraries:** pandas, numpy, scipy, matplotlib, seaborn
- **Statistical Methods:** Chi-square tests, confidence intervals, effect size calculations
- **Visualization:** Power BI Dashboard with interactive filtering

### **Dashboard Features**
- Real-time conversion tracking
- Device-specific performance metrics
- Geographic performance breakdown
- User journey flow analysis
- Statistical significance indicators


### **Dashboard Comparison Analysis**

| Dashboard Element | Variant A | Variant B | Improvement |
|-------------------|-----------|-----------|-------------|
| **Mobile Conversion** | 4.94% | 14.24% | +188% ⬆️ |
| **Desktop Conversion** | 5.87% | 13.91% | +137% ⬆️ |
| **Avg Time Mobile** | 240.37s | 243.38s | +1.2% ⬆️ |
| **Avg Time Desktop** | 243.13s | 243.24s | Stable |
| **User Count** | 2,519 (A) / 2,481 (B) | Same | Balanced |

### **Interactive Dashboard Features**
- **Real-time Filtering:** Device type, location, conversion status
- **Drill-down Capabilities:** Individual user journey analysis  
- **Color-coded Performance:** Red (low), Green (high), Visual KPI indicators
- **Cross-dashboard Comparison:** Side-by-side variant analysis

## 🎯 Business Recommendations

### **Immediate Actions**
1. **Deploy Variant B** - Roll out new background color to 100% of traffic
2. **Monitor Performance** - Continue tracking for 2-4 weeks post-launch
3. **Document Learnings** - Update design system guidelines

### **Future Optimization**
1. **A/B Test Additional Elements** - Test other design components
2. **Personalization** - Consider device-specific optimizations
3. **Geographic Customization** - Explore region-specific design preferences

## 📈 Expected Business Impact

### **Revenue Projections (Annual)**
- **Current Performance:** 4.94% conversion rate
- **Optimized Performance:** 14.24% conversion rate
- **Revenue Multiplier:** 2.88x improvement
- **ROI:** Immediate positive impact with minimal implementation cost

### **Risk Assessment**
- **Low Risk:** No negative performance indicators
- **High Confidence:** Strong statistical evidence
- **Quick Implementation:** Simple CSS/design change

## 🔗 Repository Structure

```
├── data/                    # Raw and processed datasets
├── notebooks/              # Jupyter notebooks with analysis
├── src/                    # Python analysis scripts
├── dashboards/            # Power BI dashboard files
│   ├── dashboard_a.pbix   # Variant A dashboard
│   ├── dashboard_b.pbix   # Variant B dashboard
│   └── combined_analysis.pbix # Comparative analysis
├── images/                # Dashboard screenshots
│   ├── dashboard_a.png    # Variant A screenshot
│   ├── dashboard_b.png    # Variant B screenshot
│   └── comparison_view.png # Side-by-side comparison
├── results/               # Statistical test outputs
└── README.md             # This documentation
```

## 📸 Dashboard Screenshots Setup

To properly display both dashboards in this README, ensure you have:

1. **Save Dashboard Screenshots:**
   ```bash
   mkdir images/
   # Save your Power BI dashboards as PNG files:
   # - dashboard_a.png (Dashboard showing Variant A results)
   # - dashboard_b.png (Dashboard showing Variant B results)
   ```

2. **Dashboard File Organization:**
   ```bash
   mkdir dashboards/
   # Place your Power BI files:
   # - dashboard_a.pbix
   # - dashboard_b.pbix
   # - combined_analysis.pbix (optional comparative dashboard)
   ```

## 📋 Methodology

1. **Randomized Controlled Trial** - Users randomly assigned to variants
2. **Balanced Sample Sizes** - Nearly equal group sizes (2,519 vs 2,481)
3. **Multiple Metrics Tracking** - Conversion, engagement, and behavioral metrics
4. **Statistical Rigor** - Proper significance testing and confidence intervals
5. **Business Context** - Results interpreted through business impact lens

## 🏆 Conclusion

The A/B test conclusively demonstrates that Variant B (new background color) delivers superior business outcomes with a **188% improvement in conversion rates**. The results are statistically significant, consistent across device types and geographic segments, and ready for immediate implementation.

**Final Recommendation:** Deploy Variant B to all users and establish this as the new baseline for future optimization efforts.

---

**Project Author:** Harsh Yadav   
**Last Updated:** August 15, 2025
