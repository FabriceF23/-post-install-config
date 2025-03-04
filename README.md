<!-- Step 1: Show the osTicket Logo -->
<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" height="75%" width="100%" alt="osTicket logo"/>
</p>

<!-- Step 2: Title of the Guide -->
<h1>osTicket - Post-Install Configuration</h1>

<!-- Step 3: Simple description of what this tutorial will help with -->
<p>This tutorial will guide you through setting up and configuring osTicket after it's installed.</p>

<!-- Step 4: Tools and Technologies Used -->
<h2>Environments and Technologies Used</h2>
<ul>
  <li>Microsoft Azure (Virtual Machines/Compute)</li>
  <li>Remote Desktop</li>
  <li>Internet Information Services (IIS)</li>
</ul>

<!-- Step 5: Operating System Used -->
<h2>Operating Systems Used</h2>
<ul>
  <li>Windows 10 (21H2)</li>
</ul>

<!-- Step 6: Configuration Objectives -->
<h2>Post-Install Configuration Objectives</h2>
<ul>
  <li>Configure Roles</li>
  <li>Configure Departments</li>
  <li>Configure Teams</li>
  <li>Configure Agents</li>
  <li>Configure Users</li>
  <li>Configure SLA</li>
  <li>Configure Help Topics</li>
</ul>

<!-- Step 7: Role Configuration (example of admin role setup) -->
<h3 align="center">Configure Roles</h3>
<p>Go to Admin Panel -> Agents -> Roles.</p>
<p>Set up roles like "Supreme Admin" with full permissions.</p>
<img src="https://i.imgur.com/SXpTf20.png" height="75%" width="100%" alt="Definitions"/>

<!-- Step 8: Department Configuration -->
<h3 align="center">Configure Departments</h3>
<p>Go to Admin Panel -> Agents -> Departments.</p>
<p>Create departments like "System Administrators."</p>
<img src="https://i.imgur.com/83gWQsO.png" height="75%" width="100%" alt="System Administrators"/>

<!-- Step 9: Configure Teams -->
<h3 align="center">Configure Teams</h3>
<p>Go to Admin Panel -> Agents -> Teams.</p>
<p>Create teams like "Level II Support."</p>
<img src="https://i.imgur.com/BnPrcDH.png" height="75%" width="100%" alt="Level II Support"/>

<!-- Step 10: Allow Everyone to Create a Ticket -->
<h3 align="center">Allow Anyone to Create Ticket</h3>
<p>Go to Admin Panel -> Settings -> User Settings.</p>
<p>Make sure "Require registration and login to create tickets" is unchecked.</p>
<img src="https://i.imgur.com/QsJjOuM.png" height="75%" width="100%" alt="ticket creations"/>

<!-- Step 11: Configure Agents (Adding workers) -->
<h3 align="center">Configure Agents</h3>
<p>Go to Admin Panel -> Agents -> Add New.</p>
<p>Add agents like "Jane Doe" and "John Doe" to manage tickets.</p>
<img src="https://i.imgur.com/ujpOdKM.png" height="75%" width="100%" alt="agent one access"/>

<!-- Step 12: Configure Users (Add customers) -->
<h3 align="center">Configure Users</h3>
<p>Go to Admin Panel -> Users -> Add New.</p>
<p>Add customers like "Ken User" and "Karen User" who will create tickets.</p>
<img src="https://i.imgur.com/vbPd3uK.png" height="75%" width="100%" alt="user access"/>

<!-- Step 13: Configure SLA (Set Response Times) -->
<h3 align="center">Configure SLA</h3>
<p>Go to Admin Panel -> Manage -> SLA.</p>
<p>Create different SLAs (Service Level Agreements) for response times.</p>
<ul>
  <li>Sev-A (1 hour, 24/7)</li>
  <li>Sev-B (4 hours, 24/7)</li>
  <li>Sev-C (8 hours, business hours)</li>
</ul>
<img src="https://i.imgur.com/6AAF3Ju.png" height="75%" width="100%" alt="sev one"/>

<!-- Step 14: Configure Help Topics (Categories of requests) -->
<h3 align="center">Configure Help Topics</h3>
<p>Go to Admin Panel -> Manage -> Help Topics.</p>
<p>Create topics like "Business Critical Outage" and "Password Reset."</p>
<img src="https://i.imgur.com/Xdhp63v.png" height="75%" width="100%" alt="business critical outage"/>

<!-- Final Note -->
<p>Now your osTicket system is set up! It's important to practice handling tickets and learning how to support your users. This skill is key for help desk specialists, as they are the first point of contact for customers with problems.</p>
