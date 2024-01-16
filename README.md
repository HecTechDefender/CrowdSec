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
           <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
           <br />
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
           Add a new Active Directory Forest               <br/>
<img src="https://i.imgur.com/oHYlLbE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br /> 
 
                 
<br />

<br /> 
<br />

<br />
         Leave the default configurations and set a password.                  <br/>
<img src="https://i.imgur.com/ITxolF1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br /> 
 
                 
<br />

<br /> 
<br />

<br />
       Leave the DNS part default. Check the NetBIOS domain name. Leave the default path. Launch the install. Reboot when asked.                     <br/>
<img src="https://i.imgur.com/yCG1Bm4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br /> 
 
                 
<br />

<br /> 
<br />

<br />
     Now you have the Active Directory Server, you need to populate it with misconfigurations to perform analysis. We will use BadBlood for this task, Download it on AD, Extract it, Launch Powershell as admin, go to Badblood folder, Launch Invoke-BadBlood.ps1 and let the magic happen (this will take several minutes)
 <br />
 <img src="https://i.imgur.com/ckj2T3q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br /> 
 
                 
<br />

<br /> 
<br />

<br />
        Now, you have the Active Directory configuration (2500 users, 500 groups, OU, 100 computers, etc.), have fun! <br/>
<img src="https://i.imgur.com/qHvBc1A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br /> 
 
                 
<br />


<br /> 

