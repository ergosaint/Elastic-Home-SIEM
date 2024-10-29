Elastic Home SIEM Lab 10/29/2024

[Objective]

In this guide, I’ll walk you through everything I learned while setting up a home lab for Elastic Stack SIEM using the Elastic Web portal and a Kali Linux VM. You’ll see how I configured the Kali VM to generate security events, set up an agent to forward data to the SIEM, and used Elastic’s querying tools to analyze the logs.

### Skills Learned

- Set up and configured Elastic Stack SIEM in a home lab environment.
- Acquired hands-on experience in generating and analyzing security events using Nmap on Kali Linux.
- Developed a custom dashboard in Elastic SIEM to visualize security events
- Successfully created and tested alert rules for detecting specific security events, showing competency in proactive incident response and alert management.


### Tools Used

- Elastic Stack Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Kali Linux Virtual Machine
- Oracle VM manager for hosting Linux

## Steps
1. Create an Elastic account
2. Install Oracle Virtual Box - a way to manage virtual machines (VM)
3. Aquired a Kali Linux VM
4. Run Kali VM through Oracle
5. Connect Elastic (SIEM) to Kali VM for log collection (forwarding data to SIEM) *See Screenshot bellow*

![Screenshot 2024-10-29 042334](https://github.com/user-attachments/assets/0858dcb1-21db-46cd-a8c5-7db5b4944312) *Ref 1: Kali VM*

6. Creating a Dashboard to Visualize the Events

![Screenshot 2024-10-29 051202](https://github.com/user-attachments/assets/d5a7226b-31f0-4070-806c-67980c63001b) *Ref 2: Elastic Dashboard*

7. Setup alerts

![Screenshot 2024-10-29 052452](https://github.com/user-attachments/assets/735cf895-7ea0-4eb9-b73a-6290ad0f617b) *Ref 3: Elastic Alerts*
