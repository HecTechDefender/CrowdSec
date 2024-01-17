<h1>Building a SOC Home Lab - CrowdSec</h1>

 ### 

<h2>Description</h2>
In this project, I'm on a mission to build a SOC home lab! This project will cover pfSense, Active Directory, Windows Workstation, Sysmon and CrowdSec. My goal? Creating a space where I can experiment and learn the ropes of real-world cybersecurity from the comfort of my home! 
<br />


<h2>Utilities Used</h2>

- <b>CrowdSec</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (22H2)

<h2>Program walk-through:</h2>

<br/>
<br />
<br />
 Go to the crowdsec site. Select "create free account". Create a free account and log in to CrowdSec. 
 For Windows installation, go to the GitHub page. Download the .msi file on the Windows computer. (server and workstation) Launch it.            <br/>
<img src="https://i.imgur.com/AthkOW8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
             <br/>
<img src="https://i.imgur.com/xuOppSr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
  <br/>
<img src="https://i.imgur.com/lTh56DN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
             <br/>
<img src="https://i.imgur.com/ylSK2bh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />          
<br />
Contrary to Linux, CrowdSec does not support the automatic configuration at installation time. If you want to be able to detect something other than RDP or SMB brute force, then you will need to customize your acquisition configuration. Launch Powershell as an administrator in CrowdSec's folder. 
Command: .\cscli collections install crowdsecurity/windows-firewall <br/>
<img src="https://i.imgur.com/vqZA1h7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Open the acquis.yaml file in "C:\ProgramData\CrowdSec\config". Add this to it.          <br />
<img src="https://i.imgur.com/mXFEjpJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br />
  <br/> 
 
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
                          <br/>

<br />

<br />
                          <br/>
 
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
                          <br/>
 
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
                          <br/>
       
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
                       <br/>

<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />

<br />
                       <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<br />
                       <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />

<br />

<br />
                       <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
<br /> 


<br />



<br />
                       <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br /> 
<br />
<br />
<br />                 <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 
<br />

<br />
                       <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br /> 
 
                 
<br />

<br /> 
<br />

<br />
                        <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br /> 
 
                 
<br />

<br /> 
<br />

<br />
                         <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br /> 
 
                 
<br />

<br /> 
<br />

<br />
                          <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br /> 
 
                 
<br />

<br /> 
<br />

<br />
                           <br />
 <img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br /> 
 
                 
<br />

<br /> 
<br />

<br />
                            <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br /> 
 
                 
<br />


<br /> 

