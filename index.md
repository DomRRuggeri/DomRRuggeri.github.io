---
layout: default
---
<title>HTML Reference</title>

## whoami <font size="3" color="#666">- Dom Ruggeri | DomRRuggeri@gmail.com | Menomonee Falls, WI</font>

My name is Dom Ruggeri. I'm a System Administrator specializing in PowerShell development, scripting, and automation. I work regularly with Windows Server, VMware, Hyper-V, Office 365, Azure, and Active Directory. I have a solid foundation in networking and server infrastructure.

I've worked as an IT professional for 7+ years, and have had an interest in technology since childhood. I enjoy automating complex workflows and processes, and strive to perform as few manual tasks as possible. I help other IT professionals and organizations identify areas for automation in their daily work, and realize those solutions. 

* * *

## links

*    [Upwork](https://www.upwork.com/o/profiles/users/_~01b0dddb831cc7bb38/) - I freelance as a PowerShell developer, you can check out my profile here. <br>
*    [LinkedIn](https://linkedin.com/in/domruggeri) - Feel free to reach out on LinkedIn. <br>
*    [PowerShell Tools](https://www.domruggeri.com) - I run a PowerShell blog, writing tools and tutorials. <br>

* * *

## skills / technologies

| PowerShell | Scripting & Automation | Module Development | REST API Integration | Toolmaking |
| GUI Applications | Windows Server | Active Directory | Office 365 | VMware |
| Hyper-V | SCCM | DSC | Group Policy | Azure |

* * *

## recent projects

### Service Desk Toolkit
>A PowerShell-driven GUI Application for day-to-day tasks of Service Desk technicians. Features include AD user/group information and management, SCCM software deployments, computer management, Remote Desktop management, NTFS permissions, Print Server Management, and Windows Defender tasks.
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.collapsible {
  background-color: #64618D;
  color: #32D97B;
  cursor: pointer;
  padding: 4px;
  width: 100%;
  border: none;
  text-align: center;
  outline: none;
  font-size: 15px;
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

<button class="collapsible">View Gallery</button>
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
  color: green;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
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
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: #666;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #666;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
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
<br>
<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 7</div>
  <img src="assets\images\ServiceDeskToolkit\Main.png" style="width:100%">
  <div class="text">Users and Groups</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 7</div>
  <img src="assets\images\ServiceDeskToolkit\Computers.png" style="width:100%">
  <div class="text">Computer Tasks</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 7</div>
  <img src="assets\images\ServiceDeskToolkit\Groups.png" style="width:100%">
  <div class="text">Groups</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">4 / 7</div>
  <img src="assets\images\ServiceDeskToolkit\Password.png" style="width:100%">
  <div class="text">Password Reset</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">5 / 7</div>
  <img src="assets\images\ServiceDeskToolkit\Defender.png" style="width:100%">
  <div class="text">Defender Tasks</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">6 / 7</div>
  <img src="assets\images\ServiceDeskToolkit\Print.png" style="width:100%">
  <div class="text">Printer Management</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">7 / 7</div>
  <img src="assets\images\ServiceDeskToolkit\Logoff.png" style="width:100%">
  <div class="text">Remote User Logoff</div>
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
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
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


### OpsCommands PowerShell Module
>A PowerShell Module used by Infrastructure and Operations for gathering information, and environment management quickly. Tools include AD user unlocks, password resets, PC discovery, Microsoft Monitoring Agent set up, Bulk O365 group management,VM snapshot scheduling, Exchange mailbox permissions, and more.

### FSLogixMigration Module
>Enterprise-level PowerShell module used by Microsoft for converting Roaming Profiles, and User Profile Disks to FSLogix Profile Containers. This module handled the discovery, transfer, verification, and configuration for Roaming and UPD profiles to an FSLogix environment.

### AD User Creation Tool
>A PowerShell-driven GUI Application for specialized user creation in a Hybrid AD environment. The tool was custom made to accommodate an existing onboarding proccess. An API integration was used to gather onboarding user information and needed apps, functions for copy groups of users, assigning O365 licenses, and automatic ticket creation for tasks handled by other teams.

* * *

## professional experience

### Ellsworth Adhesives \| Germantown, WI<br><font color="#a873b6"><b>Systems Administrator</b></font><font color="#64618D"> | May, 2018 - Present</font>

System monitoring, 

### Independent Contractor - Upwork \| Menomonee Falls, WI<br><font color="#a873b6"><b>PowerShell Developer | Systems Administrator</b></font><font color="#64618D"> | March, 2019 - Present</font>

Upwork Description

### Systems Incorporated \| Germantown, WI<br><font color="#a873b6"><b>IT Systems Specialist</b></font><font color="#64618D"> | February 2017 - May, 2018</font>

Systems Description

### TAKKT America Holding, Milwaukee, WI<br><font color="#a873b6"><b>System Administrator</b></font><font color="#64618D"> | May 2015 – Feb 2016</font>

Management of Microsoft and Linux servers and applications, IT
operations, desktop support, VPN user management, network administration tasks, and server
administration. Administrated and supported a dynamic Virtual Desktop Infrastructure.
Effectively planned projects, and implemented desktop support and IT operation advancements.

#### Key Achievements
*    Completed a company-wide domain migration, allowing a seamless transition for users
while meeting deadlines and minimizing business impact.
*    Composed PowerShell scripts to streamline Microsoft Exchange tasks which enabled all
team members to effectively meet advanced email needs.
*    Promptly handled and mitigated unexpected email, VPN, and application issues and
outages.

<font color="#a873b6"><b>Junior System Administrator</b></font><font color="#64618D"> | May 2013 – May 2015</font>

End-user support, hardware fixes, software installation, and PC
deployment. Managed users and security, desktop support, virus and malware removal, asset
tracking, user training, and documentation.

#### Key Achievements
*    Planned, and implemented a company-wide desktop upgrade to Windows 7 for all
company sites in North America.
*    Created, tested, streamlined, and deployed OS images for ease of desktop
management, resulting in quick turn-around time for desktop repairs.
*    Scheduled with management for training of 200+ users on Windows 7, while mitigating
impact on the business.
*    Performed extensive software compatibility checks between Windows XP and 7.

<font color="#a873b6"><b>IT Service Desk</b></font><font color="#64618D"> |  March 2013 – May 2013</font>

Desktop support, software configuration and deployment, and
maintaining printing environment. Provided and assisted with shared file services for end-users.

#### Key Achievements
*    Established relations with various print vendors to implement a replacement of in-place
printing environment, cutting annual cost on toner, hardware, and maintenance.
*    Evaluated, and presented available options for a print environment refresh to decision-
making management.
*    Created software packages and configurations for remote deployment.

* * *

## education

| Name      |   Diploma     |   Year Completed   |
|:----------|:--------------|:---------|
| Waukesha County Technical College | Associates Degree - IT Network Specialist | 2016 |
| Menomonee Falls High School | High School | 2011 |

* * *
###### Dom Ruggeri \| DomRRuggeri@gmail.com \| Menomonee Falls, WI