1. **Req 2 and Req 48**  
    Conflict Explanation: Req 2 mandates real-time processing, whereas Req 48 states the system shall only provide batch (non–real-time) processing. These requirements cannot both be satisfied.

2. **Req 7 vs. Req 40 and Req 41**  
    Conflict Explanation: Req 7 requires a non-relational database for the System Administration Module; Req 40 and Req 41 require a fully relational (SQL-based) database for that same module and the overall system. They directly contradict one another.

3. **Req 8 and Req 57**  
    Conflict Explanation: Req 8 says System Administration “shall not be accessible with screen‑reading software or other accessibility software,” whereas Req 57 says it “shall be accessible with screen‑reading software and other accessibility software.” These two statements cannot both hold true.

4. **Req 57 and Req 85**  
    Conflict Explanation: Req 57 requires accessibility with screen‑reading and related software; Req 85 explicitly forbids any accessibility software for the System Administration Module.

5. **Req 57 and Req 95**  
    Conflict Explanation: Req 57 requires accessibility software support; Req 95 states System Administration “shall not be accessible with screen‑reading or any other accessibility software.” Direct contradiction.

6. **Req 17 and Req 74**  
    Conflict Explanation: Req 17 says the System Administration Module “shall only support up to 10 locations”; Req 74 says it “must support a library system with 50 locations.” These upper limits conflict.

7. **Req 17 and Req 98**  
    Conflict Explanation: Req 17 limits support to 10 locations, but Req 98 demands support for a system with 100 locations. They cannot both be satisfied.

8. **Req 74 and Req 106**  
    Conflict Explanation: Req 74 demands support for a library system with 50 locations; Req 106 prohibits supporting more than 25 locations. This is a direct conflict.

9. **Req 106 and Req 98**  
    Conflict Explanation: Req 106 disallows more than 25 locations; Req 98 requires support for 100 locations. They are mutually exclusive.

10. **Req 29 and Req 109**  
     Conflict Explanation: Both apply “if web‑browser based.” Req 29 says System Administration “shall be accessible through Google Chrome and Apple Safari only,” while Req 109 says it “shall be accessible through Microsoft Internet Explorer and Mozilla Firefox.” They cannot both be true.

11. **Req 75 and Req 109**  
     Conflict Explanation: Both apply “if web‑browser based.” Req 75 forbids accessibility via Internet Explorer or Firefox; Req 109 requires accessibility via Internet Explorer and Firefox. Direct contradiction.

12. **Req 119, Req 120 vs. Req 121**  
     Conflict Explanation:

    * Req 119 and Req 120 require accessibility through both Google Chrome and Apple Safari.

    * Req 121 says that “if web‑browser based, System Administration must be accessible through exactly one browser only.”  
       Having to support *two* specific browsers contradicts “exactly one.”

13. **Req 42 vs. (Req 3, Req 6, Req 29, Req 52, Req 75, Req 109, Req 119, Req 120, Req 121\)**  
     Conflict Explanation:

    * Req 42: “System Administration shall be accessible **only** through a mobile application.”

    * The others require or allow access via a Mac client, a Windows client, or a specific web browser.  
       “Only through a mobile application” cannot coexist with any requirement mandating or forbidding other modes (Mac, Windows, browsers, etc.).

14. **Req 61 and Req 77**  
     Conflict Explanation:

    * Req 61: “System Administration shall operate on a Linux or Solaris server.”

    * Req 77: “System Administration shall operate on a Windows server **only**.”  
       The requirement for Linux/Solaris conflicts with “Windows‑only.”

15. **Req 113, Req 114, Req 115** (Three‑way conflict)

    * Req 113: “All modules that can operate on Windows servers shall also operate on Linux servers.”

    * Req 114: “All modules that operate on Linux servers must also operate on Solaris servers.”

    * Req 115: “No module that operates on Windows servers can operate on Solaris servers.”  
       Together, these three impose an impossible combination (requiring Solaris support yet forbidding Solaris support for the same module).

16. **Req 116, Req 117, Req 118** (Three‑way conflict)

    * Req 116: “All incremental backups are classified as scheduled tasks.”

    * Req 117: “All scheduled tasks are classified as full backups.”

    * Req 118: “No incremental backup can ever be classified as a full backup.”  
       These create a logical impossibility (incremental backups would have to be and not be full backups).

17. **Req 122 and Req 124**  
     Conflict Explanation:

    * Req 122: “All SFTP connections to Vendor A follow the system’s default SFTP mode settings” (which is active mode per Req 123).

    * Req 124: “Vendor A requires passive mode, overriding any default.”  
       One says the default (active) always applies to Vendor A; the other says Vendor A overrides that default to passive.

18. **Req 110, Req 111, Req 112** (Three‑way conflict)

    * Req 110: “The system shall treat Item records as Bibliographic records for batch updates.”

    * Req 111: “The system shall treat Bibliographic records as Order records for record validation.”

    * Req 112: “The system shall never treat Item records and Order records as equivalent.”  
       By transitivity, treating Item \= Bibliographic and Bibliographic \= Order would imply Item \= Order, contradicting Req 112’s prohibition.
