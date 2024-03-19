# Business-Case-Walmart---Confidence-Interval-and-CLT

![R](https://github.com/santhosh-spark/Walmart--Confidence-Interval-and-CLT/assets/73495628/99449556-ab45-4ce3-a5fe-79f1f45d095e)


# Walmart - Confidence Interval and CLT 📈🛒

Welcome to the Walmart Confidence Interval and Central Limit Theorem (CLT) project! 🚀 In this project, we'll explore customer purchase behavior at Walmart during Black Friday and dive into the world of data analysis to help Walmart make data-driven decisions. 📊

## About Walmart 🌎🛍

Walmart is one of the world's largest retail giants, serving over 100 million customers worldwide through its supercenters, discount department stores, and grocery shops in the United States. 🌐

## Business Problem 📝🤔

The Walmart management team is keen to understand customer purchase behaviour, specifically examining the purchase amount, and how it relates to factors such as gender, age, occupation, and more. They want to answer intriguing questions like: "Do women spend more on Black Friday than men?" Imagine 50 million male and 50 million female customers - what are their spending habits like? 🛒💰

## The Dataset 📦📊

The dataset has the following features:

- User_ID:	User ID
- Product_ID:	Product ID
- Gender:	Sex of User
- Age:	Age in bins
- Occupation:	Occupation(Masked)
- City_Category:	Category of the City (A,B,C)
- StayInCurrentCityYears:	Number of years stay in the current city
- Marital_Status:	Marital Status
- ProductCategory:	Product Category (Masked)
- Purchase:	Purchase Amount

## What Good Looks Like 👍📈

To address this business problem, we'll embark on an exciting data analysis journey:

1. **Data Import & Analysis**: Import the dataset and perform standard data analysis procedures like exploring its structure and characteristics.

2. **Handling Null Values & Outliers**: Identify null values and outliers through techniques like boxplots, 'describe' method, and 'isnull' checks.

3. **Data Exploration**: Dive into the data by tracking the amount spent per transaction for 50 million female and 50 million male customers. Calculate averages and draw conclusions.

4. **Confidence Interval Calculation**: Use the sample averages to compute a Confidence Interval (CI) within which the population average spending of 50 million male and female customers may lie. This is where the magic of Central Limit Theorem (CLT) comes into play!

5. **Play with CI Width**: Experiment with different CI widths (e.g., 90%, 95%, 99%) and report your observations.

6. **Conclusions and Recommendations**: Summarize the results and check whether the confidence intervals for average male and female spending overlap. How can Walmart use these insights for changes and improvements?

7. **Repeat for Marital Status and Age**: Extend the same analysis to understand how spending behavior varies for married vs. unmarried customers and across different age groups.

8. **Give Walmart Actionable Insights**: Provide recommendations and action items to help Walmart leverage these findings for a better shopping experience. 🤝💼

Let's embark on this data-driven adventure and explore the fascinating world of Walmart's Black Friday shopping data! Feel free to contribute, provide feedback, or star this repository if you find it helpful. 🌟🤗

Happy coding and analyzing! 📊👩‍💻👨‍💻🚀


## 💡 Recommendations 💡

1) Gender-focused Strategy 🚹🚺
- Men tend to spend more than women. The company should prioritize retaining existing male customers and attracting new male customers.

2) Product Category Insight 🛍️
- Products in categories 1, 5, 8, & 11 have the highest purchasing frequency and are favored by customers. The company can consider increasing the promotion and availability of these products, as well as boosting less-purchased items.

3) Marital Status Approach 💑
- Unmarried customers exhibit higher spending compared to married customers. The company should concentrate on attracting and engaging unmarried customers.

4) Targeting Specific Age Group 🎈
- Customers aged 18-45 contribute more to the spending. To enhance revenue, the company should focus on acquiring customers within this age range.

5) City Category Strategy 🏙️
- Male customers residing in City_Category C demonstrate higher spending compared to those in City_Category B or A. To increase revenue, the company should consider emphasizing product offerings in City_Category C.  

