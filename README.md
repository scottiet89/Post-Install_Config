# Post-Install-Config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
Here's a tutorial on how to configure roles, departments, teams, users, agents, SLAs, and help topics on osTicket:.<br />

<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket with Microsoft Azure Part 2: Post-Install Configuration (Roles, Departments, SLAs, and More)](https://youtu.be/ooZva6raT4Y)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Follow this complete [osTicket Installation Tutorial](https://github.com/alexanderdrodriguez/osticket-prereqs) before staring this tutorial

<h2>Configuration Steps</h2>

<p> Before anything headover to localhost/osTicket/scp/login.php in your VM's browser and login using the admin account you created in the osTicket Instllation tutorial.</p>
<img src="https://i.gyazo.com/255cf2560f9907342d99cb6fb5120444.png">
<p>Step 1 Configure Roles: Go to the Admin Panel -> Click on Agents -> Select Roles -> Create a new role called "Supreme Admin"</p>
<img src="https://i.gyazo.com/6656e33d64730ea9a6fbd0da26bf53b3.png">
<img src="https://i.gyazo.com/d39fab5752b4b96ba3685215d9e64018.png">
<img src="https://i.gyazo.com/8cbc5f6806258fb1ff239abb29c88a0e.png">
<img src="https://i.gyazo.com/f423597ac97416b59d601cbac6d10523.png">
<img src="https://i.gyazo.com/e967c85ed942a62d58b15465e78820b6.png">
<img src="https://i.gyazo.com/6d870d55c1e56616297eacef1688d656.png">
<img src="https://i.gyazo.com/faad144ad4e02df4a71b82592b1d9e7e.png">
<img src="https://i.gyazo.com/faad144ad4e02df4a71b82592b1d9e7e.png">
</p>
<p>Step 2 Configure Departments: Go to the Admin Panel -> Click on Agents Select Departments -> Create a new department called "System Administrators"</p>
<img src="https://i.gyazo.com/7b4b44020cbc81500ed1c0261ea6b689.png">
<img src="https://i.gyazo.com/6e532b249875465a2e16e1e127890457.png">
<img src="https://i.gyazo.com/0782861e19987802fd07c386df246b94.png">
<img src="https://i.gyazo.com/93d01bcb04f16589fe562e0415fef781.png">
<p>Step 3 Configure Teams: Go to the Admin Panel -> Click on Agents -> Select Teams -> Create a new team: "Level II Support"</p>
<img src="https://i.gyazo.com/c64f23ca04731351c39db7218a6ad469.png">
<img src="https://i.gyazo.com/b5a20fef5a1fe7fe4d4b0ec1ebc15f73.png">
<img src="https://i.gyazo.com/107fe7744149636005fe44a51ddecb9b.png">
<p>Step 4 Configure Agents (workers): Go to the Admin Panel -> Click on Agents -> Select Add New -> Add two new agents: Jane and John</p>
<img src="https://i.gyazo.com/86db9259e8d109a2c0e9dcc854345d8c.png">
<img src="https://i.gyazo.com/a2edc751e893ea1d96dc064eeceec8cd.png">
<img src="https://i.gyazo.com/b3223f6647282b6328edbba31806b506.png">
<img src="https://i.gyazo.com/a6f26ad2b37fc941b0f6f4fa7d64d0d5.png">
<img src="https://i.gyazo.com/f3bce5178ca7c7718c3a37aecfb37572.png">
<img src="https://i.gyazo.com/5edb69d58d80ab26b0b561969a0b42af.png">
<img src="https://i.gyazo.com/7baee2071e1622074d57263a00810323.png">
<img src="https://i.gyazo.com/d0b06830e86e0b8b57070015757f3679.png">
<p>Step 5 Configure Users (customers): Go to the Agent Panel -> Click on Users -> Select Add New -> Add two new users: Karen and Ken</p>
<img src="https://i.gyazo.com/2759af55865ab0ce082f26435813723d.png">
<img src="https://i.gyazo.com/b655274d917b350a2aabfeebb254d58a.png">
<img src="https://i.gyazo.com/f6565a4e402005c59e7bad4c2d0f08e6.png">
<img src="https://i.gyazo.com/1e4344d2adee58c0efbceba573ba6a5b.png">
<img src="https://i.gyazo.com/3043e340379017a50b97295719c5e7f3.png">
<p>Step 6 Configure SLA: Go to the Admin Panel -> Click on Manage -> Select SLA -> Create three new SLAs: Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7), and Sev-C (8 hours, business hours)</p>
<img src="https://i.gyazo.com/87f76526e23f4068d5562ca21661a9e7.png">
<img src="https://i.gyazo.com/1db63a8638089c4c1bb6ac66c9fbb88f.png">
<img src="https://i.gyazo.com/54c946650ec20487ff27e618b6ee61c6.png">
<img src="https://i.gyazo.com/f50da5202fdc507ccca9474cbe1a212f.png">
<p>Step 7 Configure SLA: Go to the Admin Panel -> Click on Manage -> Select Help Topics -> Create four new help topics: Business Critical Outage, Personal Computer Issues, Equipment Request, and Password Reset</p>
<img src="https://i.gyazo.com/92b9bb89d43bae5ac627a99557251dbc.png">
<img src="https://i.gyazo.com/f763b4b157693d96434e6dff5d708b1f.png">
<img src="https://i.gyazo.com/f620abf907ad7be867f77a3c468ec5ab.png">
<img src="https://i.gyazo.com/ecb88743d033b30da01e713f9e946833.png">
<img src="https://i.gyazo.com/84f13f2237de52ae4a71483250cd3631.png">
<p>That's it! You've successfully configured roles, departments, teams, users, agents, SLAs, and help topics on osTicket.</p>
