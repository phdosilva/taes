1. Req 3, 6, 42, 52  
    Conflict Explanation: Requirements 3 and 6 mandate access only via macOS-compatible clients, while Requirement 42 restricts access to a mobile application only, and Requirement 52 requires access through a web-browser or Windows-compatible client. These platform restrictions cannot all be met simultaneously.

2. Req 8, 57, 85, 95  
    Conflict Explanation: Requirements 8, 85, and 95 forbid accessibility via screen-reading or other accessibility software, yet Requirement 57 mandates that the system be accessible with such software, creating a direct contradiction.

3. Req 29, 75, 109, 121  
    Conflict Explanation: Requirement 29 (and 75 by exclusion) restricts web-browser access to Google Chrome and Apple Safari, while Requirement 109 mandates accessibility via Microsoft Internet Explorer and Mozilla Firefox; Requirement 121 further limits access to exactly one browser—these browser requirements are mutually exclusive.

4. Req 7, 40, 41  
    Conflict Explanation: Requirement 7 specifies a non-relational database back-end for the Administration Module, but Requirements 40 and 41 demand a fully relational (SQL-based) database system, making the database technology incompatible.

5. Req 30, 61, 77, 113  
    Conflict Explanation: Requirements 30 and 77 require operation solely on Windows servers, whereas Requirement 61 requires operation on Linux or Solaris servers, and Requirement 113 insists that any module running on Windows must also run on Linux. These server OS requirements cannot coexist.

6. Req 116, 117, 118  
    Conflict Explanation: Requirement 116 classifies incremental backups as scheduled tasks, Requirement 117 states that all scheduled tasks are full backups, and Requirement 118 prohibits any incremental backup from being classified as a full backup—an inherent contradiction.

7. Req 17, 74, 98, 106  
    Conflict Explanation: Requirement 17 limits support to 10 locations, Requirement 74 demands support for 50 locations, Requirement 98 for 100 locations, while Requirement 106 restricts support to a maximum of 25 locations; these conflicting capacity limits cannot be reconciled.

8. Req 110, 111, 112  
    Conflict Explanation: Requirement 110 directs that Item records be treated as Bibliographic records, and Requirement 111 directs that Bibliographic records be treated as Order records, which implies transitivity that would equate Item and Order records—explicitly forbidden by Requirement 112\.

9. Req 122, 123, 124  
    Conflict Explanation: Requirement 123 defines the system’s default SFTP mode as active and Requirement 122 requires that Vendor A connections follow this default, yet Requirement 124 mandates that Vendor A use passive mode, creating an unsolvable SFTP mode conflict.
