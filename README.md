<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>
<h1>osTicket Post-Install Configuration</h1>
This is a tutorial on how to set up the osTicket Help desk after installation. If you completed the process of creating a osTicket Help desk, copy and paste this link.

http://localhost/osTicket/scp/login.php

If you have not gone through the process of installing osTicket, go to this link for the tutorial and come back here when you have completed it.
https://github.com/jarrettm98/osticket-prereqs


<h2> Operating Systems Used </h2>
- Windows 10
<h2>Post-Install Config Steps</h2>

Once logged in with the user and password created, the admin panel should be the default mode. Next, click on the agents tab. This should go to the area where agents along with their teams, roles, and departments will be managed. First, the agents need roles. Go to the Roles tab and "Add New Role" and name it "Supreme Admin." Next, click on the "Permissions" tab. There will be three tabs of different types of permissions. For this role, check every box in all three categories.

![osTicket Create Role](https://github.com/jarrettm98/osticket-post-install-config/assets/140662793/4d3aee33-b8c0-4549-a01e-93b000b16607)


Now, the agents need Departments. Go to the "Departments" tab. Then, click "Add New Department" and name it "System Administrators." (No need to mess with any of the settings other than the name)

![osTicket Create Department](https://github.com/jarrettm98/osticket-post-install-config/assets/140662793/a7267e3c-8f3e-401f-afc3-eb23ccb5dc04)

Now, the agents need teams. Go to the "Teams" tab and create a "Level II Support. (Level I Support will already be created by default)

Now, it is time to create an agent. Go to "Agents" tab under the Agents Tab. (Use the picture below to prevent confusion) Name this agent whatever you want. (For fun, make it a name that isn't yours) Now, give them an email and username. To give this agent a password, click the "Set Password" button next to the user text window. In the window that pops up, uncheck the bubble that says "Send the agent a password reset email" then click "set". (Write down the user and password for future use) Next, in the access tab, set the department to System Administrators and the role to Supreme Admin. Also, in "Extended Access" give this agent access to the "Support" department as a "Supreme Admin" Next, in the "Teams" tab, add the agent to "Level II Support." Finally, click "Create."

![osTicket Create Agent](https://github.com/jarrettm98/osticket-post-install-config/assets/140662793/99a7edd2-9847-45ca-b814-d1019adf19d1)

Now, time to create some SLA's. These will be the severity types of the tickets that will be sent in. To create SLA levels, go to the "Manage" tab. Click on the SLA tab and "Add New SLA Plan." These SLA plans can be anything. However, in this tutorial there will be 2 SLA's. (Sev-A and Sev-C) For Sev-A, the Grace period will be 1 Hour and the Schedule will be 24/7. (Really Severe) Click "Add Plan". Sev-C will be 8 Hours and the schedule will be Business Hours (Monday-Friday 8-5 w/ U.S. Holidays) Click Add Plan. Feel free to add more SLA's.

![osTicket Create SLA](https://github.com/jarrettm98/osticket-post-install-config/assets/140662793/c83841f1-cde5-40b0-8621-337d535741a2)


Now, the tickets are going to need Help Topics to categorize the tickets. Go to the "Manage" tab and click on the "Help Topics" tab underneath it. Click "Add New Help Topic." These Help Topics can be about anything. In this tutorial there will be 2 Help Topics (Business Critical Outage and Password Reset) Name the topic and click "Add Topic." If other help topics come to mind, feel free to add more topics.

![osTicket Create Help Topics](https://github.com/jarrettm98/osticket-post-install-config/assets/140662793/1b29ea5d-7182-4cfb-afea-21cdaa10557c)


Now, to create a user that will be submitting tickets, go to the "Agent Panel" in the top right of the page. Click on the "Users" tab and click "Add User." Give the user a name and email address. For this tutorial, there are two users created. Feel free to add more if desired.

![osTicket Create User](https://github.com/jarrettm98/osticket-post-install-config/assets/140662793/6b061f9b-d9c5-46f9-bd54-2203e550cdc4)

Congratulations, you set up the help desk!

To learn how to submit tickets as well as resolve them, click on this link:

https://github.com/jarrettm98/osticket-ticket-lifecycle
