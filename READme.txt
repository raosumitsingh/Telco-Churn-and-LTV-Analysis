
TABLEAU LINK:- https://public.tableau.com/app/profile/sumitkumar/viz/TelcoChurnandLTVAnalysis/Story

Performed an analysis of churn and LTV on SQL and Python.

Approach:-
※ Began by creating the churn database using all the csv files that were available.
※ Created an ERD using https://dbdiagram.io and then checked whether the database satisfied 
   the properties of an RDBMS by validating the normalization rules.
※ Performed some data exploration and analysis on the churn data with the SQL browser.
※ Using Python removed missing values and joined all the tables to create a single table
   with all the data that was there.
※ After generating the combined dataframe, found that there was a significant difference 
   in the LTVs of the top 20% and bottom 80% customers.
※ Finally, performed a complex analysis to check which factors influence the LTVs of the
   customers and what are the conjectures that we can draw for pulling people into 
   the high-LTV group.
※ Then  implemented a bubble sort algorithm to sort the customers in 
   decreasing order of their lifetime values (LTVs).
※ And created another function to tag the customers into high- and low- LTV groups.
※ Finally, added all the functions created in this session in a single class, 
   from where we can access all of them directly.
※ Creating multiple dashboards in Tableau on the different services and their relation with contract, 
   total charges (LTVs), monthly charges, tenure, and churn.
※ Created some plots in Tableau to understand the contract and the payment patterns.
※ Created another dashboard in Tableau to understand only the LTV.
※ Finally, created a Tableau story with all the dashboards created so far.
 