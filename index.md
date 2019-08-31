---
layout: default
---
### whoami

> Dom Ruggeri \| DomRRuggeri@gmail.com \| Menomonee Falls, WI

My name is Dom Ruggeri. I'm a System Administrator specializing in PowerShell development, scripting, and automation. I work regularly with Windows Server, VMware, Hyper-V, Office 365, Azure, and Active Directory, with a solid foundation in networking and server infrastructure.

### Links
*    [Upwork](https://www.upwork.com/o/profiles/users/_~01b0dddb831cc7bb38/) - I freelance as a PowerShell developer, you can check out my profile here.
*    [LinkedIn](https://linkedin.com/in/domruggeri) - Feel free to reach out on LinkedIn.
*    [PowerShell Tools](https://www.domruggeri.com) - I run a PowerShell blog, writing tools and tutorials.

* * *

### Header 3

```powershell
#PowerShell Syntax
function Help {
  [CmdletBinding()]
    Param(
      [Parameter(ValueFromPipelineByPropertyName=$true,Position=0)]
      [Alias("DistinguishedName")]
	    [string]$Domain,

      [Parameter(Mandatory=$false,Position=1)]
        [string]$RootOU
    )
  $source = Get-ChildItem -Path "C:\Users"
}
```
### Education

| Name      |   Diploma     |   Year   |
|:----------|:--------------|:---------|
| Waukesha County Technical College | Associates Degree - IT Network Specialist | 2016     |
| MFHS      | High School   | 2011     |


### There's a horizontal rule below this.

* * *
