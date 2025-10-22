# osTicket-post-install
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This lab demonstrates the post-installation configuration of osTicket to replicate how a real IT help desk is structured and managed.  
After deploying osTicket, I configured roles, departments, teams, SLAs, and help topics to simulate a functioning support environment — similar to what Tier 1/2 IT support techs work with daily.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents and Users
- Configure SLA Plans and Help Topics

<h2>Configuration Steps</h2>

<p>
<img width="1920" height="1080" alt="Screenshot (34)" src="https://github.com/user-attachments/assets/7ec68f51-9e3d-4cf2-a1cd-b2826b5986b3" />

</p>
<p>
First configure roles go to admin panel —-- agents —- roles  and make a super admin role with access to everything   next go to configure departments  admin Panel —- agents — departments and create a sysadmin role
</p>
<br />

<p>
<img width="1920" height="1080" alt="Screenshot (36)" src="https://github.com/user-attachments/assets/f753cc92-acea-415f-8404-6a1c1279a465" />

</p>
<p>
Next add a team by going to admin panel — agents —-- teams and create an online banking teams and add agents(we will do this later)  also allow an one to make tickets go to admin panel – settings – user settings and make sure Require registration and login to create tickets  is unchecked

</p>
<br />

<p>
<img width="1920" height="1080" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/c16340eb-9d7b-4e58-b77c-089887434239" />



</p>
<p>
Configure workers  Admin Panel -> Agents -> Add New
Jane (Dept: SysAdmins) John (Dept: Support) make sure to check there passwords so they may change it once there logged in for security

</p>
<br />

<p>
<img width="1920" height="1080" alt="Screenshot (44)" src="https://github.com/user-attachments/assets/d8174010-3b52-44bd-926b-756fed13f067" />

</p>
<p>
Configure  Users Agent Panel —--- Users —-Add New Karen  add new users as many as you want to create tickets
</p>
<br />


<p>
<img width="1920" height="1080" alt="Screenshot (49)" src="https://github.com/user-attachments/assets/a2023ab7-e3c2-4be1-912f-2c0ff24380e4" />

</p>
<p>
Configure SLA head to admin panel — manage —- sla 
We added our first SLA SLA-A our urgent one and we will add 2 more  Sev-A (Grace Period: 1 hour, Schedule: 24/7) Sev-B (Grace Period: 4 hours, Schedule: 24/7) Sev-C (Grace Period: 8 hours, Business Hours)
</p>
<br />

<p>
<img width="1920" height="1080" alt="Screenshot (52)" src="https://github.com/user-attachments/assets/a79dbc63-c8f8-4762-9efe-671e5761706c" />
</p>
<p>
It should look like this 
</p>
<br />


<p>
<img width="1920" height="1080" alt="Screenshot (64)" src="https://github.com/user-attachments/assets/1d3a67a7-e909-4e23-a29d-58b5721dce9a" />

</p>
<p>
Configure  help topics (For when users create a ticket)
Admin Panel — Manage — Help Topics   Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset,  Other

</p>

##  Why This Matters
Post-install configuration transforms osTicket from just a ticketing app into a functional support environment.  

This mirrors real-world IT service desk setups where:
- Departments & Teams** = ticket routing & ownership  
- Roles = access control  
- SLAs = service expectations & escalation  
- Help Topics = user-friendly ticket categorization

 Skills shown here are directly used in Tier 1 / Tier 2 IT roles.

---

## 🧪 Lessons Learned
- Setting up SLAs and help topics greatly improves ticket flow clarity.
- Proper team and role structure makes onboarding new agents easier.
- Understanding the admin panel in osTicket builds a foundation for other enterprise ticketing systems 
<br />


