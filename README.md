<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> (22H2) at least 2vCPUs, 8GB RAM

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2> Handling Tickets</h2>

<p>
To begin simulating helpdesk ticket resolution, first remove the default "Maintenance" department: log in as admin, navigate to 
Agents > Departments, select "Maintenance," and click More > Delete.  Then, create a new ticket at http://localhost/osTicket for user "Karen" reporting an outage of the company's online banking system.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/80fad41a-dd1d-4bb7-8b78-1acef7339859"
" height="80%" width="80%" alt="user portal"/>
</p>
<p>

<img src="https://github.com/user-attachments/assets/d9fb35f4-2af3-4680-b70d-996a22ad8e28"
 height="80%" width="80%" alt="ticket 1 created"/>
</p>
<p>
Access the ticket as agent "John Doe" (http://localhost/osTicket/scp). Assign the ticket to the "Online Banking" team and set the SLA to "Sev-A" to prioritize its resolution.  Then, log in as "Jane Doe" and resolve and close the ticket.
</p>
<br />
<p>
<img src="https://github.com/user-attachments/assets/d7a89796-3d31-47e7-8fea-43dfbe34a0f6" height="80%" width="80%" alt="john accessing ticket"/>
<img src="https://github.com/user-attachments/assets/cc366648-57d0-4ae8-9e6e-a8153942b118"
height="80%" width="80%" alt="jane closing ticket"/>
</p>

<p>
Imagine a new ticket arrives stating that the Adobe software update is not working correctly in the accounting department. John Doe picks up the ticket and notices that the information provided is incomplete. It's unclear how many users are affected and what the root cause of the problem is.

    In such situations, it's best practice to gather more information from the user, perhaps through a phone call or email.  For this simulation, let's assume that after further investigation, John determines that only a few users are affected. Since the issue has a minor impact on the business, he sets the SLA to "Sev-C" and suggests restarting the affected computers as a first step. If this resolves the problem, he can then close the ticket.

</p>
<img src="https://github.com/user-attachments/assets/da3366f6-87ed-4851-88d4-c0113db6ced8" height="80%" width="80%" alt="closed 2nd ticket"/>
<br />

<p>
Imagine a critical scenario: the CFO's laptop won't turn on.  This could have a significant impact on business operations if the CFO cannot access important files. However, the severity of the issue depends on the underlying cause. A simple battery replacement is a quick fix, while a failed inverter might require more extensive repairs.

 To reflect the potential urgency, set the initial priority level to "Emergency."  This highlights the importance of the issue and ensures it receives immediate attention.  Once you gather more information about the cause of the malfunction, you can adjust the priority level accordingly.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/aea9608f-f0ab-4f6c-bad5-52785da2f296" height="80%" width"80%" alt="closed 3rd ticket"/>
</p>
<br />
<p>
After further investigation, the CFO's laptop issue is identified as a faulty charger.  Adjust the SLA to "Sev-B" and resolve the ticket once a replacement charger is provided and the laptop is confirmed to be working.
  
</p>

<p>
Effective ticket resolution requires thorough investigation, targeted questioning, and proper escalation procedures.
</p>
