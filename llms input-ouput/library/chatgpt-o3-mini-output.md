1. Req 2 and 48  
    Conflict Explanation: Requirement 2 mandates real-time processing while Requirement 48 specifies that the system provides only batch processing, which are mutually exclusive.

2. Req 7, 40, and 41  
    Conflict Explanation: Requirement 7 requires a non‑relational database back-end, whereas Requirements 40 and 41 require a fully relational, SQL‑based database system.

3. Req 8, 57, and 95  
    Conflict Explanation: Requirements 8 and 95 state that the System Administration shall not be accessible with screen‑reading or other accessibility software, while Requirement 57 mandates accessibility with screen‑reading and screen‑magnification software.

4. Req 17, 74, 98, and 106   
    Conflict Explanation: Requirement 17 limits the system to up to 10 locations; Requirement 74 demands support for 50 locations; Requirement 98 requires support for 100 locations; and Requirement 106 prohibits supporting more than 25 locations.

5. Req 116, 117, and 118  
    Conflict Explanation: Requirement 116 classifies incremental backups as scheduled tasks and Requirement 117 classifies all scheduled tasks as full backups, yet Requirement 118 forbids any incremental backup from ever being classified as a full backup.

6. Req 29, 42, 52, 75, 109, and 121  
    Conflict Explanation: Requirement 29 limits browser access to Google Chrome and Apple Safari, while Requirement 42 restricts access to a mobile application only, and Requirement 52 permits access via a web-browser or Windows‑compatible client. Moreover, Requirement 75 excludes Internet Explorer and Mozilla Firefox, conflicting with Requirement 109 which mandates their support, and Requirement 121 restricts web‑browser access to exactly one browser.

7. Req 30, 61, 77, 113, 114, and 115  
    Conflict Explanation: Requirements 30 and 77 mandate that the System Administration Module operate only on a Windows server, whereas Requirement 61 requires operation on a Linux or Solaris server. Additionally, Requirement 113 demands Windows modules also run on Linux, Requirement 114 requires Linux modules to run on Solaris, and Requirement 115 prohibits any Windows module from operating on Solaris.

8. Req 122, 123, and 124  
    Conflict Explanation: Requirement 123 sets the system’s default SFTP mode as always active, and Requirement 122 states that Vendor A’s SFTP connections follow this default; however, Requirement 124 mandates that Vendor A’s SFTP connections use passive mode, directly contradicting the default active mode.
