# Credit Risk Prediction using ML

## Project Overview:

**Project Goal**: To develop a data-driven model that predicts credit risk with high accuracy, assisting lenders in making informed loan decisions, optimizing risk management strategies, and ultimately reducing bad debt ratios and improving overall portfolio quality.

**Motivation**:

- **Financial stability**: Accurate credit risk prediction helps lenders avoid bad loans, ensuring financial stability and responsible lending practices.
- **Improved borrower experience**: By identifying borrowers with lower risk, lenders can offer more favorable loan terms and improve the overall borrower experience.
- **Data-driven insights**: This project leverages the power of data to uncover patterns and relationships in creditworthiness, leading to better decision-making and risk management.

**Note**: This project was developed as part of my academic practice to enhance my skills in Data Analysis and Machine Learning application in the financial domain.

## Dataset:

- **Dataset source**: [Credit Risk Dataset by Lao Tse](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset) on Kaggle (CSV file with 32,581 individual loan transactions).
  
- **Data fields**:
  1. **Borrower Demographics**:
     - `/person_age/`: Age of the borrower </br>
     Younger borrowers may have less established credit history and financial stability, potentially increasing risk ↑. Older borrowers may have more stable incomes and assets, potentially decreasing risk ↓.
     - `/person_income/`: Annual Income of the borrower </br>
     Higher income indicates greater financial capacity to repay loans, potentially decreasing risk ↓. Lower income may raise concerns about affordability, potentially increasing risk ↑.
     - `/person_home_ownership/`: Whether the borrower owns their own home </br>
     Homeowners may have more assets and stability, potentially decreasing risk ↓. Renters may have less financial security, potentially increasing risk ↑.
     - `/person_emp_length/`: Employment length in years </br>
     Longer employment history may indicate job security and income stability, potentially decreasing risk ↓. Frequent job changes or short employment periods may raise concerns, potentially increasing risk ↑.
       
  2. **Loan Details**:
     - `/loan_intent/`: Purpose of the loan </br>
       Types of loan_intent: 
       - Debt consolidation:	May indicate accumulated debt and financial strain ↑.
       - Education:	Invests in future earning potential, potentially lowering risk ↓.
       - Home Improvement:	Suggests stability and responsibility ↓.
       - Medical:	Unpredictable expenses and burden, potentially increasing risk ↑. 
       - Personal: Varies depending on purpose. Major purchases might be less risky than discretionary spending ↑.
       - Venture:	High risk due to business uncertainty ↑. 
     - `/loan_grade/`: Creditworthiness rating assigned by the lender. </br>
       - Grade A: High creditworthiness, low risk.
       - Grade B: Relatively low risk, slightly lower creditworthiness than A.
       - Grade C: Moderate creditworthiness, potential concerns.
       - Grade D: Higher risk compared to previous grades.
       - Grade E: Lower creditworthiness, increased risk.
       - Grade F: Significant credit risk.
       - Grade G: Lowest creditworthiness, highest risk.
     - `/loan_amnt/`: Loan amount </br>
     Higher loan amounts represent a greater financial burden and may be harder to repay, potentially increasing risk ↑. Smaller loans may pose less risk ↓.
     - `/loan_int_rate/`: Interest rate charged on the loan </br>
     Higher interest rates often reflect higher perceived risk by the lender, potentially increasing risk ↑. Lower rates may suggest lower risk ↓.
     - `/loan_status/`: Whether the loan has defaulted (not paid back), indicating the **target variable** of this analysis </br>
     Defaulted loans (1) clearly indicate risk ↑, while non-defaulted loans (0) are considered safer ↓.
     - `/loan_percent_income/`: Loan amount as a percentage of income </br>
     Higher ratios indicate a larger portion of income dedicated to loan repayment, potentially increasing risk ↑. Lower ratios suggest better financial management and a smaller burden, potentially decreasing risk ↓.

   3. **Credit History Information**:
     - `/cb_person_default_on_file/`: Whether the borrower has a history of defaults <br>
     A history of defaults significantly increases risk ↑, while a clean record suggests a lower risk profile ↓.
     - `/cb_preson_cred_hist_length/`: Length of the borrower's credit history <br>
     Longer credit history provides more data for risk assessment. Borrowers with good credit history may benefit from a longer history ↓, while those with poor credit history may see less benefit ↑.
   


features vs target variable
    
 

 -------------------------------- TO UPDATE ---------------------------------------


toolkit

applications/code editors

file structure

structure - backend
eda
machine learning
results

**Methodology:**

* Exploratory data analysis (EDA) steps.
* Model building 

**Results and Insights:**

* Key findings from EDA.
* Model performance : metrics and interpretation.
* Limitations and future work.

**Conclusion:**

* Summarize main findings and contributions.
* Highlight potential applications and benefits.
* Call to action.

**Additional Resources:**

* Links to code repository, dataset, or other relevant materials.

**Contact:**

* email address or GitHub username.
