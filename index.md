---
layout: default
---
<html><head>
<link rel="apple-touch-icon" sizes="180x180" href="assets/images/favicon/apple-touch-icon.png">
<link rel="icon" type="image/png" sizes="32x32" href="assets/images/favicon/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="assets/images/favicon/favicon-16x16.png">
<link rel="manifest" href="assets/images/favicon/site.webmanifest">
</head></html>
<title>HTML Reference</title>

## whoami <font size="3" color="#666">- Dom Ruggeri | DomRRuggeri@gmail.com | Germantown, WI</font>

My name is Dom Ruggeri. I'm a Systems Administrator specializing in PowerShell development, scripting, and automation. I work regularly with Windows Server, VMware, Hyper-V, Office 365, Azure, and Active Directory. I have a solid foundation in networking and server infrastructure.

I've worked as an IT professional for 10 years, and have had an interest in technology since childhood. I enjoy automating complex workflows and processes, and strive to eliminate as many manual tasks as possible. I help other IT professionals and organizations identify areas for automation in their daily work, and realize those solutions. 

* * *

## links

*    [LinkedIn](https://linkedin.com/in/domruggeri) - Feel free to reach out on LinkedIn. <br>
*    [PowerShell Tools](https://www.domruggeri.com) - I run a PowerShell blog, writing tools and tutorials. <br>
*    [Upwork](https://www.upwork.com/o/profiles/users/_~01b0dddb831cc7bb38/) - I freelance as a PowerShell developer, you can check out my profile here. <br>
*    [GitHub](https://github.com/DomRRuggeri) - Personal GitHub Repository. <br>

* * *

## skills / technologies

| PowerShell | Scripting & Automation | Module Development | REST API Integration | Toolmaking |
| GUI Applications | Windows Server | Active Directory | Microsoft 365 | VMware |
| Hyper-V | SCCM | DSC | Group Policy | Azure |
| Power Automate | SSO/OAuth | Azure App Registration | Endpoint Management | Enterprise Applications |

* * *

## recent projects 

### Service Desk Toolkit
>A PowerShell-driven GUI Application for day-to-day tasks of Service Desk technicians. Features include AD user/group information and management, SCCM software deployments, computer management, Remote Desktop management, NTFS permissions, Print Server Management, and Windows Defender tasks.

### OpsCommands PowerShell Module
>A PowerShell Module used by Infrastructure and Operations for gathering information, and environment management quickly. Tools include AD user unlocks, password resets, PC discovery, Microsoft Monitoring Agent set up, Bulk O365 group management,VM snapshot scheduling, Exchange mailbox permissions, and more.

### FSLogixMigration Module
>Enterprise-level PowerShell module for converting Roaming Profiles, and User Profile Disks to FSLogix Profile Containers. This module handled the discovery, transfer, verification, and configuration for Roaming and UPD profiles to an FSLogix environment.

### AD User Creation Tool
>A PowerShell-driven GUI Application for specialized user creation in a Hybrid AD environment. The tool was custom made to accommodate an existing onboarding proccess. An API integration was used to gather onboarding user information and needed apps, functions for copy groups of users, assigning O365 licenses, and automatic ticket creation for tasks handled by other teams.

<html>
<head>
<style type="text/css">
</style>

<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.collapsible {
  background-color: #64618D;
  color: #32D97B;
  cursor: pointer;
  padding: 4px;
  width: 25%;
  border: none;
  text-align: center;
  outline: none;
  font-size: 15px;
  font-family: "Consolas", monospace;

}

.active, .collapsible:hover {
  background-color: #555;
}

.content {
  padding: 0 18px;
  display: none;
  overflow: hidden;
}

</style>
</head>
<body>

<button class="collapsible">View Image Gallery</button>
<div class="content">

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box}
body {margin:0}
.mySlides {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 500px;
  position: relative;
  margin: auto;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: #32D97B;
  backgroud-color: #64618D;
  font-weight: bold;
  font-size: 18px;
  transition: 0.4s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(100,97,141,0.8);
}

/* Caption text */
.text {
  color: white;
  background-color: rgba(100,97,141,.6);
  font-size: 15px;
  padding: 5px 5px;
  position: absolute;
  bottom: 0px;
  width: 100%;
  text-align: center;
}


/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #64618D;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.4s ease;
}

.active1, .dot:hover {
  background-color: #32D97B;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 11px}
}
</style>
</head>
<body>
<div class="slideshow-container">

<div class="mySlides fade">
  <img src="assets\images\ServiceDeskToolkit\Main.png" style="width:100%">
  <div class="text">Service Desk Toolkit - Users and Groups</div>
</div>

<div class="mySlides fade">
  <img src="assets\images\ServiceDeskToolkit\Computers.png" style="width:100%">
  <div class="text">Service Desk Toolkit - Computer Tasks</div>
</div>

<div class="mySlides fade">
  <img src="assets\images\ServiceDeskToolkit\Groups.png" style="width:100%">
  <div class="text">Service Desk Toolkit - Groups</div>
</div>

<div class="mySlides fade">
  <img src="assets\images\ServiceDeskToolkit\Password.png" style="width:100%">
  <div class="text">Service Desk Toolkit - Password Reset</div>
</div>

<div class="mySlides fade">
  <img src="assets\images\ServiceDeskToolkit\Defender.png" style="width:100%">
  <div class="text">Service Desk Toolkit - Defender Tasks</div>
</div>

<div class="mySlides fade">
  <img src="assets\images\ServiceDeskToolkit\Print.png" style="width:100%">
  <div class="text">Service Desk Toolkit - Printer Management</div>
</div>

<div class="mySlides fade">
  <img src="assets\images\ServiceDeskToolkit\Logoff.png" style="width:100%">
  <div class="text">Service Desk Toolkit - Remote User Logoff</div>
</div>

<div class="mySlides fade">
  <img src="assets\images\UserCreator\Main.png" style="width:100%">
  <div class="text">AD User Creation - Main Screen</div>
</div>

<div class="mySlides fade">
  <img src="assets\images\UserCreator\Groups.png" style="width:100%">
  <div class="text">AD User Creation - Groups Window</div>
</div>

<div class="mySlides fade">
  <img src="assets\images\UserCreator\365lic.png" style="width:100%">
  <div class="text">AD User Creation - O365 Licence Window</div>
</div>

<div class="mySlides fade">
  <img src="assets\images\UserCreator\OU.png" style="width:100%">
  <div class="text">AD User Creation - OU Selection</div>
</div>

<a class="prev" onclick="plusSlides(-1)">&#10094;</a>
<a class="next" onclick="plusSlides(1)">&#10095;</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span>
  <span class="dot" onclick="currentSlide(4)"></span>
  <span class="dot" onclick="currentSlide(5)"></span>   
  <span class="dot" onclick="currentSlide(6)"></span> 
  <span class="dot" onclick="currentSlide(7)"></span>
  <span class="dot" onclick="currentSlide(8)"></span>
  <span class="dot" onclick="currentSlide(9)"></span>   
  <span class="dot" onclick="currentSlide(10)"></span> 
  <span class="dot" onclick="currentSlide(11)"></span>
</div>

<script>
var slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active1", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active1";
}
</script>

</body>
</html> 
 
</div>

<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.display === "block") {
      content.style.display = "none";
    } else {
      content.style.display = "block";
    }
  });
}
</script>
<br><br>
</body>
</html>

* * *

## professional experience

### Ellsworth Adhesives \| Germantown, WI<br><font color="#a873b6"><b>Systems Administrator</b></font><font color="#64618D"> | May, 2018 - Present</font>

Automated server deployment, user creation, and PC management tasks. Monitored and supported an environment of 200+ servers, and 1000+ end users globally. Collaborated with business unit leaders to identify and deliver areas for IT improvement. Streamlined existing IT processes. Worked regularly with VMware, Office365, Active Directory, and Cisco Meraki management tasks.

#### Key Achievements

*    Created a PowerShell toolkit for Tier 1-2 Service Desk technicians. Features included AD user/group information and management, SCCM software deployments, computer management, remote desktop management, NTFS permissions, print server management, and Windows Defender tasks.<br><br>
*    Developed a PowerShell-driven GUI Application for user creation in a Hybrid AD environment. Implemented an API integration with the ticketing system to gather onboarding user information and needed applications. Included functions for copying groups of users, assigning Office365 licenses, and automatic ticket creation for tasks overseen by other teams.<br><br>
*    Created A PowerShell Module used by Infrastructure and Operations for gathering information, and environment management quickly. Tools include AD user unlocks, password resets, PC discovery, Microsoft Monitoring Agent set up, Bulk O365 group management,VM snapshot scheduling, Exchange mailbox permissions, and more.<br><br>

* * *

### Independent Contractor \| Upwork<br><font color="#a873b6"><b>PowerShell Developer</b></font><font color="#64618D"> | March, 2019 - 2021</font>

Top Rated Freelance PowerShell Developer and Systems Administrator. Completed 30+ projects with over 20 different clients and have maintained a 100% job success rate. Practiced CI/CD pipelines for PowerShell Module development and version control. Jobs included modifying existing scripts, creating frontend user interfaces for PowerShell scripts, and developing new PowerShell solutions for automating administration.

#### Key Achievements

*    Lead Developer for enterprise-level PowerShell module used for converting Roaming Profiles to FSLogix Profile Containers. The module handled the discovery, transfer, validation, and configuration for Roaming and UPD profiles to an FSLogix environment.<br><br>
*    Created a PowerShell-driven GUI Application for gathering Office365 Audit Logs. The final product accumulated audit information for specified users, services, and timeframes, and exported results to formatted Excel spreadsheets.<br><br>

* * *

### Systems Incorporated \| Germantown, WI<br><font color="#a873b6"><b>IT Systems Specialist</b></font><font color="#64618D"> | February 2017 - May, 2018</font>

Sole IT specialist for all day-to-day IT needs in a manufacturing company. Included consulting with users, and determining hardware and software needs. Managed VMware infrastructure, backups, Active Directory, Group Policy, and On-Premise Exchange services.

#### Key Achievements

*    Researched and implemented a new Service Desk solution for IT and Maintenance departments. Migrated data from existing Service Desk, configured email automation, and provided a seamless transition for end users.<br><br>
*    Implemented Microsoft WDS and MDT imaging process to improve Help Desk efficiency, and to assist in a Windows 10 migration. Created configurations for automated software installs by department, utilized Group Policy, and maintained services to deliver up to date software.<br><br>
*    Lead and completed a project to implement Digital Signage at two corporate offices. Tested various software and platforms, established and configured physical devices for
implementation, purchased all needed equipment, and coordinated with various departments for proper delegation.<br><br>

* * *

### Independent Contractor, Milwaukee, WI<br><font color="#a873b6"><b>Systems Administrator</b></font><font color="#64618D"> | April 2016 – January 2017</font>

Met with small businesses and assessed current and future IT needs. Provided solutions, pricing, and implementation. Conducted desktop hardware upgrades, Operating System upgrades and migrations, printer consolidation, hard drive replacements, and met various customer needs.

#### Key Achievements

*    Upgraded warehouse desktops, assessed usage and hardware needs for 15 PCs, ordered new desktops, scheduled installation of each with manager and staff to minimize downtime. Trained users for Windows 7.<br><br>
*    Independent motorcycle repair shop- replaced hard drives in failing PC’s, migrated company data to centralized location and made available to needed desktops. Networked IP camera solution, and improved performance of existing PCs.<br><br>

* * *

### TAKKT America Holding, Milwaukee, WI<br><font color="#a873b6"><b>Systems Administrator</b></font><font color="#64618D"> | May 2015 – Feb 2016</font>

Managed Microsoft and Linux servers and applications, provided desktop support, VPN user management, and network and server administration. Implemented and supported Virtual Desktop Infrastructure. Effectively planned projects, and implemented desktop support and IT operation advancements.

#### Key Achievements
*    Completed a company-wide domain migration, allowing a seamless transition for users while meeting deadlines and minimizing business impact.<br><br>
*    Composed PowerShell scripts to streamline Microsoft Exchange tasks which enabled all team members to effectively meet advanced email needs.<br><br>
*    Promptly handled and mitigated unexpected email, VPN, and application issues and outages.<br><br>

<font color="#a873b6"><b>Junior Systems Administrator</b></font><font color="#64618D"> | May 2013 – May 2015</font>

End-user support, hardware fixes, software installation, and PC
deployment. Managed users and security, desktop support, virus and malware removal, asset
tracking, user training, and documentation.


#### Key Achievements
*    Planned, and implemented a company-wide desktop upgrade to Windows 7 for all company sites in North America.<br><br>
*    Created, tested, streamlined, and deployed OS images for ease of desktop management, resulting in quick turn-around time for desktop repairs.<br><br>
*    Scheduled with management for training of 200+ users on Windows 7, while mitigating impact on the business.<br><br>
*    Performed extensive software compatibility checks between Windows XP and 7.<br><br>

<font color="#a873b6"><b>IT Service Desk</b></font><font color="#64618D"> |  March 2013 – May 2013</font>

Desktop support, software configuration and deployment, and
maintaining printing environment. Provided and assisted with shared file services for end-users.

#### Key Achievements
*    Established relations with various print vendors to implement a replacement of in-place printing environment, cutting annual cost on toner, hardware, and maintenance.<br><br>
*    Evaluated, and presented available options for a print environment refresh to decision-making management.<br><br>
*    Created software packages and configurations for remote deployment.<br><br>

* * *
## additional skills/interests

| C# Programming | PCB Design/Manufacturing | 3D Printing | CAD/Fusion360 |
| Electrical Engineering | Graphic Design/GIMP | Video Editing/Production | DaVinci Resolve |
| Pinball Restoration/Servicing | Arduino/Raspberry Pi | Stable Diffusion/OpenAI | Unreal Engine 5 |

* * *

## education

| Name      |   Diploma     |   Year Completed   |
|:----------|:--------------|:---------|
| Waukesha County Technical College | Associates Degree - IT Network Specialist | 2016 |
| Menomonee Falls High School | High School | 2011 |

* * *
###### Dom Ruggeri \| DomRRuggeri@gmail.com \| Germantown, WI