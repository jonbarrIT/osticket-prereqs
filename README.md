# osticket-prereqs
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This section outlines the prerequisites and installation highlights of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Cloud)
- Remote Desktop Connection
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- PHP Manager
- Heidi SQL 12.3.0
- osTicket V1
- Rewrite AMD
- VC Redist

<h2>Highlights</h2>

<p>
<img src="https://i.imgur.com/nTmtswN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p> 
Install / Enable IIS in Windows WITH CGI and Common HTTP Features. World Wide Web Services -> Application Development Features -> CGI, Common HTTP Features
</p>
<br />

<p>
<img src="https://i.imgur.com/dwMaHFS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
If this appear, choose "Keep" the file. This message will occur as the contents within the prereqs are outdated, however these versions must used in conjunction with other programs to allow osTicket to run. Afterwards, select the drop down near "Show more" and choose "Keep anyway". Other browsers may be more effiecnt if download does not complete.
</p>
<br />

<p>
<img src="https://i.imgur.com/ZAYQ0K0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Note that some extensions are not enabled. Go back to IIS, sites -> Default -> osTicket. Double-click PHP Manager. Click “Enable for the following extensions:
  
- Enable: php_imap.dll
- Enable: php_intl.dll
- Enable: php_opcache.dll

</p>
<br />
