
**Next-Generation Budgeting System**

Overview

Welcome to the Next-Generation Budgeting System, a cutting-edge web-based application designed to transform personal financial management. This system is built to empower users with insightful tools and smart recommendations, helping them manage their budget, track expenses, and plan for a secure financial future with ease and confidence.

Our system leverages modern technologies and integrates real-time financial advice, allowing users to make informed decisions with features that focus on personalization and dynamic analysis.

Features

**💰 Smart Budgeting**

Automated Tracking: Seamlessly track and categorize your expenses in real time.

Custom Budget Plans: Create customized budgets tailored to your income, expenses, and financial goals.

Expense Alerts: Get notifications when you're close to overspending in any category.

**📈 Real-Time Financial Advice**

Investment Suggestions: Based on your savings goals and financial habits, our system recommends the best investment opportunities such as:

Gold
Stocks
Real Estate
Mutual Funds

Risk-Based Recommendations: Personalize your investments according to your risk tolerance, whether conservative or aggressive.

**🔄 Dynamic Income Analysis**

Income Growth Forecast: Analyze and predict future income growth based on your career trajectory and financial behavior.

Expense Forecasting: Get predictive insights on future expenses based on current spending patterns.

**🧠 AI-Driven Insights**
Goal-Oriented Planning: Our intelligent engine understands your specific goals (e.g., retirement, home purchase, vacation) and provides actionable insights on how to achieve them faster.

Machine Learning-Powered Recommendations: Continuously improving and learning from your financial patterns to suggest the best next steps for managing your budget.

**📊 Comprehensive Reporting**

Detailed Reports: Generate monthly, quarterly, or yearly financial summaries to track progress and make adjustments.

Visual Dashboard: A user-friendly dashboard that provides clear visualizations of spending, savings, and investment trends.

**🔒 Security First**

Bank-Grade Security: Your financial data is protected with state-of-the-art encryption and secure data storage practices.

Privacy Protection: We respect your privacy, ensuring that your data is only accessible to you.

APPROACH:

**Dataset and Preprocessing:**

•	This repository contains dataset for the expense prediction model and the .ipynb file that contains the code of the model

•	Initial dataset contains around 200 columns containing the monthly expenses for the respective reason.

•	The data is pre-processed by reducing the number of categories as following:

•	Clothing , Electronical appliances , Mobile electronics, Fashion accessories, Groceries, Miscellaneous, Processed foods, Stationary , Toiletries , Toys , Medicines , Hygiene products , Home appliances , Household essentials

•	The first processed data has a schema of :

•	Gender,Age,Type,Month,Year,Expense

Since this preprocessed_data1.xlsx file has only 350 records which is insufficient for analysis , we obtain the range of expenses for each category.
Using this range we extrapolate the dataset by random imputation of values within the respective ranges.

AI Model selection and expense Prediction:
Extensive experimentation was conducted with various machine learning algorithms to  find the best predictive model. The dataset was tested with models like K-Nearest 
Neighbours (KNN), Linear Regression, Random Forest, Support Vector Regression (SVR),  and Long Short-Term Memory (LSTM), with each model's accuracy in predicting expenses
carefully evaluated.

Linear Regression stood out as the most accurate model, delivering an impressive accuracy of 88.13%. It was implemented using Intel OneAPI’s Sklearnex package, known
for improving performance and scalability in machine learning tasks. After selecting the best model, it was prepared for deployment by pickling, ensuring it seamlessly
integrated with the platform's predictive features.


**Deployment in Web-Interface**

NextGen Budgeting offers an intuitive and visually appealing dashboard for simple and accessible user interaction.

💰 Budget vs Expense: Input your overall budget and view a detailed breakdown of spending categories to manage finances effectively.

🎯 Goals: Choose financial goals and input your budget; the system estimates the time needed to achieve them.

💵 Savings: Compare income against total predicted expenses to reveal potential savings, providing a clear financial overview.

🤖 Chatbot: Engage with a conversational chatbot that tracks expenses and offers personalized financial tips to keep users motivated.

❤️ Charity: Allocate a portion of your budget for charitable contributions, integrating social responsibility into financial planning.

📈 Suggestions: Receive personalized financial insights and investment recommendations tailored to your knowledge and interests, empowering informed decision-making.

**Conclusion:**

NextGen Budgeting revolutionizes personal finance management by harnessing thepower of AI to provide personalized budgeting, expense tracking, and insightful
recommendations. This innovative platform empowers users to take control of their financial well-being and achieve their savings goals with ease.
