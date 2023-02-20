# Online-ATM-Transaction-Application-using-Postgresql

## Mini Project

This project is based on money withdrawal.
After the money withdrawal, the withdrawal information need to be added on audit table automatically....


###Step 1: Customer table
Create customer table with follwing information
Ac.no,name,address,balance,phone,email,branch code,securiy code

###Step 2: Debit card table
Create Debit card table with follwing information...
Debit card no,account no,cvv,name,expiry month,expiry year

###Step 3: Audit table
Create Audit table with Trigger method 
Time of withdrawn,ac.no,withdrawn amount,Transaction id,balance)
    # Trigger function need to be created after updating the customer table
    # 8 or 10 digits of transaction id need to generate
