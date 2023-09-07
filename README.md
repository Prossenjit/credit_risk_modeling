# credit_risk_modeling
Objective of this project is to calculate probability of default for a borrower and segregate potential defalters from non defaulters of a bank. The data used here is a actual bank's data without sensetive informations.

This analysis includes roll rate analysis to select the time frame to justify a defaulter, vintage analysis to select performance window, observation period analysis to select observation period.

Exploratory data analysis has been performed to explore and get insights from the data which can be used to take necessary actions and valuable informations which can be used in model building.

At last, based on the result of explanatory analysis, a machine learning model was build to segregate potential defaulters from non-defaulters based on probability of default score.

This analysis includes 2 data sets.
1. Credit data
2. Application data

Credit data frame holds the borrower's ID, Months balance and status.
ID - Unique ID of a borrower
Months balance - Months of the extracted data in backwards. eg. 0 refers current month and -10 referes the month 10 months back.
Status - Status of the loan in the specific month. 0: 1-29 days past due 1: 30-59 days past due 2: 60-89 days overdue 3: 90-119 days overdue 4: 120-149 days overdue 5: Overdue or bad debts, write-offs for more than 150 days C: paid off that month X: No loan for the month.

Application data holds borrower specific information:
1. CODE_GENDER - Gender of borrower.
2. FLAG_OWN_CAR - If the borrower owns a car.
3. FLAG_OWN_REALTY - If the borrower owns a property.
4. CNT_CHILDREN - Number of childern the borrower has.
5. AMT_INCOME_TOTAL - Borrower's income.
6. NAME_INCOME_TYPE - Type of income. (eg. Commercial associate)
7. NAME_EDUCATION_TYPE - Education level of the borrower.
8. NAME_FAMILY_STATUS - Family status. (eg. Single, Married).
9. NAME_HOUSING_TYPE - Type of houseing (eg. rented, house/apartment).
10. DAYS_BIRTH - No of days went after the birthday of borrower in backward. (eg. -12000, this means 0 is the present day and borrower was born 12000 days back).
11. DAYS_EMPLOYED - Same as Days birth but for employement.
12. FLAG_MOBIL - If the borrower owns a mobile.
13. FLAG_WORK_PHONE - If the borrower has a work phone.
14. FLAG_PHONE - If the borrower owns a phone.
15. FLAG_EMAIL - If the borrower uses email.
16. OCCUPATION_TYPE - Occupation type of the borrower.
17. CNT_FAM_MEMBERS - Total number of family members.
