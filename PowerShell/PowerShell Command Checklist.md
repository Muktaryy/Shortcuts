# PowerShell Command Checklist

A practical checklist to learn and master PowerShell, from basic navigation to automation, development, and advanced Windows administration.

## 01. Navigation

* [ ] `Get-Location` — Display the current working directory
* [ ] `Get-ChildItem` — List files and directories
* [ ] `Set-Location` — Change the current directory
* [ ] `Clear-Host` — Clear the terminal screen
* [ ] `tree` — Display directories in a tree structure
* [ ] `Get-Command` — Find available commands and executables

## 02. Files and Folders

* [ ] `New-Item` — Create a file or directory
* [ ] `Copy-Item` — Copy files and directories
* [ ] `Move-Item` — Move files and directories
* [ ] `Rename-Item` — Rename files and directories
* [ ] `Remove-Item` — Delete files and directories
* [ ] `New-Item -ItemType Directory` — Create a directory explicitly
* [ ] `Test-Path` — Check whether a path exists
* [ ] `Get-Item` — Get an item at a specified path

## 03. Read and Edit Files

* [ ] `Get-Content` — Read file contents
* [ ] `Set-Content` — Replace file contents
* [ ] `Add-Content` — Append content to a file
* [ ] `Select-String` — Search text using patterns
* [ ] `Get-Content -Tail 20` — Display the last 20 lines of a file
* [ ] `notepad` — Open the Notepad text editor

## 04. Search and Filter

* [ ] `Where-Object` — Filter objects using conditions
* [ ] `ForEach-Object` — Process objects from a pipeline
* [ ] `Sort-Object` — Sort objects by property
* [ ] `Select-Object` — Select properties or limit output
* [ ] `Measure-Object` — Calculate counts, sums, averages, and more
* [ ] `Get-ChildItem -Recurse` — Search through nested directories
* [ ] `Get-ChildItem -Filter` — Filter items by a supported pattern

## 05. Processes and System

* [ ] `Get-Process` — List running processes
* [ ] `Start-Process` — Start a program or process
* [ ] `Stop-Process` — Stop a running process
* [ ] `Get-Service` — List and inspect Windows services
* [ ] `Get-ComputerInfo` — Display detailed computer information
* [ ] `Get-CimInstance` — Query system and hardware information
* [ ] `Get-Date` — Display the current date and time
* [ ] `hostname` — Display the computer name
* [ ] `whoami` — Display the current user identity
* [ ] `systeminfo` — Display detailed Windows system information

## 06. Networking

* [ ] `ipconfig` — Display IP configuration
* [ ] `ping` — Test network reachability
* [ ] `tracert` — Trace the network route to a destination
* [ ] `nslookup` — Query DNS information
* [ ] `netstat` — Display network connections and listening ports
* [ ] `Test-NetConnection` — Test connectivity to a host or port
* [ ] `Get-NetIPConfiguration` — Inspect network adapter configuration
* [ ] `curl.exe` — Transfer data using URLs
* [ ] `Invoke-WebRequest` — Send web requests and retrieve responses
* [ ] `ssh` — Connect to remote systems securely
* [ ] `scp` — Copy files over SSH

## 07. Software and Packages

* [ ] `winget search` — Search for available software packages
* [ ] `winget install` — Install a software package
* [ ] `winget upgrade` — Upgrade installed software
* [ ] `winget list` — List installed applications
* [ ] `winget uninstall` — Uninstall a software package
* [ ] `Get-AppxPackage` — Inspect installed AppX/MSIX packages

## 08. Permissions and Security

* [ ] `Get-Acl` — Inspect access control permissions
* [ ] `Set-Acl` — Apply an access control list
* [ ] `icacls` — Display or modify file and directory permissions
* [ ] `Get-ExecutionPolicy` — Check PowerShell script execution policies
* [ ] `Set-ExecutionPolicy` — Configure PowerShell execution policies
* [ ] `Get-LocalUser` — List local user accounts
* [ ] `Get-LocalGroup` — List local groups

## 09. Environment and Shell

* [ ] `Get-Help` — Read command documentation
* [ ] `Get-History` — Display commands entered in the current session
* [ ] `Get-Alias` — List command aliases
* [ ] `Set-Alias` — Create a command alias
* [ ] `$env:PATH` — Display executable search paths
* [ ] `$env:USERNAME` — Display the current username
* [ ] `$env:USERPROFILE` — Display the current user's profile path
* [ ] `$PWD` — Access the current working directory
* [ ] `$HOME` — Access the user's home directory
* [ ] `exit` — Exit the current shell

## 10. Automation and Scripting

* [ ] `if / else` — Execute code based on conditions
* [ ] `foreach` — Iterate through a collection
* [ ] `for` — Repeat code using a counter
* [ ] `while` — Repeat code while a condition is true
* [ ] `function` — Define reusable commands
* [ ] `param` — Declare script or function parameters
* [ ] `try / catch` — Handle terminating errors
* [ ] `Read-Host` — Read input from the user
* [ ] `Write-Output` — Write objects to the output pipeline
* [ ] `Start-Sleep` — Pause script execution

## 11. Developer Workflow

* [ ] `git` — Track changes with version control
* [ ] `code .` — Open the current directory in Visual Studio Code
* [ ] `python` — Run Python programs
* [ ] `py` — Use the Windows Python launcher
* [ ] `py -m venv .venv` — Create a Python virtual environment
* [ ] `pip` — Install and manage Python packages
* [ ] `npm` — Manage Node.js packages
* [ ] `npx` — Execute package binaries
* [ ] `node` — Run JavaScript with Node.js
* [ ] `where.exe git` — Locate Git executables on the system

## 12. Advanced Administration

* [ ] `Get-WinEvent` — Query Windows event logs
* [ ] `Get-ScheduledTask` — Inspect scheduled tasks
* [ ] `Register-ScheduledTask` — Register a scheduled task
* [ ] `Get-Disk` — Inspect physical and virtual disks
* [ ] `Get-Volume` — Inspect storage volumes
* [ ] `Get-Partition` — Inspect disk partitions
* [ ] `Get-ChildItem Env:` — List environment variables
* [ ] `Get-FileHash` — Calculate a file's cryptographic hash
* [ ] `Compress-Archive` — Create ZIP archives
* [ ] `Expand-Archive` — Extract ZIP archives

---

## Progress Tracker

* **Total checklist items:** 97
* **Completed:** 0
* **Goal:** Learn each command, understand its options, and practice it with real examples.

## Learning Resources

* [Official PowerShell Documentation](https://learn.microsoft.com/en-us/powershell/)
* [PowerShell Reference](https://learn.microsoft.com/en-us/powershell/module/)
* [PowerShell GitHub Repository](https://github.com/PowerShell/PowerShell)
* [Windows Command Reference](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/windows-commands)
* [Windows Package Manager Documentation](https://learn.microsoft.com/en-us/windows/package-manager/winget/)

---

## Practice Tips

* Practice in a test directory or virtual machine.
* Use `Get-Help Command-Name` to learn command options.
* Use `Get-Command *keyword*` to discover related commands.
* Be careful with `Remove-Item`, `Stop-Process`, `Set-Acl`, and disk-management commands.
* Some commands require administrator privileges, additional modules, or separately installed tools.
* Prefer PowerShell cmdlets when appropriate, but learn native Windows commands too.
* Check off each item only after you've practiced it.

⭐ **Keep learning, keep automating, and build your PowerShell skills one command at a time!**
