# All Ports Are Open...  The HoneyNet is set!
![image](https://github.com/user-attachments/assets/4cbcb3ec-5ecc-4575-b0c4-06c6eae318f9)

## In the second phase of the project,  I accessed both Network Security Groups and created a new rule (⚠️Danger_AllowAnyCustomInboundTraffic) opening both VMs to all Inbound Internet Traffic.  

![image](https://github.com/user-attachments/assets/6f01a5f8-2f33-4b45-a166-f5ff9cada94e)

![image](https://github.com/user-attachments/assets/8dc1882a-d6a2-4513-a349-3823c9440a3f)

## After allowing plenty of time for the activity logs to record any malicious traffic, I accessed Azur's Log Analytics Workspace and reviewed the Logs of both VMs.
![image](https://github.com/user-attachments/assets/9d7a4e75-e746-425c-955b-bb2183b0aed6)

## Unsurprisingly, I found hundreds of failed login attempts (mostly Brute Force attempts). I also used RDP to access the Linux VM (auth.log) and using the (grep) command narrowed the search down to show only failed "Password" attempts.

![image](https://github.com/user-attachments/assets/c95d0e8b-9a3c-4ba7-9527-80bcd3a56861)

---
![image](https://github.com/user-attachments/assets/8e64c33f-5cb6-489d-8e2c-2b4fa6167e0e)

## Using MS Sentinel Analytics, I was able to establish security alerts to notify me of Brute Force attempts, Firewall Tampering, Malware, and other types of malicious incidents. I was also able to create maps using ip geolocation data to map out bad actors across the globe attempting to breach my network. 
---
## Attack Maps Before Hardening / Security Controls
![image](https://github.com/user-attachments/assets/ff9363cc-d4ae-425a-97f7-4cd9aa861cc1)
![image](https://github.com/user-attachments/assets/734bc45f-ee56-432d-9533-d661afd17e30)
![image](https://github.com/user-attachments/assets/09ff8c60-71da-44de-b119-c7af63b60313)
---
## Metrics Before Hardening / Security Controls

![image](https://github.com/user-attachments/assets/9cd4666c-0f88-484c-9167-186613a2a9ae)

## In the next phase of the project, I will implement NIST 800-61 Incident Handling Guide and work through several incidents created by MS Sentinel.

----
----

