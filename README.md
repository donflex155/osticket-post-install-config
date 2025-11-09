<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket — Post-Installation Configuration</h1>
After successfully installing osTicket, several post-installation steps are required to secure, configure, and prepare the system for production or testing.<br />


<h2>Environments and Technologies Used</h2>

- Operating System & Platform-"IIS + PHP"
- Web Application Stack-"MySQL"
- Database Layer-"SMTP"
- Email Services-"TLS, firewall, permissions"
- Security & Access-"Admin panel, phpMyAdmin, CLI"
- Backup & Monitoring-"Logs, mysqldump, Task Scheduler"
- Tools / Utilities

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Secure the Installation
- Configure Email
- Create Departments and Help Topics
- Configure Ticket Forms and Fields 
- Add Agents and Assign Roles
- Configure Business Hours and SLA Policies
- Customize Templates and Branding
- Enable Required PHP Extensions
- Backup & Maintenance
- Monitor and Maintain
- Recommended Checks


<h2>Configuration Steps</h2>

<p>
<img width="778" height="730" alt="image" src="https://github.com/user-attachments/assets/4e6a3f83-6735-42b4-8dd1-e418b895f5d6" />

</p>
<p>
Step 1: Secure the Installation

Remove the Setup Directory:

Delete: C:\inetpub\wwwroot\osTicket\setup
Set Permissions to “Read” only: C:\inetpub\wwwroot\osTicket\include\ost-config.php
Configure SSL/TLS in IIS or your web server.

</p>
<br />

<p>
<img width="1153" height="890" alt="image" src="https://github.com/user-attachments/assets/e252eaaf-ee8f-49df-86ad-c1b86d6b51d9" />

</p>
<p>
Incoming Emails (IMAP/POP3 Fetching)
Recommended: Configure a mailbox for support tickets.
Admin Panel → Emails → Email Fetching → Add mailbox (IMAP preferred).
Test email retrieval to ensure tickets are created automatically.
</p>
<br />

<p>
<img width="1194" height="723" alt="image" src="https://github.com/user-attachments/assets/445816ff-3a8c-41ae-9668-f21f90bd2024" />

<img width="1194" height="559" alt="image" src="https://github.com/user-attachments/assets/f85afd42-2219-4560-9d5d-1355f8632748" />

<img width="1058" height="801" alt="image" src="https://github.com/user-attachments/assets/b0fb15fd-4e13-4b25-8e88-cbacf30cdefb" />

<img width="1143" height="632" alt="image" src="https://github.com/user-attachments/assets/08583a59-c23a-455d-ae02-7c31009c8a5b" />


</p>
<p>
3: Create Departments and Help Topics
Admin → Agents → Departments → Add logical teams (e.g., IT, HR, Finance).
Admin → Manage → Help Topics → Add topics mapping to departments.
</p>
<br />


<img width="1167" height="898" alt="image" src="https://github.com/user-attachments/assets/ae162c95-6752-4ff0-a288-92b23af79320" />


<img width="1198" height="929" alt="image" src="https://github.com/user-attachments/assets/137a013e-eaa7-48b9-a9b9-c9112bbed029" />


<img width="1191" height="921" alt="image" src="https://github.com/user-attachments/assets/f80110f4-fc3d-4e04-93f5-bb9a3c9587fd" /> 


<img width="1190" height="901" alt="image" src="https://github.com/user-attachments/assets/2d01b6a0-ca4a-4f48-9b4c-3b99334e8ddd" />



<img width="1188" height="826" alt="image" src="https://github.com/user-attachments/assets/f2af4359-93dc-4e80-8ab4-951ebf7f1238" /> 


<img width="802" height="663" alt="image" src="https://github.com/user-attachments/assets/71663ecd-a671-4981-8ec2-e8c70d2b8af6" />


<img width="809" height="530" alt="image" src="https://github.com/user-attachments/assets/a76665f1-4325-47ae-8b15-571dea2bb0af" />





</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />


<p>
<img width="1197" height="743" alt="image" src="https://github.com/user-attachments/assets/79bcf401-2a0c-4c7c-8bdd-f69e2ea5faf1" />

<img width="1002" height="890" alt="image" src="https://github.com/user-attachments/assets/193fc8d9-cec2-4803-9b38-54575b759ca2" />

</p>
<p>
Add Agents and Assign Roles
Admin → Agents → Add new agents.
Assign roles and departments to each agent.
Ensure permissions follow the least privilege principle.
</p>
<br />


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />



<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />



<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />



<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
