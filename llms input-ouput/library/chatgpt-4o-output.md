1\. Req 2, 48    
   Conflict Explanation: Req 2 mandates real-time processing, while Req 48 states the system shall only provide batch processing and not real-time processing.

2\. Req 3, 29, 42, 52, 57, 75, 109, 119, 120, 121    
   Conflict Explanation:    
   \- Req 3 states System Admin Module is accessible only via Mac-compatible client.    
   \- Req 29, 75, 109, 119, 120 mention various browsers (Safari, Chrome, IE, Firefox).    
   \- Req 42 states access is only via mobile application.    
   \- Req 52 says access is via web-browser or Windows-compatible client.    
   \- Req 57 says it's accessible with accessibility software.    
   \- Req 121 requires access through exactly one browser.    
   These collectively define mutually exclusive access methods that cannot all be true simultaneously.

3\. Req 8, 57, 85, 95    
   Conflict Explanation:    
   \- Req 8 and Req 95 state the System Administration Module must not be accessible with any accessibility software.    
   \- Req 57 mandates that it must be accessible with accessibility software.    
   \- Req 85 also prohibits accessibility software access.    
   These contradict directly.

4\. Req 7, 40, 41    
   Conflict Explanation:    
   \- Req 7 mandates a non-relational DB back-end.    
   \- Req 40 and 41 mandate a fully relational, SQL-based DB system for the system and the Admin Module.    
   This is a direct contradiction regarding the type of database.

5\. Req 17, 74, 98, 106    
   Conflict Explanation:    
   \- Req 17 says the System Admin Module supports only up to 10 locations.    
   \- Req 106 says it must not support more than 25 locations.    
   \- Req 74 says it must support 50 locations.    
   \- Req 98 says it must support 100 locations.    
   These are mutually exclusive capacity requirements.

6\. Req 30, 61, 77, 113, 114, 115    
   Conflict Explanation:    
   \- Req 30 and 77 say System Admin runs on Windows server only.    
   \- Req 61 says it runs on Linux or Solaris.    
   \- Req 113 says if a module operates on Windows, it must also operate on Linux.    
   \- Req 114 says all Linux modules must operate on Solaris.    
   \- Req 115 says no module on Windows can run on Solaris.    
   These together create a circular conflict about supported OS platforms.

7\. Req 116, 117, 118    
   Conflict Explanation:    
   \- Req 116 says all incremental backups are scheduled tasks.    
   \- Req 117 says all scheduled tasks are full backups.    
   \- Req 118 says no incremental backup can be classified as a full backup.    
   This forms a logical impossibility: incremental → scheduled → full, but incremental ≠ full.

8\. Req 112, 110, 111    
   Conflict Explanation:    
   \- Req 110 equates Item and Bibliographic records.    
   \- Req 111 equates Bibliographic and Order records.    
   \- Req 112 states Item and Order records can never be equivalent.    
   Together this creates a contradiction via transitivity: Item \= Bibliographic \= Order ⇒ Item \= Order (but this is forbidden).

9\. Req 122, 123, 124    
   Conflict Explanation:    
   \- Req 122 states Vendor A must follow system’s default SFTP mode.    
   \- Req 123 says default is always active mode.    
   \- Req 124 says Vendor A requires passive mode and overrides default.    
   These three cannot logically coexist.

10\. Req 121, 29, 75, 109, 119, 120    
    Conflict Explanation:    
    \- Req 121 says System Admin must be accessible via exactly one browser.    
    \- The others list multiple browsers (Chrome, Safari, IE, Firefox).    
    Multiple allowed browsers violate the "exactly one" constraint.
