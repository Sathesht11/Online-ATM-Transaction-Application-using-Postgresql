# Online-ATM-Transaction-Application-using-Postgresql

## Mini Project

This project is based on money withdrawal.
After the money withdrawal, the withdrawal information need to be added on audit table automatically....


### Step 1: Customer table
Create customer table with follwing information.
Ac.no,name,address,balance,phone,email,branch code, and password.

### Step 2: Debit card table
Create Debit card table with follwing information...
Debit card no,account no,cvv,name,expiry month, and expiry year.

### Step 3: Audit table
Create Audit table with Trigger method. 
Time of withdrawn,ac.no,withdrawn amount,Transaction id, and balance.
    1. Trigger function need to be created after updating the customer table.
    2. 8 or 10 digits of transaction id need to generate.

# Data
Based on basic bank client information, random data was created to test this application.
