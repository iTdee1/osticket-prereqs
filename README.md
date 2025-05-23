# osticket-prereqs
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create a resource group
- Create and deploy a Windows VM
- Download osTicket Installation files
- Extract files into a new dicectory
- Install software and dependencies
- Item 6
- Item 7

<h2>Installation Steps</h2>
<h3>Create an Azure Virtual Machine</h3>
   - Purpose Set up a virtual machine (VM) in the Azure cloud environment to host the osTicket application.
   <h4>Details:</h4>
   <p> - VM named **osticket-vm** is created with Windows 10 and 4 virtual CPUs for performance.
     - A username and password configuredare set for access.
     - Remote Desktop is used to connect to the VM for further configurations. 
- Item 6
- Item 7 </p> 


<p> <img width="1435" alt="1 step" src="https://github.com/user-attachments/assets/0471d9a6-d601-44dd-8e59-b3f5f1b3eee3"
height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
create
</p>
<br /> 
<p> <img width="1435" alt="Screen Shot 2025-04-19 at 8 07 45 PM" src="https://github.com/user-attachments/assets/0ffe058a-ce91-42ca-9c52-f8a98dbca881"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
step2
</p>
<br />
<p> <img width="1435" alt="Screen Shot 2025-04-19 at 8 08 52 PM" src="https://github.com/user-attachments/assets/df8677d3-96e6-4688-98d8-11c5e656977a"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
steps 3
</p>
<br />
<p> <img width="1435" alt="Screen Shot 2025-04-19 at 8 14 01 PM" src="https://github.com/user-attachments/assets/1b2902da-8434-45cb-a9ea-59637b27bcb8"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
step 4
</p>
<br />
<p> <img width="1435" alt="Screen Shot 2025-04-22 at 9 46 29 PM" src="https://github.com/user-attachments/assets/2ae3a5a5-39d5-42b8-8580-538b3626a06a"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
step 5
</p>
<br />
<p> <img width="1435" alt="Screen Shot 2025-04-22 at 10 10 55 PM" src="https://github.com/user-attachments/assets/583f0bcc-1208-47d9-9d02-18d844066ac4"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download
</p>
<br />
<p> <img width="1440" alt="Screen Shot 2025-04-22 at 10 14 49 PM" src="https://github.com/user-attachments/assets/fa3c9aa0-8747-4eaa-bf8a-7d2463f4a993"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Extract files into a new dicectory
</p>
<br />
<p><img width="1440" alt="Screen Shot 2025-04-22 at 10 21 26 PM" src="https://github.com/user-attachments/assets/c61e055f-a487-45fe-b267-3c3b6aeef8c3"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Photo of loopback before web server installation and configuration
</p>
<br />
<p><img width="1440" alt="Screen Shot 2025-04-22 at 10 27 28 PM" src="https://github.com/user-attachments/assets/365e8572-55d2-454f-b557-314d85d16e85"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Web server  and IIS installed and configured
</p>
<p> <img width="1435" alt="Screen Shot 2025-04-22 at 10 22 35 PM" src="https://github.com/user-attachments/assets/d14b23d9-80b4-447f-8d29-8af52385f21c"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p> <img width="1440" alt="Screen Shot 2025-04-22 at 10 27 10 PM" src="https://github.com/user-attachments/assets/d7125583-1cf6-4d4f-93fb-66190dfc1144"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p> <img width="1435" alt="Screen Shot 2025-04-22 at 10 51 15 PM" src="https://github.com/user-attachments/assets/e820d12d-7079-4c48-8d87-d7bc98b53f16"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Photo of loopback with web server installed and configured
</p>
<p><img width="1435" alt="Screen Shot 2025-04-23 at 3 44 22 PM" src="https://github.com/user-attachments/assets/8eb8e6a1-e7cf-4d14-a677-607f98432f9a"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p><img width="1435" alt="Screen Shot 2025-04-22 at 10 57 16 PM" src="https://github.com/user-attachments/assets/0e5e5bab-ea96-4e03-9b8f-b1e700854791"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here I added a little personalization to the web page with a marquee and welcome note.
</p>
<br />
<p> <img width="1435" alt="Screen Shot 2025-04-22 at 11 00 07 PM" src="https://github.com/user-attachments/assets/2d5de63a-220b-4670-a953-fab3836325d9"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Installation of software and other dependencies
</p>
<p> <img width="1435" alt="Screen Shot 2025-04-22 at 11 00 25 PM" src="https://github.com/user-attachments/assets/2d8840dd-56b6-4186-8b1a-af08c46a5714"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p> <img width="1435" alt="Screen Shot 2025-04-22 at 11 01 56 PM" src="https://github.com/user-attachments/assets/b9fa5281-2f11-4af9-b010-a438daec2972"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p> <img width="1435" alt="Screen Shot 2025-04-22 at 11 10 27 PM" src="https://github.com/user-attachments/assets/dd28bd1d-6716-4f7c-b1d3-a774b9e06134"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />
<p> * <img width="1435" alt="Screen Shot 2025-04-22 at 11 11 48 PM" src="https://github.com/user-attachments/assets/6e82a6a3-3405-4efa-95a9-11e53023f2b6"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Created a new PHP directory on C/ drive and extracted the PHP management files into the new directory
</p>
<br />

<p><img width="1435" alt="Screen Shot 2025-04-22 at 11 13 22 PM" src="https://github.com/user-attachments/assets/41e08c44-6b16-4164-80a2-8cf8947b0b1d"height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img width="1435" alt="Screen Shot 2025-04-22 at 11 14 07 PM" src="https://github.com/user-attachments/assets/4f5bafde-c85c-464e-82cf-f045a87f3336" />
  <img width="1435" alt="Screen Shot 2025-04-22 at 11 16 34 PM" src="https://github.com/user-attachments/assets/a6c30ff3-d969-4d27-b23f-139c0236d931" /> Configuration of MySql database
  *
  *
  *

</p>

<p>
Installation of MySQL and HediSql
</p>
<br /> 

<p> * <img width="1435" alt="Screen Shot 2025-04-22 at 11 35 04 PM" src="https://github.com/user-attachments/assets/54458991-2e56-4ed1-94ac-372a746f02c5"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
*******************************************Description and purpose to be added************************************************
</p>
<br /><p> * <img width="1435" alt="Screen Shot 2025-04-22 at 11 11 48 PM" src="https://github.com/user-attachments/assets/6e82a6a3-3405-4efa-95a9-11e53023f2b6"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
*******************************************Description and purpose to be added************************************************y
</p>
<br /><p> * <img width="1435" alt="Screen Shot 2025-04-22 at 11 11 48 PM" src="https://github.com/user-attachments/assets/6e82a6a3-3405-4efa-95a9-11e53023f2b6"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
*******************************************Description and purpose to be added************************************************
</p>
<br /><p> * <img width="1435" alt="Screen Shot 2025-04-22 at 11 11 48 PM" src="https://github.com/user-attachments/assets/6e82a6a3-3405-4efa-95a9-11e53023f2b6"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
*******************************************Description and purpose to be added************************************************
</p>
<br /><p> * <img width="1435" alt="Screen Shot 2025-04-22 at 11 11 48 PM" src="https://github.com/user-attachments/assets/6e82a6a3-3405-4efa-95a9-11e53023f2b6"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
*******************************************Description and purpose to be added************************************************
</p>
<br /><p> * <img width="1435" alt="Screen Shot 2025-04-22 at 11 11 48 PM" src="https://github.com/user-attachments/assets/6e82a6a3-3405-4efa-95a9-11e53023f2b6"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
*******************************************Description and purpose to be added************************************************
</p>
<br /><p> * <img width="1435" alt="Screen Shot 2025-04-22 at 11 11 48 PM" src="https://github.com/user-attachments/assets/6e82a6a3-3405-4efa-95a9-11e53023f2b6"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
*******************************************Description and purpose to be added************************************************
</p>
<br /><p> * <img width="1435" alt="Screen Shot 2025-04-22 at 11 11 48 PM" src="https://github.com/user-attachments/assets/6e82a6a3-3405-4efa-95a9-11e53023f2b6"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
*******************************************Description and purpose to be added************************************************
</p>
<br /><p> * <img width="1435" alt="Screen Shot 2025-04-22 at 11 11 48 PM" src="https://github.com/user-attachments/assets/6e82a6a3-3405-4efa-95a9-11e53023f2b6"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
*******************************************Description and purpose to be added************************************************
</p>
<br /><p> * <img width="1435" alt="Screen Shot 2025-04-22 at 11 11 48 PM" src="https://github.com/user-attachments/assets/6e82a6a3-3405-4efa-95a9-11e53023f2b6"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
*******************************************Description and purpose to be added************************************************
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
*******************************************Description and purpose to be added************************************************
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /> 
