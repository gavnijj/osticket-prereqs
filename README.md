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

- Enable Internet Information Services(IIS) in Windows with CGI
- Install PHP manager for IIS
- Install the Rewrite Module & C++ redistributable file
- Install MySql database & HeidiSQL
- Install osTicket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/6ppktNF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is the first window that pops up once osTicket has been installed and you attempt to load it through IIS. PHP manager should be installed into the PHP folder in the C:\ directory. The upload folder from the osTicket zip file should be copied into c:\inetpub\wwwroot directory and the file should be renamed to osTicket  
</p>
<br />

<p>
<img src="https://i.imgur.com/9SICaO9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Going into PHP Manager from IIS allows you to enable the extensions in osTicket that were disabled initially once osTicket was launched. php_imap.dll extension allows for sending/fetching emails, managing mailboxes, and handling attachments. The php_intl.dll extension enables internationalization support. This provides functions for handling localized formatting, text processing, collation, etc. The php.opcache.dll extension improves PHP performance by caching precompiled script bytecode in memory.
</p>
<br />

<p>
<img src="https://i.imgur.com/mvbHcW3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
You can name the help desk on this page and create the first admin user for the help desk. To complete the Database Settings section you have to log into your database application and then create another database specific to osTicket and then provide the credentials for the Database Settings section.
</p>

<p>
<img src="https://i.imgur.com/4onYKlv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Use HeidiSQL to make a connection to the MySQL database to configure stuff in there. A database is created called osTicket inside of osTicket and the actual installation that is happening inside of the browser is going to make use of the database and put stuff in there.
</p>

<p>
<img src="https://i.imgur.com/r4IV4ek.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
osTicket has been installed and it provides URLs to log in as a admin and to log in as a user, if you want to submit a ticket. 
</p>

<p>
<img src="https://i.imgur.com/5vUSsXc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
osTicket admin user login page.
</p>
<br />
