# SIEM-Threat-Detection-Lab-Splunk-
This project demonstrates how to detect and analyze security threats using a SIEM (Splunk). The focus is on identifying brute-force attacks and account compromise through log analysis and correlation.
Tools Used
Splunk (SIEM)
Log analysis
SPL (Search Processing Language)
Dataset

Custom authentication logs including:

LOGIN_FAIL
LOGIN_SUCCESS
FILE_ACCESS
FILE_DOWNLOAD

Detection Logic
1. Brute Force Detection

Identifies IP addresses with multiple failed login attempts.

2. Account Compromise Detection

Detects IPs with repeated failed logins followed by a successful login.

3. Post-Compromise Activity

Monitors access to sensitive files such as /etc/shadow.

Key Findings
10.0.0.5: Identified as a brute-force attacker
192.168.1.10: Successfully logged in after multiple failures and accessed sensitive files (potential compromise)
Dashboard

The Splunk dashboard includes:

Failed login analysis
Brute force detection
Account compromise detection

Skills Demonstrated
Security log analysis
Threat detection
SIEM usage (Splunk)
Incident investigation
Screenshots
![IMG_1608](https://github.com/user-attachments/assets/744b708d-9755-42fb-9c42-3539df39c55a)
![IMG_1610](https://github.com/user-attachments/assets/a718e6c7-4a31-4cf5-ba1c-44b9c22ff513)
![IMG_1611](https://github.com/user-attachments/assets/8609bd71-0e8d-4393-ba2b-d260dbf6d5a8)
![IMG_1615](https://github.com/user-attachments/assets/015ab029-6184-45dc-9025-82c7ec44811f)
![IMG_1612](https://github.com/user-attachments/assets/83ad6a66-fbef-47ec-885f-c7418190a879)
![IMG_1614](https://github.com/user-attachments/assets/a57d781f-70ae-4f92-9e99-4c92be51c9e4)
![IMG_1609](https://github.com/user-attachments/assets/9cd3bc7a-81d5-4bae-8c07-90e8487b5fb9)

![IMG_1618](https://github.com/user-attachments/assets/a3b1fee6-b51f-4807-8224-422d7aef7328)

📌 Conclusion

This project simulates a real SOC workflow by analyzing logs, detecting threats, and visualizing security events using Splunk.
