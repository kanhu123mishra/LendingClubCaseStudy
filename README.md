# LendingClubCaseStudy
This project uses lending club dataset to predict if a loan will be defaulted or not.
The company wants to understand the driving factors behind defaulting a loan , i.e. the variables which are strongly linked to loan defaults. The company may use this data for portfolio and risk assesment.


## Table of Contents
### **Project Description**
Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders.In this case, the customers labelled as 'charged-off' are the 'defaulters'.
The objective of the case study would be to identify the risky loan applicants and hence reducing the credit loss and also will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.

The project involved the below **steps** for solving the problem statement:
1)Data loading

2)EDA and data story telling

3)Data Cleaning :
  - Dropping null values
  - Dropping single value columns
  - Filtering data with loan_status='Current'
  - Dropping fields with least significance for analysis
  - **Data standardization**
  - **Treating missing values**
  - **Outlier identification & treatment**
    
4) Data Analysis:
  - **Univariate Analysis**
  - **Bivariate Analysis**
  - **Multivariate Analysis**
  - **Derived Metric Generation & Analysis**

5) Conclsuion/Insights


### **Technologies Used**
Numpy Version       => 1.18.1

Pandas Version      =>   1.1.5

Matplotlib Version  =>  3.5.3

seaborn Version     =>  0.12.2

## Conclusions
The below mentioned conclusions can be drawn from the analysis performed, the chances for defaulting a loan is higher for the below case :
1) Customer taken loan for home improvement, house, small business & credit card and having huge loan amount.

2) Customer taken loan amount > 12500.

3) Customer with high interest loan.

4) Customer with high income is given loan in high interest rate.

5) Customer taken loan for small business, credit card.

6) Customer taken loan in the year 2011. May be due to macro economic changes.

7) Verified customers

8) Customer with loan amount 5k-10k with high term. These are sub prime customer.


## Acknowledgements
- This project was inspired by https://www.linkedin.com/in/akashdeep-makkar-12110880/
- This project was based on referring the below references for any issues faced:
  
  **For revisiting topics:** Upgrad's Live Session & Notes
  
  **Panda dataframe read error:** https://stackoverflow.com/questions/24251219/pandas-read-csv-low-memory-and-dtype-options.
  
  **Seaborn countplot:** https://www.geeksforgeeks.org/countplot-using-seaborn-in-python/
  


## Contact
Created by [@kanhu123mishra] - feel free to contact me!

### Contributors
- Samir K (samirt19@gmail.com)


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
