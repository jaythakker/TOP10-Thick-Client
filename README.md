# TOP 10 Thick-Client Application Security Vulnerabilities
This repository lists TOP 10 vulnerabilities found during Thick Client Application penetration testing. 

Thick client application penetration is one of the gray area where-in lots of articles are available to test for the vulnerabilties but no proper guideline is available to lookup for. After performing penetration testing for large set of thick client applications a pattern could be drawn out to identify common issues in them. Hence over here an effort has been made to list down most common vulnerabilities found in Thick Client applications. 


## TOP 10
- T1: DLL Hijacking
- T2: DLL Injection
- T3: Insecure Data Storage - Data Stored in Files, Registry.
- T4: Hardcoded Credentials
- T5: Insecure Communication - Vulnerabilities like Clear text communication, TLS/SSL related Vulnerabilities.
- T6: Improper Input Validation
- T7: Weak Permissions
- T8: Insecure Authorization
- T9: Path Interception
- T10: Missing Memory Protection


**T1: DLL Hijacking**
DLL Hijacking is a vulnerability wherein attacker places malicious DLL in the user controlled search order of the application to gain system privileges. 

**T2: DLL Injection**
DLL Injection is a process hooking technique wherein maclicious code is inserted into running application. 

**T3: Insecure Data Storage**
In this vulnerability all the directories, files and registry are checked to determine any sensitive information.

**T4: Hardcoded Credentials**
The application is reverse engineered to check for harcoded user information, tokens, etc.

**T5: Insecure Communication**
Communication releated vulnerabilities like plain text or weak SSL implemention technique is checked in this section.

**T6: Improper Input Validation**
Based upon the functionailty attack vectors like SQL Injection, CSV Injections, etc are determined.

**T7: Weak Permissions**
Oftenly the application has misconfigured permissions allowing full control to all the users on the system. Based upon the functionailty this may be chained with other vulnerabilities to perform severe attacks.

**T8: Insecure Authorization**
In this vulnerabilities likes Direct URL access over browser is checked to determine access control mechanisms implemention in the application.

**T9: Path Interception**
In this vulnerability if the path has one or more spaces and is not surrounded by quotation marks (e.g., C:\unsafe path with space\program.exe vs. "C:\safe path with space\program.exe") then an attacker can place an executable in a higher-level directory of the path, and Windows will resolve that executable instead of the intended executable. 

**T10: Missing Memory Protection**
ASLR, DEP, CFG needs to implemented for all application at source code level. This would decrease the chances of severe vulnerabilities like Buffer Overflow.


Feel free to get in touch with me if you have any suggestions.


**Disclaimer:**
Please note, my aim is not to try to override any available standard for thick client application penetration testing. This TOP 10 is a result based upon my experience.
