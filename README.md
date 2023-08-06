<p align="center">
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
<p align="left"> Part 1: <a href="https://github.com/stevennocent/osticket-prereqs">osTicket: Prerequisites and Installation</a></p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_cdeb8316fe214205914005a78e5b1a6f~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_bea4a992832f41afa97913c15c2ed09c~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_cb93fd31b5544918bc5b88306be96c96~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_99039745abc1412eb69aadd13f61a342~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 1: Navigate to the admin panel, then click on Agents, followed by Roles, and select the option to add new roles.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_474c1f05521c4362bd268cd7b2d87dd8~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 2: Name the new role as "Senior Administrator."
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_f5fca352460b42a7aa42109d4c6375a9~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 3: Choose all the permissions for the Senior Administrator role in the Tickets, Tasks, and Knowledgebase tabs, and click "Add Role."
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_bf155220ca17460b8ef8a2fa331dbc2a~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_d7f0862daeb2478fa5bd78e262e00a4e~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 4: Navigate to Departments and select the option to add a new department.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_ce6e890a5eaf440a9d281c7d280f6f98~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_899027773c2a4b0b88ef894593f4b582~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 5: Name the department as "System Administrators" and click on "Create Dept."
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_e2aaa231051b44e0965b0fd0686a2cc6~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_52a470c0bebb4a4680bbe1e3d81b2694~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 6: Go to Teams and select the option to add a new team.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_04ccb670e90845b6b78dabf67eb1e68f~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_27fabeaac1b84b2b8cd96108f1157011~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 7: Name the team "Level II Support," add yourself as a team member, and click on "Create Team."
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_b576dc3bd91b4b66820cd60d252cec9c~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_7072d5577f7543b8acd0726202d6d051~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 8: Go to Agents and select the option to add new agents.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_60562564faf741c193991fe22edc0d06~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 9: Fill out the text input fields under "Account" to add three new agents.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_fe23c182c7554a7bafc9b618fdd503e3~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 10: Click on "Set Password," then uncheck the option "Send the agent a password reset email."
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_5334c985c058497e9b9b83da16689691~mv2.png" height="50%" width="50%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 11: Enter a password and click on "Set."
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_4bf53e313ec44a43b2d8f501f9ae5b01~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 12: For Agent 1, under the "Access" tab, assign them to the System Administrators department with a Senior Administrator role. For extended access, add them to Support.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_f8c57363cdb24bf5a72f7becd018ad21~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 13: Keep all permissions under the "Permissions" tab the same, and for teams, add Agent 1 to the Level II Support team.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_4c84c4198f724d898737b69d436d6609~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_70de6927774c4bb9888b9b1c654e8d9e~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 14: Add Agent 2 to the Support department with an "Expanded Access" role and no extended access.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_dd38ba79bd564a4bb8f4cecb67463b3f~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 15: Keep all permissions the same and add Agent 2 to the Level I Support team, then click on "Create."
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_5b5c19cdb85e418a9fce6be892155a46~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_483bc29a100c48118db222b87db8e1fa~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 16:  Create Agent 3 and choose "Maintenance" as their department, "Senior Administrator" for their role, and no extended access.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_a0890ff0a09e4fe293ae39f52d8e00d3~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 17: Add Agent 3 to the Level II Support team and click on "Create."
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_09ea5aaa4fd144c7996262fbb0a404b0~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_9fb7a351078f4627a6288eb7782b2bb6~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_43c4003ac2c74c499da2c80d8fd901dd~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 18: Go to the Agent panel, then click on "Users," and add the users who will be creating support tickets.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_7bd64b0f4d4c4ce0b190347c39690051~mv2.png" height="50%" width="50%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_d5665ce0498d4af0b782c126cf712ae0~mv2.png" height="50%" width="50%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 19: Fill out the text input fields and click "Add user" to create two users.
</p>
<br />

<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_5700366e1670403f83d69c7144ce39f1~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 20: Return to the admin panel to create SLAs (service-level agreements).
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_5c0e0015dda64269aa8ecf1c6cdda4bf~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_b627d99bd74a46f585eeeb126298ccee~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 21: Navigate to "Manage" and then "SLA," and create three distinct SLA plans by clicking "Add new SLA Plan."
</p>
<br />

<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_dd286a07258e40b78b9e57209637f4b3~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 22: Create SLA 1 and name it SEV-A. Set the grace period to one hour on a 24/7 schedule, and then click "Add Plan."
</p>
<br />

<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_88e5750a3fe947a18d58142c6ff3aea7~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 23: Create SLA 2 and name it SEV-B. Set the grace period to four hours on a 24/7 schedule.
</p>
<br />

<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_ef71d2c8792242d28a71e2f4994c3bf3~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 24: Create the last SLA, which is less severe, and name it SEV-C. Set the grace period to eight hours, Monday through Friday from 8 AM to 5 PM.
</p>
<br />

<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_69aa8d9e70fb4855b6299d4af995c519~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 25: Proceed to create various help topics by clicking on the "Help Topics" tab.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_94778f580b0a437486507b075a049bc7~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_cbca1f2db51b49a8881b81695d30429b~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 26: Click on "Add new help topic," name it "Personal Computer Issues," and then click "Add topic."
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_f8e34d00109743bebc7170ece2721e3f~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_3ec65e833f76472e8676c998799b256b~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_f9bafab7ed2e453e9ef2a85784b46ddd~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 27: Add three more help topics with the following names:
<ul>
  <li>Password Reset</li>
  <li>Equipment Request</li>
  <li>Business Critical Outage</li>
 </ul> 
</p>
<br />
