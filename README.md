# Project Name 
Lending Club Case Study
## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

 # General Information
-As per given scenario 
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

   1- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

   2- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
- What is the background of your project?
- What is the business probem that your project is trying to solve?
- What is the dataset that is being used?

# What is the background of your project?
The background of the scenario described is related to the operations of a consumer finance company specializing in lending various types of loans to urban customers. This type of company typically provides financial services to individuals or households, offering loans for purposes such as personal expenses, home improvements, education, or debt consolidation.
Consumer finance companies play a crucial role in the lending industry by providing accessible financing options to individuals who may not qualify for traditional bank loans or who prefer alternative lending sources. These companies often cater to a specific target market, such as urban customers in this case.
The background assumes that the company receives loan applications from potential borrowers and must assess the creditworthiness of each applicant. This involves evaluating various factors, such as the applicant's income, employment history, credit score, and overall financial profile. The objective is to determine the likelihood of repayment and the potential risks associated with approving or denying a loan.
The risks mentioned in the scenario highlight the potential consequences of the company's loan approval decisions. If the company approves a loan for an applicant who is not likely to repay it, there is a risk of financial loss for the company due to potential defaults. On the other hand, if the company denies a loan to an applicant who is likely to repay, there is a risk of losing business opportunities.
To manage these risks, the consumer finance company must employ sound risk assessment and mitigation strategies. This includes implementing thorough evaluation processes, utilizing data analysis and credit scoring models, and complying with regulatory requirements to ensure responsible lending practices.
The background sets the stage for understanding the context in which the company operates and the key challenges it faces in making loan approval decisions while balancing risks and business opportunities.

# What is the business probem that your project is trying to solve?-
- As per given scenario
-    1- Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

        Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

        Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

        Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 
  2- Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

# What is the dataset that is being used?
- We are using two datasetet in this project which are in "csv" format and available in project's loan_doc folder which are "loan.csv" and "Data_Dictionary.xlsx" but our main dataset is "loan.csv" which have all information about loan for a person and "Data_Dictionary.xlsx" contain only full farm of "loan.csv" table header.


## Conclusions
#Conclusion 1 from the analysis
- Here are a few key points based on the scenario we get:
1.	Loan Approval Decision: The consumer finance company is responsible for making loan approval decisions based on an applicant's profile. This decision is crucial as it determines whether the company will provide the loan to the applicant.
2.	Risk Assessment: The company needs to assess two types of risks associated with the loan approval decision. Firstly, there is the risk of approving the loan for an applicant who is not likely to repay it, which can result in financial loss for the company. Secondly, there is the risk of not approving the loan for an applicant who is likely to repay it, leading to a loss of potential business.
3.	Applicant Profile Evaluation: The company evaluates the applicant's profile to assess their creditworthiness and repayment capacity. This evaluation typically involves considering factors such as income, employment history, credit score, debt-to-income ratio, and other relevant financial information.
4.	Risk Mitigation: The company employs risk mitigation strategies to minimize the potential losses associated with loan approval decisions. This may include implementing rigorous screening processes, utilizing credit scoring models, and analysing historical data to identify patterns and indicators of default risk.
5.	Decision Making: The company must strike a balance between approving loans to eligible and creditworthy applicants while minimizing the risk of default. This requires making informed and data-driven decisions based on a comprehensive assessment of the applicant's profile and the associated risks.
6.	Compliance and Regulations: The consumer finance company must adhere to regulatory requirements and industry best practices when evaluating loan applications and making loan approval decisions. This ensures fair lending practices and protects both the company and the applicants.
7.	Ongoing Monitoring: The risk assessment process doesn't end with the loan approval decision. The company should have mechanisms in place to monitor the repayment behaviour of borrowers throughout the loan tenure. This allows for early detection of potential default risks and enables appropriate actions to be taken, such as implementing collection efforts or modifying loan terms.
These points provide an overview of the considerations and challenges faced by a consumer finance company when making loan approval decisions and managing associated risks.

- cleaning and sanitation
-   1.Dropping unnecessary columns in a DataFrame
    2.Changing the index of a DataFrame
    3.Renaming columns to a more recognizable set of labels
    4.Skipping unnecessary rows in a CSV file
-In given dataset we have 39717 rows × 111 columns after removing null value columns we get 39717 rows × 57 columns.
But there are more other columns present with null values and after removing those null value rows we get 14 rows × 57 columns.
In third attempt I remove all column with 0 value and get 14 rows × 49 columns.



## Technologies Used
- Python Version 3.8.2
- juptyrelab Version 3.5.3
- MS Excel


## Acknowledgements

-This project was inspired by - https://github.com/anushkaparadkar/lending-club-case-study
-References if any - https://seaborn.pydata.org/index.html
-This project was based on AI ML course by UpGrad


## Contact
Created by [@rderr022] - feel free to contact me!

Group Facilitator name - Rohit Pothuru
