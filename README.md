<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This project outlines the post-install configuration of the open-source help desk ticketing system <b>osTicket</b>, focusing on permissions, staff organization, and creating ticket workflows.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- osTicket Admin & Agent Panels

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Differentiate the Admin & Agent Panels
- Configure Roles & Permissions
- Organize staff into Departments & Teams
- Allow or restrict ticket creation for end users
- Add Agents (IT staff) & Users (customers)
- Define SLA policies for response and resolution times
- Create Help Topics for ticket categorization

<h2>Configuration Steps</h2>

<p>

</p>
<p>Admin Panel: Access to system configuration.</p> 
<p>Agent Panel: Access to ticket handling.</p>

<h4>Roles</h4>
  <p>Permissions grouped and assigned to agents, granting access based on position or responsibility.</p>  
  
 <p><i>Why?:</i> Roles define what an agent can or cannot do. This ensures proper security boundaries; e.g., junior staff can't delete tickets, admins can manage configurations.</p>
<br />

<p>

</p>
<h4>Departments</h4>
<p>Organizes tickets and controls visibility, ensuring issues are routed to correct group.</p>  
  
 <p><i>Why?:</i> Departments align ticket management with organizational structure, reducing confusion and misrouting.</p>
 
<h4>Teams</h4>
<p>Pulls agents from multiple departments to collaborate on specific functions.</p>  
  
 <p><i>Why?:</i> Provides flexibility across projects that require expertise from multiple groups, allowing resource pools without breaking department boundaries.</p>
<br />

<p>

</p>

<h4>Agents</h4>
<p>Staff members who resolve tickets, assigned roles and departments, e.g., Jane in SysAdmins or John in Support.</p>  
  
 <p><i>Why?:</i> Agents are the core of IT Support. Defining scope ensures accountability and clear division of responsibilities.</p> 

 
<h4>Users</h4>
<p>End customers or employees who submit tickets.</p>   
  
 <p><i>Why?:</i> Distinguishing users from agents ensures clear separation between service providers and consumers. This allows for issue tracking and effective communication.</p>  
 <br />
 
<p>

</p>

<h4>SLA Policies</h4>
<p>Defines response and resolution timeframes for different priorities.</p>
    <ul>
    <li>Sev-A Critical (1 hour, 24/7)</li>  
    <li>Sev-B High (4 hours, 24/7)</li>  
    <li>Sev-C Normal (8 hours, business hours)</li>  
    </ul>
<p><i>Why?:</i> SLAs set expectations for service delivery and provide the metrics for customer satisfaction and IT performance.</p>

 <h4>Help Topics</h4>
<p>Ticket categories: Password Reset, Equipment Request, Business Critical Outage, which guide users when submitting a ticket.</p>   
  
 <p><i>Why?:</i> Help topics streamline intake, helping users describe issues clearly and IT staff to prioritize tickets efficiently.</p>
 <br />
