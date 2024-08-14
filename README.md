# Powershell
My Powershell Scripts

**- IPV4_Hider :**
This script replaces IP addresses found in file given in parameter by a motif given in input. A backup file is generated and the number of IP addresses replaced is prompted also.

**- BruteforceLocalCreds :**
This script leverages _ValidateCredentials_ Powershell method to bruteforce password of the account given in parameter, in  the context of the machine.

**- ServiceSecurePathChecker :**
This script is built to find services on host and check wether there are in a secure location according _Defender_ (the secure path list is based on a _Defender portal_ security recommendation).  /!\ In order to enumerate services, administrative rights are required. An option has been added to interpret environment variables (_$env:<Name>_).
