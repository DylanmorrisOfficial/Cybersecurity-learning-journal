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

