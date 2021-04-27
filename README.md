# PREDICTING LOAN DEFAULTS USING MACHINE LEARNING ALGORITHMS

The dataset has a total of 100,000 rows, each of which contains details about a loan and the customer who received that loan. Information about whether or not a customer defaulted on a loan has been provided for 90,000 of the cases, while this information has not been provided for the remaining 10,000 cases. I used the 90,000 rows for which I have complete information to train and test the machine learning models. I have then used that model to predict whether or not a default occurred for the remaining 10,000 loans.

The columns contained in the dataset are:

• loan_id – The unique ID value for each loan.
• loan_default – Whether or not the customer defaulted on the loan (1 = did default, 0 = did not default). This is the primary outcome variable that you are trying to predict in this project.
• loan_amount – The total amount of money (in U.S. dollars) that was loaned to the customer,
• asset_cost – The total cost (in U.S. dollars) of the item for which the customer sought a loan.
• loan_to_value – The percentage of the total cost of the item that was paid for with the loan.
• customer_age – The age of the customer (in years).
• self_employed – Whether or not the customer is self-employed (1 = self-employed, 0 = not self-employed).
• voter_status_shared – Whether or not the customer voluntarily shared his or her voter status as part of the loan application process (1 = shared, 0 = did not share).
• drivers_license_shared – Whether or not the customer voluntarily shared his or her driver’s license information as part of the loan application process (1 = shared, 0 = did not share).
• passport_shared – Whether or not the customer voluntarily shared his or her passport information as part of the loan application process (1 = shared, 0 = did not share).
• credit_score – The customer’s FICO credit score at the time the loan was disbursed.
• credit_inquiries – The total number of times the customer’s credit has been checked as part of a loan application.
• total_credit_accounts – The total number of credit accounts that the customer has had in his or her lifetime.
• credit_history_length – The total length (in years) that the customer has had a credit history.
• active_credit_accounts – The total number of active credit accounts that the customer had at the time when the loan was disbursed.
• overdue_credit_accounts – The total number of credit accounts that the customer had that were overdue at the time when the loan was disbursed.
• average_credit_account_age – The average age of the customer’s credit accounts (in years).
• total_current_balance – The total amount of money (in U.S. dollars) that the customer currently owes to creditors.
• total_disbursed_loans – The total amount of money (in U.S. dollars) that the customer has received in loans during his or her lifetime.
• recent_loans – The total number of new loans that the customer has had the past six months.
• recent_defaulted_loans – The total number of loans on which the customer defaulted in the past six months.
