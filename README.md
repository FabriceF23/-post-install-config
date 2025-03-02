<p align="center"> 
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/> 
</p> 

<h1>osTicket - Post-Install Setup</h1> 

<p>This guide will show you how to set up osTicket, a tool that helps businesses manage customer support tickets (like a request for help). After you install osTicket, here's how to make it work for your team.</p>

<h2>Tools and Technologies Used</h2>
<ul>
  <li>Microsoft Azure (this is where we set up virtual machines to run osTicket)</li>
  <li>Remote Desktop (a way to control another computer from far away)</li>
  <li>Internet Information Services (IIS) (helps run websites)</li>
</ul>

<h2>Operating System</h2>
<p>Windows 10 (version 21H2)</p>

<h2>Setup Goals</h2>
<p>Here’s what we wanted to set up after installing osTicket:</p>
<ul>
  <li>Create roles with different permissions for users (like who can do what).</li>
  <li>Make departments so tickets are easier to organize.</li>
  <li>Set up teams for specific tasks.</li>
  <li>Allow anyone (customers) to submit tickets.</li>
  <li>Set up agents (people who help customers), users (customers), service levels (how fast we respond), and help topics (the categories of tickets).</li>
</ul>

<h2>Step-by-Step Setup</h2>
<p> 
  <img src="https://i.imgur.com/fOmiEF3.png" height="70%" width="70%" alt="Configuring roles and permissions"/>
  <img src="https://i.imgur.com/CpzZXAy.png" height="70%" width="70%" alt="Creating departments and roles"/>
</p>

<p>First, I logged into the admin area of osTicket (the control panel) from the Windows Virtual Machine we set up. I created a new role called "Supreme Admin" with full permissions. This means they can assign tickets, close them, delete, or change them. I also made a department called "SysAdmins" and made it the top department in the system.</p>

<br />
<p>
  <img src="https://i.imgur.com/aNqVwOh.png" height="80%" width="80%" alt="Creating teams and agents"/>
</p>

<p>Then, I set up some teams in the Agents section. For example, I created a team for "Online Banking." I also turned on a setting so that users (customers) could create tickets by registering and logging into the system. After that, I created two agents: one for the "SysAdmins" department and one for the "Support" department.</p>

<br />
<p>
  <img src="https://i.imgur.com/9FrYNyx.png" height="80%" width="80%" alt="Creating user accounts"/>
  <img src="https://i.imgur.com/K6Flk2m.png" height="80%" width="80%" alt="Setting up SLAs and help topics"/>
</p>

<p>I created two test users, Karen and Ken, to act as customers. I went to the Agent panel to make their accounts. Then, I went back to the Admin panel and set up Service Level Agreements (SLAs). These are just rules about how fast we’ll respond to different types of issues. Here’s what I set up:</p>

<ul>
  <li>Sev-A: We’ll respond within 1 hour, anytime (24/7).</li>
  <li>Sev-B: We’ll respond within 4 hours, anytime (24/7).</li>
  <li>Sev-C: We’ll respond within 8 hours, available most of the time (25/7 – meaning almost always except a very short time).</li>
</ul>

<br />
<p>Lastly, I created different Help Topics to help organize the tickets. These are things like:</p>

<ul>
  <li>Business Critical Outage (when something important goes wrong)</li>
  <li>Personal Computer Issues</li>
  <li>Equipment Request (asking for new equipment)</li>
  <li>Password Reset</li>
  <li>Other (for anything else that doesn’t fit)</li>
</ul>

