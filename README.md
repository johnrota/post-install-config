<img src="https://static.wixstatic.com/shapes/2ebf04_6ddec2f2c2eb4cd4ada9cef3f6ace924.svg" alt="osTicket Logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial provides a comprehensive guide to the post-installation configuration procedures of the open-source help desk ticketing system, osTicket. Users can learn how to optimize their osTicket installation by configuring its various admin/agent settings, including roles, departments, ticket templates, and more.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Establish a senior administrator position with appropriate role-based access control privileges and permissions.
- Implement a new department for system administrators.
- Configure one team responsible for level II support issues.
- Create three agents with distinct roles and permissions based on their job requirements.
- Add two users who will serve as example customers by sending in support tickets.
- Configure service-level agreements (SLAs) by establishing performance metrics and customer service targets.
- Set up four help topics that enable customers to easily narrow down their support issues.

<h2>Configuration Steps</h2>
<p align="left"> Part 1: <a href="https://github.com/johnrota/osticket-prereqs">osTicket: Prerequisites and Installation</a></p>
<br />

<p align="center"> 
<img src="https://imgur.com/GH4Bqmy.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 1: Navigate to the admin panel, then click on Agents, followed by Roles, and select the option to add new roles.
</p>
<br />

<p>
<p align="center"> 
<img src="https://imgur.com/QCrkz6i.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 2: Name the new role as "Senior Administrator."
</p>
<br />

<p>
<p align="center"> 
<img src="https://imgur.com/5ZnbJnD.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 3: Choose all the permissions for the Senior Administrator role in the Tickets, Tasks, and Knowledgebase tabs, and click "Add Role."
</p>
<br />

<p>
<p align="center"> 
<img src="https://imgur.com/iYZ4i4X.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://imgur.com/KeenZHc.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 4: Navigate to Departments and select the option to add a new department.
</p>
<br />

<p>
<p align="center"> 
<img src="https://imgur.com/YdrJanP.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
Step 5: Name the department as "System Administrators" and click on "Create Dept."
</p>
<br />

<p>
<p align="center"> 
<img src="https://imgur.com/gvswbDP.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://imgur.com/lHQMr9d.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 6: Go to Teams and select the option to add a new team.
</p>
<br />

<p>
<p align="center"> 
<img src="https://imgur.com/RJUOHNh.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
<p align="center"> 
<img src="https://github-production-user-asset-6210df.s3.amazonaws.com/138822912/258663851-98db7e7c-b501-4345-899c-5e261bb24755.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
</p>
<p>
Step 7: Name the team "Level II Support," add yourself as a team member, and click on "Create Team."
</p>
<br />

<p>
<p align="center"> 
<img src="https://imgur.com/A5qMjyR.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
Step 8: Go to Agents and select the option to add new agents.
</p>
<br />

<p>
<p align="center"> 
<img src="https://imgur.com/lLFsYkv.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 9: Fill out the text input fields under "Account" to add three new agents.
</p>
<br />


<p>
<p align="center"> 
<img src="https://imgur.com/Utpe5YS.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 10: For Agent 1, under the "Access" tab, assign them to the System Administrators department with a Senior Administrator role. For extended access, add them to Support.
</p>
<br />

<p>
<p align="center"> 
<img src="https://imgur.com/ioaztbK.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 11: Keep all permissions under the "Permissions" tab the same, and for teams, add Agent 1 to the Level II Support team.
</p>
<br />

<p>
<p align="center"> 
<img src="https://imgur.com/QvsGfim.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://imgur.com/49bQeEC.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 12: Add Agent 2 to the Support department with an "Expanded Access" role and no extended access.
</p>
<br />

<p>
<p align="center"> 
<img src="https://imgur.com/8F6noyx.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 13: Keep all permissions the same and add Agent 2 to the Level I Support team, then click on "Create."
</p>
<br />

<p>
<p align="center"> 
<img src="https://imgur.com/KUhNQIE.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://imgur.com/Rmfzwnd.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 14:  Create Agent 3 and choose "Maintenance" as their department, "Senior Administrator" for their role, and no extended access.
</p>
<br />

<p>
<p align="center"> 
<img src="https://imgur.com/ioaztbK.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 15: Add Agent 3 to the Level II Support team and click on "Create."
</p>
<br />

<p>
<p align="center"> 
<img src="https://imgur.com/VGX8NSU.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 16: Go to the Agent panel, then click on "Users," and add the users who will be creating support tickets.
</p>
<br />

<p>
<p align="center"> 
<img src="https://imgur.com/wKoCw0N.png" height="50%" width="50%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://imgur.com/tXs3nXp.png" height="50%" width="50%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 17: Fill out the text input fields and click "Add user" to create two users.
</p>
<br />

<p align="center"> </p>
<p>
Step 18: Return to the admin panel to create SLAs (service-level agreements).
</p>
<br />

<p>
<p align="center"> 
<img src="https://imgur.com/x2Kg0Ar.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 19: Navigate to "Manage" and then "SLA," and create three distinct SLA plans by clicking "Add new SLA Plan."
</p>
<br />

<p align="center"> 
<img src="https://imgur.com/qstAQF9.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 20: Create SLA 1 and name it SEV-A. Set the grace period to one hour on a 24/7 schedule, and then click "Add Plan."
</p>
<br />

<p align="center"> 
<img src="https://imgur.com/gGOvpjS.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 21: Create SLA 2 and name it SEV-B. Set the grace period to four hours on a 24/7 schedule.
</p>
<br />

<p align="center"> 
<img src="https://imgur.com/Q1Csvoh.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 22: Create the last SLA, which is less severe, and name it SEV-C. Set the grace period to eight hours, Monday through Friday from 8 AM to 5 PM.
</p>
<br />

<p align="center"> 
<img src="https://imgur.com/pi7cqgN.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 23: Proceed to create various help topics by clicking on the "Help Topics" tab.
</p>
<br />

<p>
<p align="center"> 
<img src="https://imgur.com/undefined" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
Step 24: Click on "Add new help topic," name it "Personal Computer Issues," and then click "Add topic."
</p>
<br />

<p>
<p align="center"> 
<img src="https://imgur.com/CPovG20.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://imgur.com/cIB5l5b.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://imgur.com/JeDTttS.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 25: Add three more help topics with the following names:
<ul>
  <li>Password Reset</li>
  <li>Equipment Request</li>
  <li>Business Critical Outage</li>
 </ul> 
</p>
<br />
