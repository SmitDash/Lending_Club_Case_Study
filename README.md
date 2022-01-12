# Lending Club Case Study
> This project is based on analysing the risk of approving loans to the default customers by using EDA.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This project gives an idea about how the real business problems are solved using EDA. And also gives basic understanding on risk analysis in banking and finantial services.
- This project is based on a consumer finance company which specialises in lending various types of loans to urban customers. With the help of EDA this project is trying to analyse what is the risk on appoving loans for the customers that are categorised as default/charged off.
- With the help of EDA and risk analysis, this project is trying to analyse the risk on approving the loan on the basis of no. of charged off/defaulter customers by observation of univariate, bivariate and multivarate analysis.
- The complete loan dataset for all loans issued through the time period 2007 to 2011 are used for this project.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- From univariate analysis the features that are considered to be useful for approving loan are term, grade, purpose, sub_grade, emp_length, earliest_cr_line, revol_util, loan_amnt, annual_inc.
- From bivariate analysis the features that are considered to be useful for approving loan are term, grade, 
purpose, int_rate, annual_inc, earliest_cr_line.
- From multivariate analysis the features that are considered to be useful for approving loan are term, funded_amnt_inv, int_rate, earliest_cr_line, annual_inc, revol_util.
- After observing all the analysis, the features that are useful on the basis of which approving loan to default customers can be decided are term, grade, purpose, int_rate, annual_inc, revol_util.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Ipython - 7.30.1 (version)
- NumPy - 1.21.5 (version)
- Pandas - 1.3.5 (version)

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by lending club.
- Reference link on risk analysis [https://corporatefinanceinstitute.com/resources/knowledge/credit/purpose-of-credit-risk-analysis/].
- This project was based on [https://nycdatascience.com/blog/student-works/project-1-analysis-of-lending-clubs-data/].


## Contact
Created by [@SmitDash] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->