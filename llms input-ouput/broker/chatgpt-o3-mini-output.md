1. Req 2, 3, 4  
    Conflict Explanation: Requirements 2 and 3 mandate that both an email and an SMS be sent upon account lock, while Requirement 4 prevents an SMS from being sent if an email has already been sent.

2. Req 5, 6  
    Conflict Explanation: Requirement 5 specifies invoicing broker accounts once per year, whereas Requirement 6 specifies invoicing them once per month.

3. Req 7, 40, 42, 47  
    Conflict Explanation: Requirements 7 and 40 forbid deletion of invoices, but Requirement 42 permits brokers to delete associated invoices when deleting subscriber accounts, and Requirement 47 mandates a cleanup cycle that may include invoice deletion.

4. Req 10, 11  
    Conflict Explanation: Requirement 10 forbids PBX accounts from having virtual circuits, yet Requirement 11 requires deactivation of virtual circuits for PBX accounts that do not pay, implying they can exist.

5. Req 12, 13, 37  
    Conflict Explanation: Requirement 12 (and 37\) allow brokers direct access to or printing of the rate table, while Requirement 13 restricts rate table access solely to administrators.

6. Req 41, 43  
    Conflict Explanation: Requirement 41 requires overdue invoices to be highlighted in the dashboard, but Requirement 43 explicitly prohibits highlighting overdue invoices.

7. Req 32, 45  
    Conflict Explanation: Requirement 32 prohibits modifications to data in closed broker accounts, whereas Requirement 45 permits revising data in such accounts.

8. Req 33, 34  
    Conflict Explanation: Requirement 33 mandates account audits once per month, while Requirement 34 mandates weekly audits, resulting in inconsistent frequencies.

9. Req 56, 57  
    Conflict Explanation: Requirement 56 states that locked foreign accounts should be closed after 30 days, but Requirement 57 forbids closing any inactive foreign account.

10. Req 49, 50, 51  
     Conflict Explanation: Requirement 49 allows admin users to view closed broker accounts and Requirement 50 extends the ability to reopen them to all viewers, yet Requirement 51 specifically prohibits admin users from reopening closed accounts.

11. Req 52, 53, 54  
     Conflict Explanation: Requirement 52 implies that with Payment Gateway integration, payment history is recorded in the invoice table, which according to Requirement 53 should trigger monthly backups; however, Requirement 54 contradicts this by forbidding monthly backups when integrating with the Payment Gateway.

12. Req 14, 39, 44  
     Conflict Explanation: Requirements 14 and 44 enforce automatic assignment of unique identification numbers for new accounts, while Requirement 39 permits brokers to assign user-specified numbers, creating a contradiction.
