# Project Name
> Lending Club Case Study - Analysis of impact of various factors on loan re-payment


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Lending club case study is analysis of various factors on loan repayment. The insights of this analysis will help banks to identify if a person is likely to replay loan or not.<br /><br />
The idea behind implementing this project is to underatand how real business problems are solved using EDA. Apart from applying EDA techniques, we also learnt about risk analytics in banking and financial services.<br /><br />
Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
Loan data set contains the complete loan data for all loans issued through the time period 2007 to 2011.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
<li><strong>83.1%</strong> individuals have successfully repaid their loans, <strong>2.76%</strong> are current loans and <strong>14.2%</strong> loans have been declared as charged off.</li>
<li>Majority of loans fall within the income range of <strong>40000 to 80000</strong>.</li>
<li>As income rises, the rate of loan defaults decreases.</li>
<li>Significant portion of defaulters opted for a <strong>60 months</strong> loan term. But when we studied only <strong>'Charged-Off'</strong> data then found that a significant portion of defaulters opted for a <strong>36 months</strong> loan term.</li
<li>There is no evident connection between owning a home and the rate of defaults on loans. But when we studied only <strong>'Charged-Off'</strong> data then found that a significant portion of individuals who have defaulted on their payments reside in <strong>rented</strong> accommodations.</li>
<li>The default rate is directly related to the interest rate. In other words, most individuals who failed to repay their loans had borrowed money at interest rates exceeding 20%. However, upon analyzing exclusively the <strong>'Charged-Off'</strong> data, we discovered that a notable number of people who failed to meet their payment obligations had taken out loans with a ratio ranging from <strong>10-15%</strong>.</li>
<li>Loans with installment amounts between <strong>500 and 750</strong> exhibit the highest rate of defaults. However, this information doesn't provide any useful insights on whether to approve or deny a loan application.</li>
<li>The default rate is highest for loans acquired for <strong>small businesses</strong> and lowest for those taken for <strong>weddings</strong>. However, upon analyzing exclusively the 'Charged-Off' data, the default rate is highest for loans acquired for <strong>Debt Consolidation</strong> and lowest for those taken for <strong>Renewable energy</strong>.</li>
<li><strong>loan_amnt</strong>, <strong>int_rate</strong> and <strong>annual_inc</strong> are related together ie have <strong>positive correlation</strong>.</li>
<li>Increasing debt to income ratio the default rate also increases upto range <strong>20-25</strong> but drops after that and most drop range is at <strong>25-30</strong>. This drop might be explained with a reason that people with very high debt to income ratio dont want to increase their debt further so they mostly pay off thier loans.</li>
<li>Majority of individuals who defaulted on their payments belong to job <strong>grade G</strong>.</li>
<li>However, Upon examining only the 'Charged-Off' data, we found that a small proportion of individuals who defaulted on their payments belong to job <strong>grade G</strong>.</li>
<li>The above chart shows that the majority of individuals who defaulted on their payments belong to state <strong>NE</strong>.</li>
<li>The chart above indicates that most people who defaulted took out larger loans in the state of CA.</li>
<li>The chart above shows that most people who failed to make payments have more than a <strong>10+ years</strong> of experience.</li>
<li>The above chart shows that a majority of defaulted loans were approved in the month of <strong>December</strong>.</li>
<li> The above chart shows that a majority of defaulted loans were approved in the year of <strong>2011</strong>.</li>

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
<li>Python</li>
<li>Numpy</li>
<li>Pandas</li>
<li>Matplotlib</li>
<li>Seaborn</li>


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
<p>"We want to express my heartfelt gratitude to the teachers and peers at Upgrad/IIITB for their consistently clear and informative sessions, as well as for patiently addressing our queries every day. I also extend my appreciation to the entire Upgrad team for providing us with this incredible learning platform."</p>


## Contact
Created by [Narendra Jha]
