# All Ports Are Open...  The HoneyNet is set!
![image](https://github.com/user-attachments/assets/4cbcb3ec-5ecc-4575-b0c4-06c6eae318f9)

## In the second phase of the project,  I accessed both Network Security Groups and created a new rule (Danger_AllowAnyCustomInboundTraffic) opening both VMs to all Inbound Internet Traffic.  

![image](https://github.com/user-attachments/assets/6f01a5f8-2f33-4b45-a166-f5ff9cada94e)

![image](https://github.com/user-attachments/assets/8dc1882a-d6a2-4513-a349-3823c9440a3f)

## After a week or so, allowing plenty of time for the activity logs to record any malicious traffic, I accessed Azur's Log Analytics Workspace and reviewed the Logs of both VMs.
![image](https://github.com/user-attachments/assets/9d7a4e75-e746-425c-955b-bb2183b0aed6)

## Unsurprisingly, I found hundreds of failed attempts (mostly Brute Force attempts). I also used RDP to access the Linux VM and using the (grep) command accessed (auth.log) files showing only failed "Password" attempts.

![image](https://github.com/user-attachments/assets/c95d0e8b-9a3c-4ba7-9527-80bcd3a56861)
