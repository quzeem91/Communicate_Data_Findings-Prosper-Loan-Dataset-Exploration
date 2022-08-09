# Prosper Loan Data Exploration
## by OLAMIDE QUZEEM O.

<h2>Installations</h2>
<ul>
<li>NumPy</li>
<li>pandas</li>
<li>Matplotlib</li>
<li>Seaborn</li>
</ul>

## Dataset


**About the Dataset** 
 
<p>This Dataset contains information on 113,937 loans with 81 variables From Prosper Loan, a peer-to-peer personal loan lending Company.This Dataset was explored To Help identify variables That are Pivotal In loan Completion.</p>
<p>The Dataset can be Downloaded through this 
<a href='https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv'>url</a> and The Dataset Description File Can be accessed 
through this <a href='https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid'>link.</a></p><br>
<p>The Dataset Originally had a Dimenision of  113,937 Observations  with 81 variables,which was later subsetted to 55089 
observations and 17 Variables.</p>
<p>This Huge reduction in the Dataset in terms of Rows and Columns  was as a result of The 
Objective of The Analysis,which is  to Explore  The variables That Might help  predict The Outcome Of a 
loan(Completed,ChargedOff,Defaulted,Cancelled)So as To Know which Loan applications are to be approved or Not .</p>
<p>with over 58000 Observations still a running loan and Had to be Dropped .
Amidst The 81 Variables,only a handful(17 Variables)  of it seems to be pivotal to the aim of the Analysis and were picked .<p>
    

## Summary of Findings

Borrowers with a Non Available value for their ListingCategory and EmploymentStatus,Not Displayed value for their 
IncomeRange are prone to Default on loans .Homeowners and Non Homeowners have about the same distribution in Loan
Completion and Defaults .The more number of Recommendations a Borrower gets The more Likely They will complete 
their loan.Borrowers with Good DTI Tend To Complete Their Loans .Loans with a 1 year Duration have the highest 
completion rate with little Defaults .Borrowers With a ListingCategory of Auto and Auto related values  such as 
Motorcycles ,Boats ,RV  also have a good Completion rate.

## Key Insights for Presentation

In The Presentation ,Variables suspected To influence Loan Outcome were first selected and subsetted for .
Then I continued  With Introducing The variable of Interest(loanOutcome) alongside Other variables That Influence
Values of this variable Individually.Such as listingcategory which is The Reasons Borrowers Took Prosper loan,
IsBorrowerHomeowner that states the proportion Of Borrowers that owns a Home and Borrowers Who dont ,number of Recommendations a Borrower gets and Their DebtToIncome ratio.

These variables were explored and plotted against Each Other  using Clustered barchart ,Facetted Histogram plots ,point plots,scatterplot and I could see a pattern  of  How Borrowers With Good DTI and an handful number of  Recommendations Completes Their loan .And also How a selected handful Borrowers That owns a Home takes loan Of above 25k dollars without defaulting.
