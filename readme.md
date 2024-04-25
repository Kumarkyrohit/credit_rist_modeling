## Problem statement
We have the customers data from the bank as well as from a cibil score providing agency, we have to predict wheather the customer should be given loan or not.

We these 4 categories in our target variable apart from a simple yes and no categorization - 

1. P1 - customer is very good for loan
2. P2 - Good but not as good as P1
3. P3 - 2nd least priority customers
4. P4 - least priority customers 

### Banking Domain Knowledge

All these terms below are as per the bank and for the bank -

### Assets and Liabilities
In banking, assets refer to all financial resources owned by the bank, including cash, loans, investments, and properties. These assets generate income for the bank. Liabilities are the obligations of the bank, such as deposits and borrowings, which the bank must repay.

### Non-Performing Assets (NPA)
Non-Performing Assets (NPA) are loans or advances that have stopped generating income for the bank, typically because the borrower has failed to pay interest or repay the principal amount for a specified period (usually 90 days). NPAs are a concern for banks as they affect profitability and indicate credit risk.


Memory updated
Certainly! Here's a draft for your README file:

Banking Domain Knowledge
Assets and Liabilities
In banking, assets refer to all financial resources owned by the bank, including cash, loans, investments, and properties. These assets generate income for the bank. Liabilities are the obligations of the bank, such as deposits and borrowings, which the bank must repay.

Non-Performing Assets (NPA)
Non-Performing Assets (NPA) are loans or advances that have stopped generating income for the bank, typically because the borrower has failed to pay interest or repay the principal amount for a specified period (usually 90 days). NPAs are a concern for banks as they affect profitability and indicate credit risk.

### Disbursed Amount
The disbursed amount is the total amount of money loaned or distributed by the bank to borrowers.

### Overdue Amount, Days Past Due (DPD), and Portfolio at Risk (PAR)
Overdue Amount refers to the amount that a borrower has failed to repay by the due date. Days Past Due (DPD) is the number of days by which a payment is late. Portfolio at Risk (PAR) is the portion of a bank's loan portfolio that is at risk of default.

If DPD > 0, the customer has defaulted

When DPD > 0, OSP is the amount that is PAR

### Credit Risk Types in Banking 
When DPD = 0, NDA(Non Deliquent Account)

0 < DPD > 30, SMA1(Standard monitoring account -1 )

31< DPD >60, SMA2(Standard monitoring account -2 )

61< DPD >90, SMA3(Standard monitoring account -3 )

91 < DPD >180, NPA

DPD > 180, written-off loan

### Why do banks Write-off loans?
Once a loan becomes an NPA after DPD crosses 180 days, the bank considers it unlikely that the full amount will be recovered.

Writing off the loan allows the bank to remove the NPA from its balance sheet, reflecting the true financial position. It also helps the bank in managing its capital and provisioning requirements. Additionally, writing off the loan does not mean that the bank stops its recovery efforts. The bank may continue to pursue the borrower and any collateral put up against the loan to recover as much of the outstanding amount as possible.
