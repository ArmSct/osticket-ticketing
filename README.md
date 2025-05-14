![68747470733a2f2f692e696d6775722e636f6d2f7278463149686a2e706e67](https://github.com/user-attachments/assets/7fa9f6dd-dbb0-45db-b07b-2031041045fb)

# osTicket Incident Handling
In this lab, I simulate the lifecycle of support tickets within the osTicket system by creating, managing, and resolving tickets as both end users and help desk agents. The objective is to practice efficient ticket handling, ensure proper classification, and understand escalation paths while maintaining clear communication with the user.

## Technology Utilized
- osTicket v1.15.8
- Windows 10 Virtual Machine (Azure)
- RDP for VM access
- IIS, PHP, MySQL for backend support

## Ticket 1: Online Banking System Outage
From the end-user osTicket URL (http://localhost/osTicket) submit a ticket as karen (end-user) describing the issue. 
![mstsc_7eYbwQNmsG](https://github.com/user-attachments/assets/73985d6b-fd04-42a3-b896-932cf17423af)

As a Help Desk Agent (John) change the SLA to "SEV-A" and update the Help Topic to "Report a Problem / Business Critical Outage". 
![mstsc_A9I2cHhpzZ](https://github.com/user-attachments/assets/4044a568-1322-4334-95a9-1e9c95704455)

Escalate the problem to a more capable department, in this case, the "Online Banking" department.
![mstsc_WodhEYXeqn](https://github.com/user-attachments/assets/e60fd970-b175-4a89-9257-ef60a9a93f7b)

As an Online Bamking Agent (Jane), investigate the issue and resolve the problem. The close the ticket.
![mstsc_vkNqKFOubz](https://github.com/user-attachments/assets/06d5e39e-6004-44e2-8b0a-ee4e073289ec)

![mstsc_lph5IbpN8G](https://github.com/user-attachments/assets/2472a598-b4d9-48df-a4ec-fa806bc11ce6)

## Ticket 2: Adobe Upgrade Failure
From the end-user osTicket URL (http://localhost/osTicket) submit a ticket as ken (end-user) describing the issue. 
![mstsc_TYjvDjnzAO](https://github.com/user-attachments/assets/80c21402-466c-41d1-a4c7-64d2420cdd65)

As a Help Desk Agent (John) change the SLA to "SEV-C". Investigate the issue and update the customer on the situation.
![mstsc_mLKhhz423h](https://github.com/user-attachments/assets/420bc80f-97cd-4fe5-9374-4fa7e2ec5916)

Once the problem is resolved, close the ticket and leave a note regarding the closed ticket.
![mstsc_foWw3m6tZ7](https://github.com/user-attachments/assets/1c6eb0b5-6c1a-47af-9e65-16d4e6bf8424)

## Ticket 3: CFO Laptop Fails to Power On
