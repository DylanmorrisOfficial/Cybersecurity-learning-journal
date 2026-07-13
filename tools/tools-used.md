# Tools Used

## Linux Terminal

Purpose:
System administration and navigation.

### Commands Used

#### Navigation

- pwd = Print working directory
- ls -al = List files including hidden files
- cd = Change directory

#### File Management

- find <starting_point> -name <filename> = Find a file
- mkdir = Create a directory
- cat = Display file contents
- nano = Edit text files

#### System Information

- whoami = Display current user
- uname -a = Display kernel and OS information
- df -h = Display disk usage

#### Networking & Utilities

- wget = Download files from the web

#### Process Management

- kill = Terminate a process

### Shell Scripting

Purpose:
Automate Linux administration and repetitive tasks.

Concepts Practiced:
- Variables
- User input
- Conditional statements (if/else)
- Loops
- Executing commands within scripts
- Scheduling scripts with cron

## Windows Command Prompt

Purpose:
Basic networking and system administration tasks.

### Commands Used

#### File Management

- dir /a = List hidden files
- dir /s <filename> = Search for files
- type <filename> = Display file contents

#### System Information

- hostname = Display computer name
- systeminfo = Display system information

#### Networking

- ipconfig = Display network configuration

## PowerShell

Purpose:
Windows automation and system administration.

### Commands Used

#### Navigation

- Get-Location = Show current location
- Set-Location = Change directory
- Get-ChildItem = List files and folders

#### Help & Discovery

- Get-Help = Display command help
- Get-Command = List available commands

#### System Information

- Get-Process = Display running processes
- Get-Service = Display services
- Get-Date = Display current date and time

#### Objects & Output

- Select-Object = Select specific properties
- Sort-Object = Sort output
- Where-Object = Filter output
- Measure-Object = Count or measure data

## Wireshark

Purpose:
Capture and analyse network traffic.

Features Practiced:
- Packet capture
- Display filters
- Packet colouring
- Find Packet
- Follow TCP/UDP/HTTP streams
- Export Objects
- Packet comments
- Example Display Filters
- Protocol filters

## Tcpdump

Purpose:
Capture and analyse network traffic from the Linux command line.

### Commands Used

sudo tcpdump = Start packet capture
sudo tcpdump host <host> -w <file>.pcap = Capture traffic from a specific host and save it
src port <port> and dst port <port> = Filter traffic by source and destination ports

## Nmap

Purpose:
Network discovery and port scanning.

### Commands Used

nmap -sL = List scan
Basic host discovery
Basic network scanning

## John the Ripper

Purpose:
Password auditing and hash cracking.

### Commands Used

john = Start password cracking against supported hash files

Concepts Practiced:
- Password hashes
- Dictionary attacks
- Basic password recovery

## Metasploit

Purpose:
Penetration testing framework used to discover, exploit and validate vulnerabilities.

### Commands Used

- msfconsole = Launch the Metasploit Framework
- search = Search for available modules
- use <module> = Select a module
- show options = Display required module options
- set <option> <value> = Set a module option
- setg <option> <value> = Set a global option
- info = Display information about a module
- run = Execute the selected module
- exploit = Launch an exploit
- back = Exit the current module
- sessions = List active sessions
- workspace = Manage project workspaces

## Meterpreter

Purpose:
Interact with compromised systems after successful exploitation.

### Commands Used

#### Navigation

- pwd = Print working directory
- ls = List files and directories
- cd = Change directory

#### File Management

- cat = Display file contents
- search = Search for files
- upload = Upload files
- download = Download files

#### System Information

- sysinfo = Display operating system information
- getuid = Display current user
- ps = List running processes
- shell = Open a command shell

## Burp Suite

Purpose:
Intercept, inspect and modify HTTP requests during web application testing.

### Features Practiced

- Proxy
- HTTP request interception
- HTTP history
- Request modification
- Repeater
- Web application traffic analysis

## SQL

Purpose:
Query and manage relational databases.

### Commands Used

- SELECT = Retrieve data from a table
- FROM = Specify the table to query
- WHERE = Filter query results
- ORDER BY = Sort query results