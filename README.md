# post-install-config
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

- Windows 11 pro</b> 



<h2>Configuration Steps</h2>

<p>
  Configure Roles for grouping permissions
<img src="https://github.com/sparkman787/post-install-config/blob/main/step2.PNG"/>
</p>
<p>
This is where we can add more roles inside a company/department with certain grouping permissions, from as little to view only to all access.
  Next we can configure deparments inside to help with ticket visibility (Help Desk vs SysAdmins, vs Networking)
  <img src="https://github.com/sparkman787/post-install-config/blob/main/step3.PNG"/>
  We can also configure Teams which would be essentially creating a group amongst different departments (or pulling a group from different departments into one team)
</p>
<br />

<p>Next we want to configure it so anyone can create a ticket ( you can configure it to require registration inside the system)
<img src="https://github.com/sparkman787/post-install-config/blob/main/step4.PNG"/>
</p>
<p>
Inside the Agents Tab we can create new agents (since we currently have no "real agents" in order to test out OS ticket creation and delegation/completion).
  Then we can also add in Users to create fake tickets to assign to our fake agents in order to test out ticket eval and distribution.
    <p>Agents</p>
  <img src="https://github.com/sparkman787/post-install-config/blob/main/step5.PNG"/>
 <p>Users</p>
  <img src="https://github.com/sparkman787/post-install-config/blob/main/step6.PNG"/>

</p>
<br />

<p>Next we will configure SLA (most will already be set up with inhouse rules for tickets) here is an example of a Sev-A most important
<img src="https://github.com/sparkman787/post-install-config/blob/main/step7.PNG"/>
</p>
<p>
The last thing we need to set up is Help Topics, (when users create a ticket) to help categorize. It should be under Admin panel => Manage => Help Topics. By doing this it makes it easier for users to define issues outside of SLA defining.
  <img src="https://github.com/sparkman787/post-install-config/blob/main/step8.PNG"/>
</p>
<br />
