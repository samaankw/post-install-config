<p align= "center">
<img src= "https://i.imgur.com/9PeLFEi.jpeg" alt="osTicket logo"/>
<H2> osTicket-Post-Install-Configuration</H2>
<p> Part 2 covers the post-installation configuration of osTicket, the open-source helpdesk ticketing system. In this section, you'll complete the necessary setup steps to ensure the system is secure, functional, and ready for use</p>

<h2>Environments and Technologies Used </h2>
- Microsoft Azure( Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<H2> Operating Systems Used </H2>
- Windows (21H2)

<h2> List of Prequisites </h2>
- Microsoft Azure
- Virtual Machine
- osTicket


<h2> Good Things to Know</h2>
- Roles
- Departments
- Teams
- Users
- Agent
- Service Level Agreements(SLA)

<h2>Installation Steps</h2>
<h2>Step 1: Open osTicket and Log in</h2>
<p>Log in to your osTicket dashboard using the admin credentials you created during installation.</p> 

[If you haven’t installed osTicket yet or need guidance, please check out my step-by-step installation tutorial for help getting started](https://github.com/samaankw/osticket-prereqs)</p>
<img src="https://i.imgur.com/2A5zjEi.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h2>Step 2: Configure Roles</h2>
<p>First, ensure that you are in the Admin Panel by checking the top-right corner of the screen—if it says "Agent," that means you are currently in the Admin Panel.

Next, navigate to the Agent tab and select Roles, then click on Add New Role. In the form that appears, enter "Supreme Admin" as the role name.

Switch to the Permissions tab and check every box under the Tickets, Tasks, and Knowledgebase sections to grant full access. Once all permissions are selected, click Add Role to save and create the new role.</p>
<img src="https://i.imgur.com/sgTcFc6.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/bfDkCom.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h2> Step 3 Configure Departments</h2>
<p>Make sure you're still in the Admin Panel by checking the top-right corner of the screen.

Next, navigate to the Agent tab and click on Departments, then select Add New Department. In the form, enter "System Administrators" as the department name. Finally, click Create Department to save the new department. </p>

<img src="https://i.imgur.com/sgTcFc6.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/jPe0wgn.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/> 

<h2> Step 4: Configure Teams </h2>
<p>Navigate to the Agent tab and click on Teams, then select Add New Team. In the form, enter "Level II Support" as the team name.

Next, go to the Members tab, and from the "Select Agent" dropdown menu, choose your name. Once you've selected yourself, click Create Team to finalize and add the new team.</p>

<img src="https://i.imgur.com/d58vKNE.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/ErYtOgV.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h2> Step 5: Allow Anyone to Create Tickets</h2>
<P> Navigate to Settings and then select User Settings. In the User Settings section, ensure that the box next to "Registration Required: Require registration and login to create tickets" is unchecked. This will allow users to submit tickets without needing to register or log in first.</P>

<img src="https://i.imgur.com/C29Mjzj.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h2> Step 6: Configure Agents </h2>
<p>Navigate to the Agent tab and click on Add New Agent. In the form that appears, enter the following details:

Name: Jane Doe

Email: jane.doe(@)osticket.com

Username: jane.doe

Next, click on Set Password and uncheck the option that says "Send the Agent a Password Reset Email." Set the password to something of your choice, and make sure to uncheck the box that says "Require Password Change at Next Login."

Finally, click Set to save the new agent. </p>

<img src="https://i.imgur.com/rVqL685.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/xW2J3nU.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>Navigate to the Access tab.

Under Primary Department, click the Department dropdown menu and select System Administrators. Then, in the Role dropdown menu, choose Supreme Admin.

For Extended Access, select the Department dropdown menu, choose Support, and then click Add next to Supreme Admin.

Next, go to the Team tab, select the Team dropdown menu, and choose Level II Support. Click Add to assign the team, and then click Create to finalize the setup.</p>

<img src="https://i.imgur.com/yyWRbRr.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/dNxdkmH.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>Create a new agent and replace Jane with John by following the same steps as before, with some adjustments to the Primary Department.

Navigate to the Access tab and under Primary Department, open the Department dropdown menu and select Support. For the Role, choose View Only from the dropdown menu.

In the Extended Access section, select Department, choose Support, and click Save Changes to apply the updates for John. </p>

<img src="https://i.imgur.com/VgWL2Fc.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/yyWRbRr.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h2> Step 7: Configure Users </h2>
<img src="https://i.imgur.com/D6otlsu.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>Navigate to the Users tab to create a new user.

In the form that appears, enter the following details:

Email Address: Karen(@)osticket.com

Full Name: Karen Karen

Once you've filled out the information, click Add User to save the new user profile.</p>

<img src="https://i.imgur.com/U61zrnJ.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/> 

<p>Go back to the Users tab to create another user.

In the form, enter the following details:

Email Address: Ken(@)osticket.com

Full Name: Ken Ken

After filling in the information, click Add User to save the new user profile. </p>
<img src="https://i.imgur.com/fjGXX3i.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/> 

<h2> Step 8: Configure Service Level Agreements (SLA)</h2>
<p>To create an SLA, go to the Manage tab and select SLA, then click on Add New SLA Plan.

In the form that appears, enter the following details:

Name: SEV-A

Grace Period: 1

For the Schedule, select 24/7 from the dropdown menu. Once you've entered the details, click Add Plan to save the new SLA. </p>
<img src="https://i.imgur.com/1iE1jba.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/UEMWLmr.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/> 

<P>Create another SLA by entering the following details:

Name: SEV-B

Grace Period: 4

Schedule: Select 24/7 from the dropdown menu.

Once you've filled out the form, click Add Plan to save this new SLA. </P>
<img src="https://i.imgur.com/yYBXnI8.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>  


<p>Create the final SLA by entering the following details:

Name: SEV-C

Grace Period: 8

Schedule: Select Monday-Friday 8 AM - 5 PM with U.S. Holidays from the dropdown menu.

Once you've filled in the details, click Add Plan to save this SLA.
</p>
<img src="https://i.imgur.com/IkaRGJU.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/> 

<h2> Step 9: Configure Help Topics </h2>

<p>To create the four Help Topics, go to the Manage tab and select Help Topics, then click on Add New Help Topic.

For each topic, enter the following names:

Business Critical Outage

Personal Computer Issues

Equipment Request

Password Reset

After entering each topic name, click Add Topic to save it.</p>


<img src="https://i.imgur.com/Yz2Sroy.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/> 

<p> Congratulations! You have configured osTicket successfully! You have completed the second part of this three-part osTicket Install/Configuration/Ticket-Creation tutorial series.</p>






