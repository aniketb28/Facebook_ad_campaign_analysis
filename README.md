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

--
