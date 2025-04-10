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

- Create a Virtual Machine in Microsoft Azure
- Connect to Virtual Machine via Remote Desktop
- Enable IIS in Windows
- Install MySQL
- Install Heidi SQL
- Finish configuration in browser window

<h2>Installation Steps</h2>

<p>
<img width="482" alt="image" src="https://github.com/user-attachments/assets/4b2935d8-7030-4564-93a7-d084d2a7c798" />
</p>
<p>
Firstly, a Virtual Machine in Microsoft Azure must be created. This machine will house all of our pre-aggregated installation files and eventually os-Ticket.</p>
<br />

<p>
<img width="301" alt="image" src="https://github.com/user-attachments/assets/a1a6dcfe-5d8f-41d1-a633-9c8d6e7b0107" />
</p>
<p>
Next, we retrieve the public IP Adress from the Virtual Machine and connect to it via Remote Desktop.
</p>
<br />

<p>
<img width="191" alt="image" src="https://github.com/user-attachments/assets/fb8bfc6c-f706-416f-8934-9c51e1f67f43" />
</p>
<p>
Next, we enable Internet Information Services with CGI by accessing IIS, World Wide Web Services, Application Development Features, and CGI. 
</p>
<br />

<p>
<img width="227" alt="image" src="https://github.com/user-attachments/assets/2bac4a9e-c0ec-417b-be20-d1f608d888e9" />
</p>
<p>
Then, we install PHP Manager.
</p>
<br />

<p>
<img width="227" alt="image" src="https://github.com/user-attachments/assets/9da3b6c7-99f6-4a7e-aa65-89ea909412d4" />
</p>
<p>
After, we install the Rewrite Module.
</p>
<br />

<p>
<img width="305" alt="image" src="https://github.com/user-attachments/assets/3d63749a-ab93-42c4-868f-045916736540" />
</p>
<p>
Next, we create a PHP directory in the C: drive.
</p>
<br />

<p>
<img width="272" alt="image" src="https://github.com/user-attachments/assets/fc828b31-3bdc-4922-a141-0b2841a26d97" />
</p>
<p>
Next, we extract PHP binaries into the C: drive.
</p>
<br />

<p>
<img width="219" alt="image" src="https://github.com/user-attachments/assets/60bb7ea3-5645-4c1c-98f3-262c57a2d71c" />
</p>
<p>
Next, we install a Microsoft Visual C++ redistributable. 
</p>
<br />

<p>
<img width="224" alt="image" src="https://github.com/user-attachments/assets/29b92a30-f4a1-4b49-a542-79be1a70bfd5" />
</p>
<p>
Now, nearing completion of all the necessary files, we install MySQL which is a database necessary for os-Ticket to run.
</p>
<br />

<p>
<img width="230" alt="image" src="https://github.com/user-attachments/assets/1702db1c-3212-4aa5-b327-e566c387e287" />
</p>
<p>
Next, register PHP from within IIS, this makes the web server aware of PHP.
</p>
<br />

<p>
<img width="346" alt="image" src="https://github.com/user-attachments/assets/dbc5c680-cc55-450a-96ff-c5ca8e19f878" />
</p>
<p>
Next, we install os-Ticket itself and add necessary functionalities from the PHP manager such as PHP Imap, and PHP opcache.
</p>
<br />

<p>
<img width="209" alt="image" src="https://github.com/user-attachments/assets/2ba84517-78ac-4072-86ce-cc14862142a7" />
</p>
<p>
Lastly, we install HeidiSQL, an application that will allow us to connect to our database.</p>
<br />

<p>
<img width="266" alt="image" src="https://github.com/user-attachments/assets/525125c2-7a12-4e3e-a0d9-1998cb813b0b" />
</p>
<p>
Finally, we finish configuring os-Ticket in the browser.
</p>
<br />

<p>
<img width="182" alt="image" src="https://github.com/user-attachments/assets/861ed8b7-b002-4d35-876f-0f71906e076f" />
</p>
<p>
Congratulations, we have successfully installed os-Ticket.
</p>
<br />
