<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Teams and Departments
- Configure Agents
- Configure SLA
- Create Help Topics

<h2>Configuration Steps</h2>

**Important Notice:**

Please ensure you're logging in on the correct page:
<p></p><strong>
Admin/Analyst Login:</strong> <a href="http://localhost/osTicket/scp/login.php">Admin/Analyst Login Page</a>
<p>
<strong>End User Login:</strong> <a href="http://localhost/osTicket">End User osTicket Portal</a>
</p>

**Acknowledge Agent Panel vs Admin Panel**

To manage user roles and permissions, please follow the configuration steps below:

- **Configure Roles**: Group permissions for agents by setting up specific roles. Learn more about configuring roles [here](https://docs.osticket.com/en/latest/Admin/Agents/Roles.html).
  
- **Admin Panel**:
  - Go to **Agents** → **Roles** to set up and manage roles.
  - **Supreme Admin**: This role grants full administrative privileges.

<p>
<img src="https://i.imgur.com/ihYnKsn.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/Iw5PB1f.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/8S6evVC.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/XcKyHGH.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>

**Configure Departments for Ticket Visibility**

To manage ticket visibility and assign agents to specific departments (e.g., Help Desk, SysAdmins, Networking), follow the steps below:

Configure Departments: Control which agents have access to specific tickets by configuring departments.
- Admin Panel:
  - Navigate to Agents → Departments to configure and assign agents to the appropriate departments.
  - SysAdmins: This department will have access to system administration-related tickets.

<img src="https://i.imgur.com/MnUqHPN.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>

**Configure Teams for Cross-Department Collaboration**

To set up teams that pull agents from different departments and facilitate collaboration, follow these steps:
- Configure Teams: Create teams that combine agents from various departments to work on specific issues. 
- Admin Panel:
  - Go to Agents → Teams to create and configure teams.
  - Online Banking: This team can include agents from various departments to handle online banking-related tickets.
 
<img src="https://i.imgur.com/knnDKeO.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
