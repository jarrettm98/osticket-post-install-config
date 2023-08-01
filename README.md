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

Once logged in with the user and password created, the admin panel should be the default mode. Next, click on the agents tab. This should go to the area where agents along with their teams, roles, and departments will be managed. First, go to the Roles tab and "Add New Role" and name it "Supreme Admin." Next, click on the "Permissions" tab. There will be three tabs of different types of permissions. For this role, check every box in all three categories.

![osTicket Create Role](https://github.com/jarrettm98/osticket-post-install-config/assets/140662793/4d3aee33-b8c0-4549-a01e-93b000b16607)


Now, go to the "Departments" tab. Then, click "Add New Department" and name it "System Administrators." (No need to mess with any of the settings other than the name)

![osTicket Create Department](https://github.com/jarrettm98/osticket-post-install-config/assets/140662793/a7267e3c-8f3e-401f-afc3-eb23ccb5dc04)

Next, go to the "Teams" and create a "Level II Support. (Level I Support will already be created by default)

Now, it is time to create an agent. Go to "Agents" tab under the Agents Tab. (Use the pictue below to prevent confusion) Name this agent whatever you want. (For fun, make it a name that isn't yours) Now, give them an email and username. To give this agent a password, click the "Set Password" button next to the user text window. In the window that pops up, uncheck the bubble that says "Send the agent a password reset email" then click "set". (Write down the user and password for future use) Next, in the access tab, set the department to System Administrators and the role to Supreme Admin. Next, in the "Teams" tab, add the agent to "Level II Support." Finally, click "Create."

![osTicket Create Agent](https://github.com/jarrettm98/osticket-post-install-config/assets/140662793/99a7edd2-9847-45ca-b814-d1019adf19d1)


