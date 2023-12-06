<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

<ul>
  <li>Roles Configuration</li>
  <li>Department Setup</li>
  <li>Team Setup</li>
  <li>Agent Setup</li>
  <li>SLA Configuration</li>
  <li>Help Topics Setup</li>
</ul>

<h2>Role Configuration</h2>

<p>
<img src="https://github.com/Dennistrangithub/post-install-config/assets/152820266/ba399b04-9689-4101-88cf-6a32ccd89bd9" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I go to the Admin panel and make a new role for supreme admins
</p>
<br />

<p>
<img src="https://github.com/Dennistrangithub/post-install-config/assets/152820266/b5dcfff1-0939-47b5-ac95-b425e0dfdae4" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Adding Supreme admin as a new role and giving the role all permissions
</p>
<br />

<h2>Department Setup</h2>
<p>
<img src="https://github.com/Dennistrangithub/post-install-config/assets/152820266/c8eaa557-7974-45d6-ba3c-0d19e624ab9b" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<img src="https://github.com/Dennistrangithub/post-install-config/assets/152820266/3eddc129-977b-4e5c-9821-afc2f16b1cad" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
I go to the department panel and add a new department called "System Administrators"
</p>
<br />

<h2>Team Setup</h2>
<p>
<img src="https://github.com/Dennistrangithub/post-install-config/assets/152820266/1646e110-4231-457e-bcb0-43ff5b256f72" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<img src="https://github.com/Dennistrangithub/post-install-config/assets/152820266/4d2d6b06-4757-48af-8786-784f183221a4" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
I continue to create teams within the Ticketing System such as "Support II"
</p>
<br />

<h2>Member Setup</h2>
<p>
<img src="https://github.com/Dennistrangithub/post-install-config/assets/152820266/5ec82e41-7822-4c43-94df-46b8a90d2369" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<img src="https://github.com/Dennistrangithub/post-install-config/assets/152820266/317599b0-25f2-446e-9aaa-3a7405b5cf3d" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
Now I create team members within the system and assign them to different departments.
This is the First one, and I also set him/her in a department I added.
</p>
<br />

<h3>2nd Person</h3>
<p>
<img src="https://github.com/Dennistrangithub/post-install-config/assets/152820266/a1c5e416-ca5f-45d0-ac49-5105aa83de39" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<img src="https://github.com/Dennistrangithub/post-install-config/assets/152820266/1a3bd1fe-09c2-41ae-9cbc-263f0d0257b7" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/Dennistrangithub/post-install-config/assets/152820266/993ed4c7-7ca7-41ed-8232-381c1fb72242" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
This is the second one, I set him/her in a department I added and I'll add him to the support team.
</p>
<br />

<h2>SLA Configuration</h2>
<p>
<img src="https://github.com/Dennistrangithub/post-install-config/assets/152820266/bbb36339-5fed-4cc5-a4d4-9b8b1e2158cb" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
This is the part where I set up the SLA configurations according to how sever the problem is.
<li>SEV-A (Grace period is 1 hour within a 24/7 scedual)
<li>SEV-B (Grace period within a 4 hour window within a 24/7 scedual)
<li>SEV-C (Grace period of 8 hours within a 9/5 scedual)
</p>
