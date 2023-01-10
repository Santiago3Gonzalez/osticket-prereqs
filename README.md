<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install/ Enable IIS with CGI
- Download and install PHP manager for IIS
- Download and install Rewrite Module
- Download PHP 7.3.8 and unzip in the directory file
- Download Microsoft visual c++ 2015
- Download MySQL 5.5.62
- Register PHP from within IIS
- Install osTicket
- Enable php_imap.dll, php_intl.dll, php_opcache.dll
- Rename ost-config and disable inheritance and add new permissions for everyone
- Install HeidiSQL
- Set up osTicket in browser


<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/5c4CWTI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is after I had downloaded Iss and configured and then as you can see I enable
</p>
<br />

<p>
<img src="https://i.imgur.com/MERWp3R.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is after I had installed the PHP manager
</p>
<br />

<p>
<img src="https://i.imgur.com/IjlCWop.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Before it was retired, I used MySQL to download: 
     Php 5.6.31
  ; Php 7.0.33 (x86)
  ; Php 7.1.29
  ; Php 7.2.26 (x86)
  ; Php 7.3.25

</p>
<br />

<p>
<img src="https://i.imgur.com/BphYCkU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is after I install osTicket and changed the name of sample config in its file to just ost-config. I also make sure to disable inheritance and allow all permissons in its properties
</p>
<br />

<p>
<img src="https://i.imgur.com/K4i53QL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is after I install Hedi and then setup osTicket in the browser. 
</p>
<br />
