1. **Req 2, 3, 4**  
    Conflict Explanation: \#2 and \#3 mandate sending both email and SMS when an account is locked, but \#4 forbids sending an SMS if an email was already sent for the same event.

2. **Req 5, 6**  
    Conflict Explanation: \#5 requires invoicing broker accounts once per year, while \#6 requires invoicing them once per month (both using CDR).

3. **Req 7, 9, 40, 8, 42**  
    Conflict Explanation: \#7 and \#40 forbid deleting issued invoices, and \#9 specifies invoices reside only in subscriber accounts. However, \#8 and \#42 require the broker to be able to delete subscriber accounts (and their associated data/invoices), creating a direct contradiction.

4. **Req 10, 11**  
    Conflict Explanation: \#10 forbids PBX accounts from having virtual circuits, while \#11 instructs the system to deactivate virtual circuits for PBX accounts (implying they do have them).

5. **Req 12, 13, 37**  
    Conflict Explanation: \#12 and \#37 allow the broker to access and even print the rate table, but \#13 states that only the administrator shall have access to the rate table.

6. **Req 32, 45**  
    Conflict Explanation: \#32 states that brokers shall not modify data in closed accounts, whereas \#45 says brokers can revise data in previously closed accounts.

7. **Req 33, 34**  
    Conflict Explanation: \#33 requires a monthly audit of all accounts, while \#34 requires a weekly audit of all accounts.

8. **Req 46, 47, 48**  
    Conflict Explanation: \#46 flags invoices older than 60 days as overdue, \#47 mandates scheduling all flagged (overdue) invoices for a cleanup cycle (possible deletion), but \#48 says overdue invoices shall never be deleted.

9. **Req 49, 50, 51**  
    Conflict Explanation: \#49 authorizes admins to view closed broker accounts; \#50 declares that anyone who can view them can also reopen them; \#51 forbids admins from reopening any closed broker account.

10. **Req 55, 56, 57**  
     Conflict Explanation: \#55 says an inactive foreign account is locked automatically, \#56 says any locked foreign account is closed after 30 days, but \#57 says no inactive foreign account shall ever be closed.

11. **Req 52, 53, 54**  
     Conflict Explanation: If the system integrates with the Payment Gateway (\#52), it must record payment history in the invoice table, which triggers monthly backups (\#53). However, \#54 says that if the system integrates with the Payment Gateway, it shall not perform monthly backups—an outright contradiction.
