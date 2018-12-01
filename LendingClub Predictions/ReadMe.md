
# LendingClub Predictions

Lending Club is a marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return. You can read more about their marketplace [here](https://www.lendingclub.com/public/how-peer-lending-works.action).

Each borrower fills out a comprehensive application, providing their past financial history, the reason for the loan, and more. 
- Lending Club evaluates each borrower's credit score using past historical data (and their own data science process!) and assign an interest rate to the borrower. 
- The interest rate is the percent in addition to the requested loan amount the borrower has to pay back. 
- A higher interest rate means that the borrower is riskier and more unlikely to pay back the loan while a lower interest rate means that the borrower has a good credit history is more likely to pay back the loan. 
- Each borrower is given a grade according to the interest rate they were assigned. 
- If the borrower accepts the interest rate, then the loan is listed on the Lending Club marketplace.
- Approved loans are listed on the Lending Club website, where qualified investors can browse recently approved loans, the borrower's credit score, the purpose for the loan, and other information from the application.
- The borrower then makes monthly payments back to Lending Club either over 36 months or over 60 months. Many loans aren't completely paid off on time, however, and some borrowers [default](https://www.lendingclub.com/investing/investor-education/collection-of-monthly-payments) on the loan.
- Lending Club releases data for all of the approved and declined loan applications periodically on their [website](https://www.lendingclub.com/info/download-data.action).
- The data dictionary for the data is present [here](https://github.com/ajdatahub/ProjectDS/tree/master/LendingClub%20Predictions). The LoanStats sheet describes the approved loans datasets and the RejectStats describes the rejected loans datasets. Since rejected applications don't appear on the Lending Club marketplace and aren't available for investment, we'll be focusing on data on approved loans only.


- The approved loans datasets contain information on current loans, completed loans, and defaulted loans. Let's now define the problem statement for this machine learning project:

    __Can we build a machine learning model that can accurately predict if a borrower will pay off their loan on time or not?__

