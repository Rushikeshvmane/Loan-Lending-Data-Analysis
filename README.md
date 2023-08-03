# Loan Lending Data Analysis

<h2> Background:</h2>

Forex Club (FC) is the world's largest peer-to-peer lending company, headquartered in San Francisco, California

<h2> How it work's: </h2>


1. Customers interested in a loan complete a simple application at ForexClub.com.

2. Forex Club leverages data and technology to screen borrowers, facilitate the transaction with appropriate interest rates, and 
service the loan.

3. Qualified applicants receive loan offers and can evaluate their options with no impact to their credit score.

<h2> Objective: </h2> 
  Identify variables that provide strong indicators of potential loan default thus helping Forex club to decide approval/rejection of 
loan.

      
 
  
  * Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who **default** cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this project.
     
<h2>Tools Used</h2>

- <b>PowerBI</b> 
- <b>Microsoft Excel</b>

<h2>Data Cleaning, Data Analysis & Visualization </h2>

1. Using PowerBI ETL tool which is known as Power Query Editor, Data was extracted from excel sheets & csv files, transformed into readable and understandable format with cleaning, proper formating, namimg of columns and rows.
2. Using DAX (Data Analysis Expression) different calculated columns and measures were created which were further used with different kinds of visuals to create an interactive dashboard consisting of many visuals which would generate interesting and crucial insights from the raw data and make it easy for top manamgement to understand the same, in order to take Data driven crucial business decions. And identify the driving factors for such Loan defaults

<h2>Insights Generated:</h2>




1. Loan Purpose Analysis : <br/>   
<img src="https://github.com/Rushikeshvmane/Loan-Lending-Data-Analysis/assets/141236953/edb73ce3-a2a3-4987-9345-a155f81b3504" height="70%" width="75%"/>

<br />
<br />
2. Loan Status Analysis:
  Year, Subscription, Model colour, Category:  <br/>
<img src="https://github.com/Rushikeshvmane/Loan-Lending-Data-Analysis/assets/141236953/8e39cf9b-b563-4079-8ace-4ae888070867" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
3. Loan Term by Loan Status Analysis: <br/>
<img src="https://github.com/Rushikeshvmane/Loan-Lending-Data-Analysis/assets/141236953/38458043-656d-4f61-a483-fa544e0572c0" height="55%" width="55%" alt="Disk Sanitization Steps"/>
  

  

<br />
<br />
4. Deafulter Rate % by Employement Length:  <br/>
<img src="https://github.com/Rushikeshvmane/Loan-Lending-Data-Analysis/assets/141236953/f3452256-0040-4536-98a1-0f10885db813" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

5. Deafulter Rate % Among Home Ownership Status:  <br/>
<img src="https://github.com/Rushikeshvmane/Loan-Lending-Data-Analysis/assets/141236953/22ebbd32-eb07-415d-ad9d-3420b8b2bdf0" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />

6. Deafulter Rate % Among Verification Status:  <br/>
<img src="https://github.com/Rushikeshvmane/Loan-Lending-Data-Analysis/assets/141236953/eec8a6d5-cd61-4cdd-8f1d-efd8ac1c5dfd" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />










7. Driving Factors/ Insights:    

    i) "Pro" subscription is getting Maven Private LTD. more number of orders i.e. 243.2K compared to other subscriptions 
    and as well as highesh sales i.e.320M was generated through "Pro" subscription only, so More offers, discounts
    & marketing strategies can be implemented to double down on the sales revenue.
    
    ii) "Car" category is generating the highesh sales revenue i.e. 718M .

    iii) Order quantity for the year 2023 & 2024 was almost the same i.e. 227k- 229k but 2023 sales revenue was almost 
    100% more than the 2024 sales revenue, so whatever strategy was being used in 2023 can be used in upcoming year as well. 

    iv) "Uttar pradesh" is the state with highesh sales revenue amount of 108M, accordingly Maven Private LTD shall 
    take notice of the same and concentrate more on this states customers and what kind of subscriptions are
    they taking , which category is performing better , which month of the year is showing hike in orders. 

    v) Forecasting of next 15 days on the basis of previous data provided is done. 




    
