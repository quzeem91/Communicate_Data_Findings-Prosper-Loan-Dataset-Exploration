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


<p>This dataset contains information on 113,937 loans with 81 variables from Prosper Loan, a peer-to-peer personal loan lending company. The dataset was explored to help identify pivotal variables in loan completion.</p>

<p>You can download the dataset from this <a href='https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv'>URL</a>, and the dataset description file can be accessed through this <a href='https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid'>link</a>.</p>

<p>The dataset originally had 113,937 observations with 81 variables but was later subsetted to 55,089 observations and 17 variables.</p>

<p>This reduction in the dataset was done to focus on exploring variables that might help predict the outcome of a loan (completed, charged off, defaulted, canceled) to determine which loan applications should be approved.</p>

<p>Out of the 81 variables, only a subset of 17 variables seemed to be pivotal to the analysis objective and were selected for further exploration.</p>

<h2>Summary of Findings</h2>

<p>Based on the analysis, the following findings were observed:</p>

<ol>
  <li>Borrowers with a non-available value for their listing category and employment status, and a not displayed value for their income range, are prone to default on loans.</li>
  <li>Homeowners and non-homeowners have a similar distribution in loan completion and defaults.</li>
  <li>The number of recommendations a borrower receives is positively correlated with loan completion.</li>
  <li>Borrowers with good debt-to-income (DTI) ratio tend to complete their loans.</li>
  <li>Loans with a 1-year duration have the highest completion rate with fewer defaults.</li>
  <li>Borrowers with a listing category of "Auto" and auto-related values such as motorcycles, boats, and RVs also have a good completion rate.</li>
</ol>

<h2>Key Insights for Presentation</h2>

<p>For the presentation, the following key insights will be highlighted:</p>

<ol>
  <li>Variables suspected to influence loan outcome were selected and subsetted for analysis.</li>
  <li>The variable of interest, loan outcome, was introduced along with other variables that individually influence its values, such as listing category, borrower homeownership status, number of recommendations, and debt-to-income ratio.</li>
  <li>These variables were explored and plotted against each other using clustered bar charts, facetted histogram plots, point plots, and scatter plots. Patterns were observed, such as borrowers with good DTI and a low number of recommendations being more likely to complete their loans. Additionally, a selected group of homeowners taking loans above $25,000 without defaulting was identified.</li>
</ol>

<p>By presenting these key insights, the audience will gain a clear understanding of the factors that contribute to loan completion and the potential predictors of loan outcomes.</p>




