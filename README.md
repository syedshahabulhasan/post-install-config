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

- **Configure Roles**: Group permissions for agents by setting up specific roles.
  
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

**Allow Anyone to Create Tickets**

To control who can create tickets, you can enable or disable the requirement for user registration:

- Allow Anyone to Create Tickets: If you want to allow unregistered users to submit tickets, ensure the setting is configured as follows:
  - Admin Panel → Settings → User Settings
  - **UNCHECK**: Unregistered users can create tickets to allow anyone to submit a ticket without registration.

<img src="https://i.imgur.com/uBBQ7AC.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>

**Configure Agents**

To add new agents and assign them to specific departments, follow the steps below:

- Configure Agents: Add agents (workers) and assign them to appropriate departments based on their role.
- Admin Panel:
  - Go to Agents → Add New to create new agents.
  - Example:
    - Jane: Assigned to SysAdmins department.
    - John: Assigned to Support department.

<img src="https://i.imgur.com/H7nQwzx.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/g5zpIIh.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/NRbSLl1.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Q3Ug4fR.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>

**Configure Users (Customers)**

To add new users (customers) and manage their details, follow the steps below:
- Configure Users: Add users to the system to allow them to submit tickets and track progress.
- Agent Panel:
  - Switch to the Agent Panel.
  - Go to Users → Add New to add new users.
  - Example:
    - Karen
<img src="https://i.imgur.com/kh4sdKr.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>

