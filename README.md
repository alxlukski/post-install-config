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

Part 3 (Post Installation Setup)
Configure Roles
Admin Panel -> Agents -> Roles
Supreme Admin
Configure Departments
Admin Panel -> Agents -> Departments
System Administrators
Configure Teams
Admin Panel -> Agents -> Teams
Level I Support
Level II Support
Allow anyone to create tickets
Admin Panel -> Settings -> User Settings
Registration Required: Require registration and login to create tickets 
Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane
John
Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken
Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours)
Configure Help Topics
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset


<h2>Configuration Steps</h2>

<p>
![image](https://github.com/alxlukski/post-install-config/assets/150772204/59469f9f-fa86-4fa6-a339-d15eb5b71a91)
</p>
<p>
In this screenshot, we create departments inside of osTicket. These departments are for giving a group of accounts a dedicated location with specified rules and access inside of the system.
</p>
<br />

<p>
![image](https://github.com/alxlukski/post-install-config/assets/150772204/cda49e8f-1d07-4fb8-bc17-16430f4d23cb)
</p>
<p>
In this screenshot, we set up agent accounts inside of osTicket, so that they can access the system, and user tickets.
</p>
<br />

<p>
![image](https://github.com/alxlukski/post-install-config/assets/150772204/4830a58c-4cc3-484b-a863-f5eb1b698439)
</p>
<p>
In this screenshot, we create user accounts inside of osTicket, so that tickets can be opened for agents to access.
</p>
<br />
