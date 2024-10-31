# 🛒 Walmart Customer Purchase Behavior Analysis

## 📖 Project Overview

Walmart, an American multinational retail giant, serves over 100 million customers worldwide across its supercenters, department stores, and grocery chains. This analysis focuses on understanding the customer purchase behavior at Walmart, particularly during Black Friday, with insights into gender-based spending habits and how factors such as marital status and age influence purchases.

## 🧩 Business Problem

Walmart's management seeks to analyze customer purchase behavior, specifically comparing purchase amounts by gender to identify if spending habits differ significantly. The goal is to address questions such as:
- Do women spend more on Black Friday than men?
- How do marital status and age impact spending patterns?

These insights will guide Walmart in tailoring promotions and enhancing the customer experience to increase sales and improve customer targeting.

## 📊 Dataset

- **Dataset Link**: [walmart_data.txt](https://drive.google.com/file/d/1wvMdK_0NrSodLoZMSgVQfyCG0j0it_nK/view?usp=sharing) 

### Dataset Attributes:
- **User_ID**: Unique user identifier
- **Product_ID**: Unique product identifier
- **Gender**: Customer's gender (Male/Female)
- **Age**: Age in specified bins
- **Occupation**: Occupation (masked for anonymity)
- **City_Category**: City type (A, B, C)
- **StayInCurrentCityYears**: Number of years in the current city
- **Marital_Status**: Marital status of the customer
- **ProductCategory**: Product category (masked for anonymity)
- **Purchase**: Purchase amount

## 🔍 Analysis Approach

1. **Data Exploration and Preprocessing**:
   - Analyzed data structure, types, and provided a statistical summary.
   - Detected missing values and outliers using methods like boxplots and descriptive statistics.
   - Converted categorical attributes to 'category' type as necessary.

2. **Gender-Based Spending Analysis**:
   - Tracked average spending per transaction for male and female customers.
   - Calculated confidence intervals to predict the population spending range based on samples, leveraging the Central Limit Theorem (CLT).
   - Observed the distribution of spending and intervals to conclude on gender-based spending patterns.

3. **Confidence Interval Analysis**:
   - Used varying confidence levels (90%, 95%, 99%) to understand the reliability of average spending estimates.
   - Compared male and female spending confidence intervals to determine if there's a significant overlap or difference.

4. **Marital Status and Age Group Analysis**:
   - Repeated the confidence interval analysis for marital status (Married vs. Unmarried) and age groups.
   - Grouped age bins by life stages (0-17, 18-25, 26-35, 36-50, 51+) to understand stage-specific spending patterns.

## 📈 Insights and Recommendations

1. **Key Findings**:
   - Identified significant patterns in spending across gender, marital status, and age groups.
   - Gender-based confidence intervals revealed if women spend more on Black Friday than men.
   - Marital status and age-specific intervals highlighted additional patterns in spending behaviors.

2. **Recommendations for Walmart**:
   - **Targeted Promotions**: Create gender-specific promotions based on spending insights.
   - **Age-Based Marketing**: Tailor offers by age groups (e.g., special promotions for young adults in the 18-25 age group).
   - **Enhanced Personalization**: Develop personalized marketing strategies for married vs. unmarried customers based on spending habits.
   - **Strategic Confidence Levels**: Use 95% confidence intervals to balance accuracy and business insights.

## 🎯 Conclusion

This analysis provides actionable insights for Walmart to improve its customer targeting, leverage gender and age-specific data for promotions, and refine marketing strategies to align with observed spending behaviors.

## 🚀 Future Scope

- Extend the analysis to explore specific product categories and their appeal across customer segments.
- Incorporate seasonal trends to understand spending variations during other key shopping events.
- Apply clustering techniques to identify distinct customer segments based on purchase behavior.

## 📧 Contact

For further information or collaboration inquiries, feel free to reach out at:

- **Email**: adharshreddy.c@gmail.com
- **LinkedIn**: [adharshreddyc](https://www.linkedin.com/in/adharshreddyc/)
