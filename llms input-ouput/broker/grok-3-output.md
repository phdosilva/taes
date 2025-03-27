1\. Req 4, 2, 3    
   Conflict Explanation: Req 2 mandates an email notification when an account is locked, and Req 3 mandates an SMS notification for the same event, but Req 4 states that if a user receives an email notification, they will not receive the same notification via SMS, making it impossible to satisfy both Req 2 and Req 3 simultaneously.

2\. Req 5, 6    
   Conflict Explanation: Req 5 specifies that broker accounts are invoiced once per year using CDR, while Req 6 specifies invoicing once per month using CDR, presenting incompatible frequencies for the same operation.

3\. Req 7, 40, 42    
   Conflict Explanation: Req 7 and Req 40 both forbid deleting invoices, but Req 42 allows a broker to delete subscribers’ accounts and associated invoices, directly contradicting the prohibition in Req 7 and Req 40\.

4\. Req 8, 9, 7    
   Conflict Explanation: Req 8 allows a broker to delete subscribers’ accounts and associated data, Req 9 states that invoices are stored only in subscriber accounts, and Req 7 forbids deleting invoices. Together, these create a logical impossibility: deleting a subscriber account (per Req 8\) would delete its invoices (per Req 9), violating Req 7\.

5\. Req 10, 11    
   Conflict Explanation: Req 10 forbids PBX accounts from having virtual circuits, while Req 11 mandates deactivating virtual circuits for PBX accounts that don’t pay, implying virtual circuits can exist in PBX accounts, directly contradicting Req 10\.

6\. Req 12, 13    
   Conflict Explanation: Req 12 allows brokers to access the rate table, while Req 13 restricts access to only the administrator, who creates an access list for brokers, contradicting the direct access granted in Req 12\.

7\. Req 14, 15    
   Conflict Explanation: Req 14 mandates that the system automatically assign unique identification numbers to all users, while Req 15 allows users to customize the prefix of their identification numbers, conflicting with the system’s automatic assignment.

8\. Req 33, 34    
   Conflict Explanation: Req 33 specifies that an audit of all accounts occurs once per month, while Req 34 specifies once every week, presenting incompatible frequencies for the same operation.

9\. Req 41, 43    
   Conflict Explanation: Req 41 mandates highlighting overdue invoices in the dashboard, while Req 43 states the system shall not highlight overdue invoices in the dashboard, directly contradicting each other.

10\. Req 44, 39    
    Conflict Explanation: Req 44 mandates that the system automatically create a unique number for subscription accounts at enrollment, while Req 39 allows brokers to assign a user-specified number, conflicting with the system’s automatic assignment.

11\. Req 32, 45    
    Conflict Explanation: Req 32 forbids brokers from modifying data in closed accounts, while Req 45 allows brokers to revise data in all previously closed accounts, directly contradicting each other.

12\. Req 47, 48    
    Conflict Explanation: Req 47 mandates that all flagged invoices (overdue per Req 46\) be scheduled for a cleanup cycle that may include deletion, while Req 48 states overdue invoices shall never be deleted, directly contradicting each other.

13\. Req 49, 50, 51    
    Conflict Explanation: Req 49 allows any admin user to view closed broker accounts, Req 50 states that any user who can view closed broker accounts can reopen them, and Req 51 forbids any admin user from reopening closed broker accounts. Together, these create a logical impossibility: an admin can view (Req 49), thus can reopen (Req 50), but cannot reopen (Req 51).

14\. Req 52, 53, 54    
    Conflict Explanation: Req 52 requires recording payment history in the invoice table if the system integrates with the Payment Gateway, Req 53 mandates monthly backups of the invoice table if payment history is recorded there, and Req 54 forbids monthly backups of the invoice table if the system integrates with the Payment Gateway. Together, these create a logical impossibility: integration triggers recording (Req 52), recording triggers backups (Req 53), but integration forbids backups (Req 54).

15\. Req 55, 56, 57    
    Conflict Explanation: Req 55 mandates locking any inactive foreign account, Req 56 mandates closing locked foreign accounts after 30 days, and Req 57 forbids closing any inactive foreign account. Together, these create a logical impossibility: an inactive account is locked (Req 55), then closed after 30 days (Req 56), but cannot be closed (Req 57).  