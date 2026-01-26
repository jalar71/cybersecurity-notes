#  Power in PowerShell — Notes From My TryHackMe Journey

I recently finished the Command Line Essentials room on TryHackMe for PowerShell and honestly I couldn’t fathom how powerful this tool really is.

It’s easily one of the most useful scripting environments anyone in IT or cybersecurity can learn to make their daily menial work easier. 

---

## Why Microsoft developed PowerShell?

For years Command Prompt was the default Windows shell. But as Windows started being used in larger more complex enterprise environments its limitations became obvious.

Microsoft felt the need to develop a more powerful command language to address that hence PowerShell was born.

Unlike CMD which mostly works with plain text, PowerShell works with objects and that puts the **POWER** in PowerShell.

---

## What are Objects?

To really understand PowerShell we need to understand what an **object** is.

In programming, an object represents something with:

- **Properties** → characteristics  
- **Methods** → actions  
  
TryHackMe did a wonderful job explaining the concept using an example of a car:

- Properties: `Color`, `Model`, `FuelLevel`
- Methods: `Drive()`, `HonkHorn()`, `Refuel()`

In Powershell Objects are just like the car, It is a *thing* that comes with:

→ Facts about it(properties)

→ Things it can do(methods)

---

##  Basic Syntax → Verb-Noun

PowerShell commands are called **cmdlets** (pronounced *command-lets*).
Example of the syntax: 
- `Get-Content` → retrieves (gets) file contents  
- `Console.Set-Location` → changes (sets) the current directory  


---


### Basic Commands

Lists all cmdlets, functions, scripts, and aliases in your session:

```powershell
Get-Command
