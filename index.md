---
layout: default
---
## whoami
My name is Dom Ruggeri. I'm a System Administrator specializing in PowerShell development, scripting, and automation. I work regularly with Windows Server, VMware, Hyper-V, Office 365, Azure, and Active Directory. I have a background in networking, and server infrastructure.

### 
Check out my [Upwork](https://www.upwork.com/o/profiles/users/_~01b0dddb831cc7bb38/) profile, or visit [my website](https://www.domruggeri.com)

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

* * *

## Quote
> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

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
#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
