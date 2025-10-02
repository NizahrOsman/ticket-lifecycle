<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket Admin & Agent Panels

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment & Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<h4>Intake</h4>
<ul>
  <li>End users created tickets for various issues</li>
  <li>Mobile/online banking system is down</li>
  <li>Accounting department needs adobe upgrade</li>
  <li>CFO's laptop will not power on</li>
</ul>

<p><i>Why?:</i>Intake and porper ticket creation captures issues in a structured system, ensuring every problem is documented instead of being lost in informal requests. </p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<h4>Assignment & Communication</h4>
<ul>
<li>Tickets were reviewed by Help Desk Agent (John), who ovsereved properties:</li>
  <li>Priority</li>
  <li>Department</li>
  <li>SLA</li>
  <li>Assigned To</li>

<li>Properties were then set according to severity and business impact:</li>
  <li>Sev-A (1 hour, 24/7) -> Online Banking Department</li>
    <li>Critical outage directly impacts customers and revenue, requiring immediate escalation</li>
  <li>Sev-B (4 hours, 24/7) -> Support Department</li>
    <li>Adobe upgrade was urgent but not business critical</li>
    <li>CFO laptop failure was Sev-C not entire impacting revenue,</li>
</ul>

<p><i>Why?:</i>Assigment ensures the right team recieves the ticket, and SLAs define timeline of completion based on severity of impact.</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<h4>Working The Issue</h4>
<ul>
<li>Specified agent progresses tickets towards resolution:</li>
  <li>John handled the Adobe upgrade and CFO laptop tickets</li>
  <li>Jane resolved the online banking outage, as it requred SysAdmin level </li>
<li>Escalation rules were tested: John could no longer access certain SysAdmin tickets after they got reassigned, demonstrating access control</li>
  <li>Assigned To</li><br />
