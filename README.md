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

