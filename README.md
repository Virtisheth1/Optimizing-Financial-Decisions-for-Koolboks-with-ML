# Optimizing-Financial-Decisions-for-Koolboks-with-ML

 1. **Exploratory Data Analysis (EDA)**
   - Conducted EDA to identify key patterns in customer payment behavior, product popularity, and income demographics.
   - The top three product sizes (538L, 208L, 158L) were found to generate the most revenue.
   - Income categories were matched with product sizes, showing broad market appeal of the 538L product across income levels.
 2. **Pricing Optimization**
   - Analyzed key economic indicators like the Nigerian prime rate, inflation rate, and auto loan percentages to inform pricing strategies.
   - Recommended simplifying product offerings and aligning payment plans with customer income levels for better financial outcomes.
   - Emphasized the importance of collecting income data to support the "Pay as You Go" (PAYG) billing model.

 3. **Creditworthiness Modeling**
   - **Model 1: Credit Risk Profiling (Pre-Purchase)**
     - Built an XGBoost model to assess customer credit risk before purchases based on demographic and financial attributes.
     - Achieved 88% accuracy with precision and recall for both trusted and at-risk customers.
     - Features like product use and location were critical predictors of credit risk.
   - **Model 2: Credit Risk Profiling (Post-Purchase)**
     - Focused on predicting repossession probability using payment behavior and customer attributes.
     - Achieved 87% test accuracy, highlighting the importance of down payment percentage and product size in assessing risk.

 4. **Predicting Default Probability**
   - Implemented a logistic regression model to predict the likelihood of default based on payment data and customer behavior.
   - The model achieved high accuracy (98.39%) and ROC-AUC (99.79%), indicating strong performance in distinguishing between defaulters and non-defaulters.

 5. **Default Management and Repossession Criteria**
   - Established clear criteria for determining default and outlined actions (repossession or write-off) based on payment delinquency.
   - Developed business rules for repossession if non-payment exceeds 30 days and write-off for shorter periods.

**Technologies Used:**
- **Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, XGBoost, Logistic Regression
- **Tools**: SMOTE (for imbalance handling), RandomOverSampler, Label Encoding, Cross-Validation, Feature Engineering

This project successfully optimized pricing, credit risk assessment, and default prediction, leading to actionable recommendations for Koolboks' financial strategies.

