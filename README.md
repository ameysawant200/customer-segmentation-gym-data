# 🧘‍♂️ Customer Segmentation – Gym Data

## 📊 Overview
This project segments 2,000 gym members into distinct customer groups using clustering techniques. The objective is to support **targeted marketing and retention strategies** by understanding patterns in demographics, income, and lifestyle.

## 🛠️ Tools & Techniques
- Python (Pandas, Seaborn, Scikit-learn, Matplotlib)
- Unsupervised Learning: K-Means++, Agglomerative Clustering
- Evaluation: Elbow Method, Silhouette Score
- Cluster Profiling & Business Insight

## 📁 Dataset Summary
- 2,000 gym members with attributes:
  - Demographics: Age, Gender, Marital Status, Education
  - Socioeconomic: Income, Occupation, Settlement Size

## 🔍 Key Analysis Steps

1. **Exploratory Data Analysis**:
   - Cleaned and explored distributions of categorical & numeric variables
   - Correlation heatmap: Income strongly related to Age

2. **Clustering Techniques**:
   - Used StandardScaler to normalize Age & Income
   - Determined optimal clusters using Elbow and Silhouette methods
   - Applied:
     - K-Means++ (4 segments)
     - Agglomerative Clustering (4 segments)

3. **Segment Interpretation**:
   - Cluster 0: “Rural Young Starters” – Low-income, single males in rural areas
   - Cluster 1: “Urban Professionals” – Middle-aged, high-income, highly educated
   - Cluster 2: “Affluent Seniors” – Wealthiest, oldest, urban retirees
   - Cluster 3: “Rural Low-Income Singles” – Youngest and lowest income

## 📈 Sample Visualizations
- Elbow Plot (K vs. WCSS)
- Silhouette Scores
- Cluster Scatter Plot (Age vs Income)

## 💡 Business Insights
- Segment-specific fitness plans can drive better engagement and retention
- Affluent Seniors are ideal for premium services and loyalty programs
- Rural groups need discounted plans and localized campaigns

## 🧠 Recommendations
- Launch marketing tailored to income/age cluster
- Offer referral schemes for Rural Starters
- Upsell wellness tracking to Urban Professionals

## 🤖 Author
**Amey Pradeep Sawant**  
Master of Business Analytics, Macquarie University  
[LinkedIn Profile](https://www.linkedin.com/in/your-link)
