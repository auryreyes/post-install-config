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
- Configure Departments
- Configure Teams
- Allow anyone to create tickets
- Configure Agents (Workers)
- Configure Users (Customers)
- Configure Service Level Agreement (SLAs)
- Configure Help Topics

<h2>Configuration Steps</h2>

<h3>Step 1. Configure Roles</h3>

Agents are assigned roles based on the Departments to which they have access. We’ll create a role called “Supreme Admin” and add an agent to have access to all permissions.

**Add Role**
- Admin Panel -> Agents -> Roles
- Supreme Admin

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>Step 2. Configure Departments</h3>

The help desk's Departments are used to route tickets, thus each Department has a variety of settings that can be set.

**Add Departments**
- Admin Panel -> Agents -> Departments
- System Administrators

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>Step 3. Configure Teams</h3>

You can group Agents from several Departments using teams to solve a certain problem.

**Add Teams**
- Admin Panel -> Agents -> Teams
  - Level I Support
  - Level II Support

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>Step 4. Allow anyone to create tickets</h3>

- Admin Panel -> Settings -> User Settings
- Registration Required: Uncheck “Require registration and login to create tickets”

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>Step 5. Configure Agents(Workers)</h3>

Agents are granted access to the help desk in order to respond to and resolve tickets.
Create two Agents, Jane Doe with administrator access and John Doe as a support.

**Add Agents**
- Admin Panel -> Agents -> Add New
  - Jane Doe
  - John Doe

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>Step 6. Configure Users (Customers)</h3>

Users can now register for an account and log in to generate tickets or check the status of existing tickets. Either the Agent Panel or the Admin Panel can be used to add users. In this case, two users were established via the Agent Panel.

**Add Users**
- Agent Panel -> Users -> Add New
  - Karen
  - Ken

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>Step 7. Configure Service Level Agreement (SLAs)</h3>

The SLA Plan's goal is to specify how long the help desk administrator anticipates it will take to resolve tickets.

**Add Service Level Agreement (SLAs)**
- Admin Panel -> Manage -> SLA
  - Sev-A (1 hour, 24/7)
  - Sev-B (4 hours, 24/7)
  - Sev-C (8 hours, business hours Mon - Fri 8am-5pm with U.S. Holidays)

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>Step 8. Configure Help Topics</h3>

Help Topics will simplify the help desk experience for your end users and ensure correct ticket assignment and timely resolution.

**Add Help Topics**
- Admin Panel -> Manage -> Help Topics
  - Business Critical Outage
  - Personal Computer Issues
  - Equipment Request
  - Password Reset
  
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

  osTicket is now set up. The following lesson will demonstrate how to submit and respond to tickets.This will help you gain confidence and skill. The ticketing system is vital in the Help Desk profession.
