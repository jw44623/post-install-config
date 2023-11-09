<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create a Resource Group
  ![image](https://github.com/jw44623/osticket-prereqs/assets/150184762/26bbae34-e7b8-4772-a552-b7d205161ded)

- Create a Windows 10 Virtual Machine (VM) with 2 Virtual CPUs and a Linux (Ubuntu 20.04) Virtual Machine with 2 Virtual CPUs
  ![image](https://github.com/jw44623/osticket-prereqs/assets/150184762/e39dda9e-885a-4774-82cb-50b96cf8eb77)
![image](https://github.com/jw44623/osticket-prereqs/assets/150184762/d170dd36-d539-4a25-a15d-9d9237e708da)


<h2>Installation Steps</h2>


Install / Enable IIS in Windows WITH
CGI and Common HTTP Features

![image](https://github.com/jw44623/osticket-prereqs/assets/150184762/23280825-972b-4f9d-9416-98c0ac168623)
</p>
<br />

Download and install PHP Manager for IIS and the Rewrite Module
![image](https://github.com/jw44623/osticket-prereqs/assets/150184762/7f651181-1c3b-43a7-a534-83a173cd2bb8)

Create the directory C:\PHP
