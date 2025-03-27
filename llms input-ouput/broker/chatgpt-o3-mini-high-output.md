1. Req 2, 3, 4  
    Conflict Explanation: Req 2 mandates sending an email notification when an account is locked and Req 3 mandates sending an SMS notification, but Req 4 prohibits sending the SMS if the email has already been sent.

2. Req 5, 6  
    Conflict Explanation: Req 5 requires invoicing broker accounts once per year while Req 6 requires invoicing them once per month, creating incompatible invoicing frequencies.

3. Req 7, 40, 42, 47, 48  
    Conflict Explanation: Reqs 7 and 40 forbid deletion of invoices, yet Req 42 allows brokers to delete associated invoices when deleting subscriber accounts, and Req 47 mandates scheduling flagged invoices for potential deletion—this contradicts Req 48, which states that overdue invoices shall never be deleted.

4. Req 10, 11  
    Conflict Explanation: Req 10 forbids PBX accounts from having virtual circuits, but Req 11 directs the system to deactivate virtual circuits for PBX accounts that do not pay, implying that such circuits may initially exist.

5. Req 12, 13  
    Conflict Explanation: Req 12 permits brokers direct access to the rate table, while Req 13 restricts rate table access solely to the administrator who must manage broker access.

6. Req 33, 34  
    Conflict Explanation: Req 33 calls for an audit of all accounts once per month, whereas Req 34 requires an audit once every week, establishing contradictory audit frequencies.

7. Req 39, 44  
    Conflict Explanation: Req 44 mandates that the system automatically creates a unique number for a subscription account at enrolment, conflicting with Req 39, which allows brokers to assign a user-specified number for a new subscription account.

8. Req 32, 45  
    Conflict Explanation: Req 32 prohibits brokers from modifying data in closed accounts, yet Req 45 allows brokers to revise data in previously closed accounts.

9. Req 41, 43  
    Conflict Explanation: Req 41 requires overdue invoices to be highlighted in the dashboard, while Req 43 states that overdue invoices shall not be highlighted, resulting in a direct contradiction.

10. Req 50, 51  
     Conflict Explanation: Req 50 permits any user who can view closed broker accounts to reopen them, but Req 51 explicitly prohibits admin users from reopening closed broker accounts.

11. Req 52, 53, 54  
     Conflict Explanation: Req 52 requires that if the system integrates with the Payment Gateway, payment history must be recorded in the invoice table; Req 53 then mandates monthly backups of that table if payment history is recorded; however, Req 54 prohibits monthly backups of the invoice table when integrated with the Payment Gateway.

12. Req 55, 56, 57  
     Conflict Explanation: Req 55 mandates that inactive foreign accounts be automatically locked, Req 56 requires that locked foreign accounts be closed after 30 days, but Req 57 forbids closing any inactive foreign account.
