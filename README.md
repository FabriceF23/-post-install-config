<p align="center"> <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/> </p> <h1>osTicket - Post-Install Configuration</h1> This guide outlines the post-install configuration steps for the open-source help desk ticketing system, osTicket, which I have set up. <h2>Environments and Technologies Used</h2> - **Microsoft Azure** (Virtual Machines/Compute) - **Remote Desktop** - **Internet Information Services (IIS)** <h2>Operating Systems Used</h2> - **Windows 10** (version 21H2) <h2>Post-Install Configuration Goals</h2> The main configuration goals after installation were: - Set up user roles and permissions. - Define departments for ticket visibility and management. - Organize teams for different tasks. - Enable open ticket creation by anyone. - Configure agents, users, service level agreements (SLA), and help topics. <h2>Step-by-Step Configuration</h2> <p> <img src="https://i.imgur.com/fOmiEF3.png" height="70%" width="70%" alt="Disk Sanitization Steps"/> <img src="https://i.imgur.com/CpzZXAy.png" height="70%" width="70%" alt="Disk Sanitization Steps"/> </p> <p> After setting up the osTicket system on a Windows Virtual Machine (from a previous project), I logged into the Admin panel. I created a new role called **"Supreme Admin"** and assigned it key permissions such as **Assign**, **Close**, **Create**, **Delete**, and **Edit**. Additionally, I created a new department called **"SysAdmins"** and set it as the "Top Level Department". </p> <br /> <p> <img src="https://i.imgur.com/aNqVwOh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> </p> <p> Next, I set up teams under the **Agents** tab. For example, I created a team for **"Online Banking"**. I also enabled the user registration and login feature so that users could create tickets. Subsequently, I created two new agents and assigned one to the **"SysAdmins"** department and the other to the regular **"Support"** department. </p> <br /> <p> <img src="https://i.imgur.com/9FrYNyx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> <img src="https://i.imgur.com/K6Flk2m.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> </p> <p> I then created two user accounts, **Karen** and **Ken**, to simulate customer tickets. I switched to the **Agent** panel to create these users, then returned to the Admin panel to configure Service Level Agreements (SLAs). I went to the **Manage** tab and created three SLAs with specific parameters: - **Sev-A**: 1-hour grace period, 24/7 schedule - **Sev-B**: 4-hour grace period, 24/7 schedule - **Sev-C**: 8-hour grace period, 25/7 schedule </p> <br /> <p> Lastly, in the **Help Topics** section under the **Manage** tab, I created various help topics to organize tickets better. These included: - **Business Critical Outage** - **Personal Computer Issues** - **Equipment Request** - **Password Reset** - **Other** </p>
