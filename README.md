# 📊 Campaign Analysis Report

Analyzing ad campaign performance using marketing KPIs such as ROAS, CTR, CPC, and others to draw actionable insights. Below is a detailed analysis and visualization of the dataset.

---

## 📈 Dataset Overview
- **Number of Unique Ads**: 1,143  
- **Number of Campaigns**: 3  
- **Number of Facebook Campaigns**: 691  
- **Number of Interest Groups**: 40  
- **Number of Age Groups**: 4  

### Initial Preview of the Dataset
| Column               | Description                                                                                       |
|----------------------|---------------------------------------------------------------------------------------------------|
| `ad_id`             | Unique ID for each ad                                                                             |
| `xyz_campaign_id`   | Campaign ID of the XYZ company                                                                    |
| `age`               | Age group of the target audience                                                                  |
| `gender`            | Gender of the target audience                                                                     |
| `interest`          | Interests of the target audience (based on Facebook profile)                                      |
| `Impressions`       | Number of times the ad was shown                                                                  |
| `Clicks`            | Number of times the ad was clicked                                                                |
| `Spent`             | Amount spent on the ad (in USD)                                                                   |
| `Total_Conversion`  | Total inquiries generated from the ad                                                             |
| `Approved_Conversion` | Total purchases made after interacting with the ad                                               |

---

## 🎯 Feature Engineering
**Key Metrics Derived**:  
1. **Click-Through Rate (CTR)**: `Clicks / Impressions * 100`
2. **Cost Per Click (CPC)**: `Spent / Clicks`
3. **Conversion Rate (CR)**: `Approved_Conversion / Total_Conversion`
4. **Cost Per Conversion**: `Spent / Approved_Conversion`
5. **Cost Per Mille (CPM)**: `(Spent / Impressions) * 1000`
6. **Return on Ad Spend (ROAS)**: `Conversion Value / Spent`

---

## 📊 Campaign Insights

### Campaign Performance Summary
| Campaign    | Avg Conversion | Avg Expense | Avg Visibility   |
|-------------|----------------|-------------|------------------|
| Campaign A  | 0.44           | $2.77       | 8,943 impressions|
| Campaign B  | 0.39           | $6.23       | 17,517 impressions|
| Campaign C  | 1.39           | $89.06      | 327,718 impressions|

### Key Findings  
- **Campaign C**: High visibility but lower ROAS.  
- **Campaign A & B**: Relatively higher ROAS and cost efficiency.

---

## 📈 Visualizations

### 🧑‍🤝‍🧑 Gender and Age Impact on ROAS
![Gender and Age Impact on ROAS](gender_age_roas.png)

### 🎯 Top 5 Interest Groups by ROAS
| Interest Group | ROAS    |
|----------------|---------|
| 63             | 555.56  |
| 19             | 204.08  |
| 16             | 175.44  |
| 29             | 138.89  |
| 28             | 125.79  |

### 📊 Cost Per Mille (CPM) Analysis
![CPM Analysis by Campaign](campaign_cpm.png)

---

## 🔗 Relationship Analysis

### 🔍 Clicks vs Impressions
![Clicks vs Impressions](clicks_impressions.png)

### 📉 Correlation Heatmap
![Correlation Heatmap](correlation_heatmap.png)

---

## 📜 Conclusion
- **Focus Groups**: Campaigns A and B perform better for ROAS.  
- **Optimization**: Improve efficiency in Campaign C to maximize returns.  
- **Interest Groups**: Target high-performing groups like *Interest Group 63*.  

---

## 🌟 Next Steps
1. Enhance ad creatives for Campaign C.
2. Further explore underperforming interest groups.
3. A/B test for different age and gender segments.

---

> 🚀 **Happy Analyzing!**
