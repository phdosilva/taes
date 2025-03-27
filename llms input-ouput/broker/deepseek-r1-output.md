1\. Req 2, 3, 4    
   Conflict Explanation: Req 2 and 3 mandate sending both email and SMS upon account lock, but Req 4 prevents SMS if email is sent, creating a contradiction.

2\. Req 5, 6    
   Conflict Explanation: Req 5 specifies annual invoicing, while Req 6 mandates monthly invoicing for the same accounts.

3\. Req 7, 40, 42    
   Conflict Explanation: Req 7 and 40 forbid invoice deletion, but Req 42 allows brokers to delete subscriber invoices.

4\. Req 12, 13    
   Conflict Explanation: Req 12 grants brokers access to the rate table, while Req 13 restricts access to administrators only.

5\. Req 37, 13    
   Conflict Explanation: Req 37 allows brokers to print the rate table, conflicting with Req 13’s restriction of rate table access to administrators.

6\. Req 41, 43    
   Conflict Explanation: Req 41 mandates highlighting overdue invoices in the dashboard, while Req 43 prohibits it.

7\. Req 32, 45    
   Conflict Explanation: Req 32 forbids modifying closed accounts, but Req 45 allows brokers to revise closed accounts.

8\. Req 33, 34    
   Conflict Explanation: Req 33 requires monthly audits, while Req 34 mandates weekly audits.

9\. Req 46, 47, 48    
   Conflict Explanation: Req 47 schedules flagged invoices for potential deletion, but Req 48 prohibits deleting overdue invoices (flagged by Req 46).

10\. Req 49, 50, 51    
    Conflict Explanation: Req 50 permits users who can view closed accounts (admins per Req 49\) to reopen them, but Req 51 explicitly forbids admins from reopening closed accounts.

11\. Req 52, 53, 54    
    Conflict Explanation: Req 53 mandates monthly backups if payment history is recorded (triggered by Req 52’s integration), but Req 54 prohibits backups if integrated.

12\. Req 55, 56, 57    
    Conflict Explanation: Req 55 and 56 lock and close inactive foreign accounts, but Req 57 prohibits closing inactive foreign accounts.

13\. Req 39, 44    
    Conflict Explanation: Req 44 mandates auto-generated unique numbers for subscription accounts, while Req 39 allows brokers to assign user-specified numbers.  