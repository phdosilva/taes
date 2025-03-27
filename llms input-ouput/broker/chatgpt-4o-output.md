1\. Req 1, 4    
   Conflict Explanation: Req 1 triggers both email and SMS notifications after account lock, but Req 4 forbids sending the same notification via SMS if it has already been sent via email.

2\. Req 5, 6    
   Conflict Explanation: Req 5 mandates annual invoicing for broker accounts, while Req 6 mandates monthly invoicing for the same using CDR. These frequencies conflict.

3\. Req 8, 9, 42    
   Conflict Explanation: Req 8 and Req 42 allow brokers to delete subscriber accounts and associated invoices, but Req 9 states invoices are only stored in subscriber accounts, and deletion of the account would mean deleting the invoice. This contradicts Req 7 and Req 40, which forbid invoice deletion.

4\. Req 7, 42    
   Conflict Explanation: Req 42 allows brokers to delete invoices, but Req 7 forbids deletion of issued invoices.

5\. Req 40, 42    
   Conflict Explanation: Req 42 allows deletion of invoices, but Req 40 forbids it.

6\. Req 10, 11    
   Conflict Explanation: Req 10 forbids PBX accounts from having virtual circuits, but Req 11 talks about deactivating virtual circuits for PBX accounts—implying they do have them.

7\. Req 12, 13    
   Conflict Explanation: Req 12 gives brokers access to the rate table, but Req 13 restricts access to administrators only, who manage broker access separately.

8\. Req 33, 34    
   Conflict Explanation: Req 33 mandates monthly account audits, while Req 34 mandates weekly account audits. These frequencies are incompatible for the same audit.

9\. Req 41, 43    
   Conflict Explanation: Req 41 states overdue invoices will be highlighted in the dashboard, but Req 43 says they shall not be highlighted.

10\. Req 45, 32    
    Conflict Explanation: Req 45 allows brokers to revise data in previously closed accounts, but Req 32 forbids brokers from modifying data in closed accounts.

11\. Req 47, 48    
    Conflict Explanation: Req 47 says flagged invoices (overdue) may be scheduled for deletion, but Req 48 forbids deletion of overdue invoices.

12\. Req 50, 51    
    Conflict Explanation: Req 50 allows any user who can view closed broker accounts to reopen them, but Req 51 forbids any admin user from reopening closed broker accounts. Since admin users are allowed to view closed accounts (Req 49), Req 50 implies they should be able to reopen, contradicting Req 51\.

13\. Req 52, 54    
    Conflict Explanation: Req 52 mandates integration with Payment Gateway and recording payment history in the invoice table. If this happens, Req 53 requires monthly backups of the table, while Req 54 forbids them.

14\. Req 55, 56, 57    
    Conflict Explanation: Req 55 locks inactive foreign accounts, Req 56 says locked foreign accounts are closed after 30 days, but Req 57 says no inactive foreign account shall ever be closed. These three cannot all be true simultaneously.
