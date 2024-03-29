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

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img src="https://imgur.com/vaSRdll.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://imgur.com/3SjzqLn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://imgur.com/vYRT1BI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Created a new ticket as an external end user (Karen Johnson) in osTicket Support Center. Karen is manager of online banking platform and she wanted to create a ticket to notify IT department that mobile banking is down. The help topic is "Business Critical Outage" because customers are reporting that they cannot access mobile banking. Karen also created another ticket as "General Inquiry" to find out some info about hardware refresh as her department is having issues with their currents tablet and she requested it to be answered ASAP. 
</p>
<br />
<p>
<img src="https://imgur.com/Yrc9T8S.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Ken from Accounting Department created a new ticket as "Personal Computer Issues" as entire Accounting Department Adobe Reader is not working and nobody has been able to use it since the upgrade last night.  
</p>
<br />
<p>
<img src="https://imgur.com/TGSGAtG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://imgur.com/8Xs5StQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://imgur.com/A56Tkui.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Jane Green as a queue manager is going to go through open tickets and assign them to other help desk professionals if needed. Open ticket by Karen "Entire mobile banking is down" sounds like business impacting incident and it could potentially lose money for the business so Jane set up this ticket as an "Emergency" priority level. Jane set SLA Plan as SEV-A as this ticket is critical incident and it has to be resolved in a matter of one hour. She also assigned this ticket to "System Administrators" department as they are responsible for mobile banking infrastructure. Jerry from Sys Engineering found and corrected a failed load balancer, and ticket got resolved.
</p>
<br />
<p>
<img src="https://imgur.com/bO8HKXP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next ticket "Entire Accounting Dept Adobe Reader is not working" was assigned to John Smith with "High" priority level and re-assigned to SEV-B SLA Plan.
</p>
<br />
<p>
<img src="https://imgur.com/7Ws7dJc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
A "When are we getting hardware refresh" ticket was set to a "Low" priority level with SEV-C SLA Plan and resolved by a queue manager - Jane Green as hardware was slated for Q1 and Karen's department was already able to start testing new units. 
</p>
<br />
<p>
<img src="https://imgur.com/3v0FsFE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
John Smith logged in into his osTicket account to resolve a "Entire Account Dept Adobe Reader is not working" ticket assigned to him. John rolled back version of Adobe Reader to previous version and in the meantime, he will research why the new version doesn't work on the Accounting Department hardware. After doing some research. John figured out the problem, re-upgraded eveyone to a newer version of Adobe Reader and closed the ticket.
</p>
<br />
