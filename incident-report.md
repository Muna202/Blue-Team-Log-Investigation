BLUE TEAM LOG INVESTIGATION LAB

OVERVIEW:
This lab simulates suspicious login attempts on a linux system and investigates the resulting authentication logs.

TOOLS USED:
Kali linux
Linux authentication logs
Google Cloud

INVESTIGATION STEPS:

1. Generated failed login attempts by using invalid credentials through Kali Linux terminal (via Google Cloud)
2. Analysed /var/log/auth.log
3. Identified failed/invalid authentication events.

FINDINGS:
Multiple failed login attempts were detected for the user "fakeuser."

INDICATORS OF COMPROMISE:
Repeated failed authentication attempts

CONCLUSION:
The activity resembles brute force login attemots and would require further monitoring and mitigation in a formal SOC environment.
