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

Agents are assigned roles based on the Departments to which they have access.

**Add Role**
- Admin Panel -> Agents -> Roles -> Add New Role
- Supreme Admin

<p>
<img src="https://i.imgur.com/gpxx8hh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/gsYpF7W.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/R4HDxDq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/ic8yhcA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/6DrekNo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/qFXjfhD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>Step 2. Configure Departments</h3>

The help desk's Departments are used to route tickets, thus each Department has a variety of settings that can be set.

**Add Departments**
- Admin Panel -> Agents -> Departments -> Add New Department
- System Administrators

<p>
<img src="https://i.imgur.com/m6qryWE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/kp3c1Yr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>Step 3. Configure Teams</h3>

You can group Agents from several Departments using teams to solve a certain problem.

**Add Teams**
- Admin Panel -> Agents -> Teams -> Add New Team
  - Level I Support
  - Level II Support

<p>
<img src="https://i.imgur.com/EtD6beg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/1i3Xgwn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>Step 4. Allow anyone to create tickets</h3>

- Admin Panel -> Settings -> User Settings
- Registration Required: Uncheck “Require registration and login to create tickets”

<p>
<img src="https://i.imgur.com/kcW6wER.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>Step 5. Configure Agents(Workers)</h3>

Agents are granted access to the help desk in order to respond to and resolve tickets.
Create two Agents, Jane Doe with administrator access and John Doe as a support.

**Add Agents**
- Admin Panel -> Agents -> Add New Agent
  - Jane Doe
  - John Doe

<p>
<img src="https://i.imgur.com/Jc2MhjY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/pgMx5Ro.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/b2RRaRj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/av4w9vo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/UWdnBmS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/b2RRaRj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/ip16yjG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>Step 6. Configure Users (Customers)</h3>

Users can now register for an account and log in to generate tickets or check the status of existing tickets. Either the Agent Panel or the Admin Panel can be used to add users. In this case, two users were established via the Agent Panel.

**Add Users**
- Agent Panel -> Users -> Add User
  - Karen
  - Ken

<p>
<img src="https://i.imgur.com/jOnUAz9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/JDrU86X.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/awR7kcH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/wvfrF56.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>Step 7. Configure Service Level Agreement (SLAs)</h3>

The SLA Plan's goal is to specify how long the help desk administrator anticipates it will take to resolve tickets.

**Add Service Level Agreement (SLAs)**
- Admin Panel -> Manage -> SLA -> Add New SLA Plan
  - Sev-A (1 hour, 24/7)
  - Sev-B (4 hours, 24/7)
  - Sev-C (8 hours, business hours Mon - Fri 8am-5pm with U.S. Holidays)

<p>
<img src="https://i.imgur.com/gn1liIR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/0VstBXf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/n5a7J0T.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/vX4zx0M.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/KFGNt9G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>Step 8. Configure Help Topics</h3>

Help Topics will simplify the help desk experience for your end users and ensure correct ticket assignment and timely resolution.

**Add Help Topics**
- Admin Panel -> Manage -> Help Topics -> Add New Help Topic
  - Business Critical Outage
  - Personal Computer Issues
  - Equipment Request
  - Password Reset
  
<p>
<img src="https://i.imgur.com/2jTOhtx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/7DFqLmZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/qPXFtJl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/WrLpIku.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/4r39Vmo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

osTicket is now set up. The following tutorial will demonstrate how to submit and respond to tickets. This will help you gain confidence and skill. The ticketing system is vital in the Help Desk Profession.
