<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


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
  <li>End users created tickets for various issues.</li>
  <li>Mobile/online banking system is down.</li>
  <li>Accounting department needs Adobe upgrade.</li>
  <li>CFO's laptop will not power on.</li>
</ul>

<p><i>Why?:</i> Proper ticket intake ensures issues are documented in a structured system, preventing problems from being lost in informal requests.</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h4>Assignment & Communication</h4>
<ul>
  <li>Tickets were reviewed by Help Desk Agent (John), who observed properties</li>
  <li>Priority</li>
  <li>Department</li>
  <li>SLA</li>
  <li>Assigned To</li>
</ul>

Properties were then set according to severity and business impact:
   <ul>
    <li>Sev-A (1 hour, 24/7) -> Online Banking Department</li>
     <li>Critical outage directly impacted customers and revenue, requiring immediate escalation</li>
    <li>Sev-B (4 hours, 24/7) -> Support Department</li>
      <li>Adobe upgrade was urgent but not business critical</li> 
      <li>CFO laptop failure was significant but not directly impacting revenue.</li>
</ul>

<p><i>Why?:</i> Assignment ensures the right team receives the ticket, while SLAs define timeline of completion based on severity and impact.</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h4>Working the Issue</h4>

<ul>
<li>Specified agents progressed tickets toward resolution:</li>
  <li>John handled the Adobe upgrade and CFO laptop tickets.</li>
  <li>Jane resolved the online banking outage, as it required SysAdmin level access. </li>
<li>Escalation rules were tested: John could no longer access certain SysAdmin tickets after they got reassigned, demonstrating access control in real time.
</li>
</ul>
  <p><i>Why?:</i> This reflects the core of help desk troubleshooting, escalation when necessary, and continuous communication with users. Additionally, implementing access boundaries protects sensitive departments while ensuring work is distributed correctly.</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Resolution"/>
</p>

<h4>Resolution</h4>
<ul>

<li>All tickets were closed after resolution, and SLA timelines were met.</li>
  <li>osTicket's built in email notifications ensured users received updates at every stage, maintaining a communication loop</li>
  <li>Reinforced best practices: log every interaction (calls, chat requests, in person requests) into the system to keep records accurate and team informed.</li>
</ul>
   <p><i>Why?:</i> Ticket resolution is not just about fixing issues, it's about documenting work, maintaining contact with customers/users, and creating data that leadership can use to measure IT effectiveness.</p>
   <br />

   <h2>Key Takeaways</h2>
    <ul>
      <li>Every issue should be processed as a ticket despite method of communication. </li>
      <li>SLAs and department structures enforce accountability and service quality.</li>
      <li>Practicing the lifecycle multiple times builds technical intuition and reinforces the technical skills for IT support.</li>
    </ul>
