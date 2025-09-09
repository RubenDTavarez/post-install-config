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

- Configuration of Roles for grouping permission     
- Configuration of departments 
- Configuration of teams 
- Creation of ticket permissions
- Configuration of Agents
- Configuration of Users
- Configuration of the SLA
- Configure Help Topics 

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/BQMhFuG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
    Once we get our "congratulation" page  after the installation there will be  multiple URSLs for the osTicket. Here we find the URL links  for the administrators/Agents to log in and perform their task and other link for the end users to summit their monitor their tickets. There are differences between the admins and agents panels as usual. You can take a look at the picture above. Admins can create agents, set permissions etc. 
</p>
<br />

<p>
<img src="https://i.imgur.com/JBBfBKN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
    Roles: These are permissions granted to the Agents per department that they access to. Each role a set of permissions that can be changed by agents given that Role in association with a department they have access to. From the Admin panel > Agents > Roles. In the picture above the text we can see some roles and the type of access they have. You can create an unlimited amount of roles and group a set of permissions for the type access your team needs based on their roles. 
</p>
<br />

<p>
<img src="https://i.imgur.com/ubu9Bp2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
    Departments: To access departments panel,  click on the Admin Panel, then click on Agents and  Departments. You can have departments, Parent Departments and Child Departments. These can be the Support, Accounting or Admins department. We have a child department when it is under another a department. The agents of the Parent Department will see the tickets of the child department. This will not be the same for the agents from the child department. 

</p>
<br />


<p>
<img src="https://i.imgur.com/fiCV4JV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
    Teams:  Teams are a great way to put together agents from different departments to handle a specific topic or issue. We can also implement a new set of rules and permissions for a specific team and grant access to agents who otherwise would not be able to access it. To create an a Team in your admin panel, locate the agents tab, and click on Teams. Then click add new team, and fill out the information requested.    
</p>
<br />


<p>
<img src="https://i.imgur.com/gArSaBG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
    Tickets request by endusers: We will allow  all users  —  even those not registered —  to create tickets. From our admin panel, click on settings and click users next. We need to make the “registration required” box is unchecked.    
</p>
<br />


<p>
<img src="https://i.imgur.com/X4nOanJ.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
   Configuring Agents: Agents will take care of     
</p>
<br />


<p>
<img src="https://i.imgur.com/2LI3TjT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
    Tickets.    
</p>
<br />


<p>
<img src="https://i.imgur.com/2LI3TjT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
    Tickets.    
</p>
<br />


<p>
<img src="https://i.imgur.com/2LI3TjT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
    Tickets.    
</p>
<br />
