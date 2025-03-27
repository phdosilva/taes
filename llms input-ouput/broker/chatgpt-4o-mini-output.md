1. Req 5, 6  
    Conflict Explanation: The system cannot invoice broker accounts both once per year and once per month at the same time for the same accounts, as these are conflicting frequencies.

2. Req 8, 42  
    Conflict Explanation: A broker is allowed to delete their subscribers' accounts and associated data (Req 8), but Req 42 permits deleting only subscriber accounts, not associated invoices, which creates a conflict in terms of data deletion authority.

3. Req 9, 40  
    Conflict Explanation: Req 9 states invoices shall only be stored in a subscriber account, but Req 40 forbids deleting invoices, implying that invoices cannot be moved or deleted from accounts, which conflicts with the idea of only storing invoices in subscriber accounts.

4. Req 10, 11  
    Conflict Explanation: Req 10 forbids PBX accounts from having virtual circuits, but Req 11 mandates deactivating virtual circuits for PBX accounts that don't pay for the service, which implies that PBX accounts can have virtual circuits before deactivation, creating a conflict.

5. Req 13, 12  
    Conflict Explanation: Req 13 gives the administrator exclusive access to the rate table and specifies that brokers' access is controlled by an access list, while Req 12 states that brokers should have access to the rate table, creating a conflict regarding access authority.

6. Req 14, 15  
    Conflict Explanation: Req 14 mandates that the system automatically assigns unique identification numbers to all registered users, while Req 15 allows users to customize the prefix of their identification numbers, which could conflict with the requirement for uniqueness.

7. Req 21, 22  
    Conflict Explanation: Req 21 supports invoicing and payments in multiple currencies, but Req 22 mandates that monthly automated backups are performed and a data recovery plan is in place, which could create conflicting requirements around data management, particularly with different currency formats.

8. Req 33, 34  
    Conflict Explanation: Req 33 mandates an audit once per month, while Req 34 mandates an audit once per week, creating a conflict in the frequency of audits.

9. Req 35, 36  
    Conflict Explanation: Req 35 prevents account creation from foreign countries, but Req 36 mandates that foreign accounts be stopped if inactive for three months, creating a contradiction in the treatment of foreign accounts.

10. Req 46, 48  
     Conflict Explanation: Req 46 states that any invoice older than 60 days shall be flagged as overdue, but Req 48 states that overdue invoices must never be deleted, creating a conflict regarding the handling of overdue invoices.

11. Req 49, 51  
     Conflict Explanation: Req 49 grants admin users the right to view closed broker accounts, while Req 51 prohibits admin users from reopening closed accounts. This creates a conflict regarding administrative authority over closed accounts.

12. Req 55, 56, 57  
     Conflict Explanation: Req 55 states that any foreign account that becomes inactive shall automatically be locked, Req 56 says that locked foreign accounts will be closed after 30 days, but Req 57 states that no inactive foreign account shall ever be closed, creating a contradiction regarding the treatment of inactive foreign accounts.
