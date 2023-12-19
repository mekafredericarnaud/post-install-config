<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Admin Panel
- Configure Agent Panel

<h2>Configuration Steps</h2>

Browse to your help desk login page: http://localhost/osTicket/scp/login.php.
<p>
<img src="https://i.imgur.com/QFnwCHP.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once we enter the login, we access to the help desk osTicket page.
</p>
<img src="https://i.imgur.com/cK10TNq.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
We will first configure the Admin Panel: right now it is on Agent Panel and we need to switch by clicking on to Admin Panel.  
</p>
<img src="https://i.imgur.com/Gu6luTC.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
1.) Configure Roles.
</p>
a. Admin Panel -> Agents -> Roles and click on Add New Role.
</p>
<img src="https://i.imgur.com/y7jioJi.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
b. Create a new role Supreme Admin and set the Permissions.
</p>
<img src="https://i.imgur.com/jBk15WE.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/xdHiX5e.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/6DXNZDA.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/5Q4zf9p.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
The new role has been succesfully added.
</p>
<img src="https://i.imgur.com/AuWQuDI.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
2.) Configure Departments.
a. Admin Panel -> Agents -> Departments and click on Add New Department.
</p>
<img src="https://i.imgur.com/sPQ90NK.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
b. Create a department System Administrators.
</p>
<img src="https://i.imgur.com/bbLiWTU.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/XB1J2cc.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
The new Department has been successfully added.
</p>
<img src="https://i.imgur.com/VLJtzbM.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
4.) Configure Teams.
</p>
a. Admin Panel -> Agents -> Teams and click on Add a New Team Level II Support.
</p>
<img src="https://i.imgur.com/LwlrY9N.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/9aOmUIM.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/pacUKXp.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
The new Level II Support Team has been successfully added.
</p>
<img src="https://i.imgur.com/" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
5.) Allow anyone to create tickets.
</p>
a. Admin Panel -> Settings -> User Settings.
<p>
b. Registration Required: Require registration and login to create tickets.
</p>
<img src="https://i.imgur.com/qiRJABS.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
Successfully update User Settings and Options.
<img src="https://i.imgur.com/07EIBsk.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
6.) Configure Agents (workers).
</p>
a. Admin Panel -> Agents -> Add New Agent named Jane, Set Password, Status and Settings.
<img src="https://i.imgur.com/1oBiF0q.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
Access.
<img src="https://i.imgur.com/tWgjyqJ.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
Permissions.
<img src="https://i.imgur.com/pMzZDmR.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
Teams.
<img src="https://i.imgur.com/6lgxbqV.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
We successfully added Jane.
<img src="https://i.imgur.com/jazT5pU.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
b. Admin Panel -> Agents -> Add New Agent named John, Set Password, Status and Settings.
</p>
<img src="https://i.imgur.com/AVSgFvP.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
Access.
<img src="https://i.imgur.com/JHAro3S.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
We successfully added Jane.
<img src="https://i.imgur.com/I6FHkx8.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/4TNOLW4.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
7.) Configure SLA.
</p>
a. Admin Panel -> Manage -> SLA..
</p>
- Create Sev-A (1 hour, 24/7).
<img src="https://i.imgur.com/HaoZz3D.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
Plan successfully added.
<img src="https://i.imgur.com/lYBwyHH.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
- Create Sev-B (4 hours, 24/7).
<img src="https://i.imgur.com/zDFEybd.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
Plan successfully added.
<img src="https://i.imgur.com/tctmvCk.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
- Create Sev-C (8 hours, business hours).
<img src="https://i.imgur.com/YVrXaYQ.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
Plan successfully added.
<img src="https://i.imgur.com/R3qvxgo.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
8.) Configure Help Topics.
</p>
Admin Panel -> Manage -> Help Topics and Add Neww Help Topic.
<img src="https://i.imgur.com/B9UOVQy.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
- Business Critical Outage.
<img src="https://i.imgur.com/B4wgIlx.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/0sai93W.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
- Personal Computer Issues.
<img src="https://i.imgur.com/t8sUXJq.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/14mTEvS.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
- Equipment Request.
<img src="https://i.imgur.com/DYbSvoq.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
- Password Reset.
<img src="https://i.imgur.com/ASavUeB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/0RgA3bk.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
We successfully added New Help Topic.
<img src="https://i.imgur.com/kPJzRQp.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
9.) Now, we can switch back to Agent Panel and Configure Users (customers).
</p>
<img src="https://i.imgur.com/BGJq9k7.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
a. Agent Panel -> Users -> Add New User named Karen.
</p>
<img src="https://i.imgur.com/QXbZirg.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/I2YxPNp.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
b. Agent Panel -> Users -> Add New User named Ken.
</p>
<img src="https://i.imgur.com/QKCgvCg.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/ud7cPse.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
All User have been added successfully.
<img src="https://i.imgur.com/0jWlIux.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We can now touch on tickets Lifecycle on the following project.
