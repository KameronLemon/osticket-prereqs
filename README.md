<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- IIS in windows manager with CGI
- PHP Manager for IIS
- Rewrite Module (rewrite_amd64_en-US.msi)
- PHP 7.3.8
- VC_redist.x86.exe
- MySQL 5.5.62

<h2>Installation Steps</h2>


![Capture](https://github.com/user-attachments/assets/0cc5a1c0-7f79-44ae-93f7-c20901fb4a5a)
![image](https://github.com/user-attachments/assets/b4c0f1ee-62be-4b29-a78b-5649f42f7001)





</p>
<p>
Within your virtual machine install / enable IIS in windows with CGI (World Wide Web Services -> Application Development Features -> [X] CGI).

</p>
<br />

![image](https://github.com/user-attachments/assets/fe50b369-ad88-4219-a013-bf4a149afec9)


</p>
<p>
Download and install PHP manager for IIS.
</p>
<br />

![image](https://github.com/user-attachments/assets/59cad3b8-5773-42d1-aede-5f5b0d502b8b)


</p>
<p>
Download and install rewrite module (rewrite_amd64_en-US.msi).
</p>
<br />

![image](https://github.com/user-attachments/assets/4124d897-73a3-4a20-a3a2-5a67edc8f716)
![image](https://github.com/user-attachments/assets/c7e2e8e7-c6c2-4834-afe2-3658bed197e3)

</p>
<p>
Create brand the new directory C:\PHP and then unzip PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) into the “C:\PHP” folder.

</p>
<br />

![image](https://github.com/user-attachments/assets/bbbb0098-090d-4359-99c8-2af0ca63ad28)

</p>
<p>
Download and install VC_redist.x86.exe.

</p>
<br />

![image](https://github.com/user-attachments/assets/7996289f-6467-49bc-9f69-931d342ea0c3)
![image](https://github.com/user-attachments/assets/4767556d-6bc9-49d9-92c4-34256b771203)
![image](https://github.com/user-attachments/assets/17b4b10c-3a18-456e-a0a0-22008865dc5c)
![image](https://github.com/user-attachments/assets/4de71998-4697-49c6-a585-5a32ab277502)

</p>
<p>
Download and install install MySQL 5.5.62 (mysql-5.5.62-win32.msi). Create and save your login credentials.

![image](https://github.com/user-attachments/assets/2948f1e8-881c-4f27-b2db-597785a192f1)

</p>
<p>
Open IIS as an admin and register PHP within the application.

![image](https://github.com/user-attachments/assets/409c8cb7-a4b5-47a7-9c6f-c9f5156758d1)

</p>
<p>
Download and unzip osTicket-v1.15.8.zip” and copy the “upload” folder into “c:\inetpub\wwwroot”. After that Reload IIS










