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

Set up all the agents, departments, and other functions that we will need to have access to in order to fulfill our role as a helpdesk professional. This is done after we have installed all of the prequisites for OSticket.




<h2>Configuration Steps</h2>

I am going to make a supreme admin role. When in the admin panel, you can go to Agents-> Roles and then create a new role. Since this is a Supreme Admin, we will give them every permission. This screenshot does not show the Supreme Admin role made, but just the page where you CAN make the role. 

![image](https://github.com/MatthewTulloch/post-install-config/assets/165750459/8133519f-7c15-4702-b7b5-2f6c938a01d7)

Select the Departments button in the agents tab so we can create a new Department. Agents are assigned to a specific department depending on their assigned role within the helpdesk. I created the System Administrators department, where I'll put the supreme admins. Other settings such as SLAs, managers and other email settings can be set up in the departments tab as well. 


![image](https://github.com/MatthewTulloch/post-install-config/assets/165750459/db600e2c-1c4b-49b8-a607-7f57d26e1a0d)



I will now create a team, teams allow you to pull agents from different departments so that you can have a specific team to deal with certain degrees on difficult problems. To set up a team go to Agents->Teams. We already have a Level I support team, so we will create a Level II one as well.


![image](https://github.com/MatthewTulloch/post-install-config/assets/165750459/8b57bf91-a4dd-4709-b73d-1ce5c73657d9)



Now, I will create the Agents. Agents solve tickets. Agents are assigned primary departments, they are also given a primary role for tickets sent to their department. Agents can be given access to other departments other than their own + have different roles depending on which department they are in.

![image](https://github.com/MatthewTulloch/post-install-config/assets/165750459/dee40be1-3bb0-4981-b575-ec64e0acbb21)

![image](https://github.com/MatthewTulloch/post-install-config/assets/165750459/62dc9603-f4e9-4985-adc0-a92ddf0e822a)

Time to create Users! Users will be the ones oftentimes making tickets, and we need their email address.

![image](https://github.com/MatthewTulloch/post-install-config/assets/165750459/8af9fc1f-680e-474d-bf46-bd213b3b4974)

SLAs (service level agreement) Plans provide a length of time in which Agents should complete a tickets. There is often a period of time laid out (ex. SEV-C is 24/7 in business hours (8), which are 9-5 for many of us)

![image](https://github.com/MatthewTulloch/post-install-config/assets/165750459/06e6c3e0-2aab-4135-982b-e110dea167de)

Help topics help people categorize whatever ticket they are making. The example here is for a password reset, we have a help topic for that.

![image](https://github.com/MatthewTulloch/post-install-config/assets/165750459/e680365c-38c2-49f8-a445-51ec99a468e8)



