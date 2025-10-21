# Pre-Security-Notes
Notes and takeaways from TryHackMe Pre Security learning path

## Introduction to Cybersecurity 
- CIA Traid
  - Confidentiality = keep data hidden
  - Integrity = keep data accurate, unaltered, unbiased
  - Availability = keep resources accesible to only authorized users

- Common Roles Within Cybersecurity
  - SOC analyst
  - Penetration Tester
  - Incident Responder
  - Security Engineer
    
- High- level Attack Types
  - Phising
  - Malware
  - DDoS
  - Insider Threats
 
## Networking Fundamentals 
- IP adresses
  - Unique device identifier (IPv4 vs IPv6)
    
- Port and Protocols
  - TCP -> connection- oriented
  - UDP -> connectionless
  - Common ports = 22(SSH), 80 (HTTP), 443 (HTTPS), 25 (SMTP)
 
- OSI Model (has 7 layes)
  - Application
  - Presentation
  - Session
  - Transport
  - Network
  - Data Link
  - Physical
 
-DNS -> resolves domain names = IPs 

- Routing and Packets
  - Data that is broken into packets and forwarded by routers/ switches
 
## How the Web Works 
- Client- Server Model
  - Browser sends requests, and the server sends back repsonses

- HTTP methods
  - common: GET (retrieve data), POST (send data), PUT, DELETE

- Examples of Status Code
  - 200 OK
  - 404 Not Found
  - 500 Server Error
 
- Cookies and Sessions
  - used to maintain user state, ex. keeping user logged in
    
- Structure of URL
  - protocol://domain/path?query#fragment

 ## Linux Fundamentals 
- Navigate: pwd, ls, cd, mkdir, touch, rm, cp, mv
- Permissions: ls -l to to view rwx, and modify with chomd or chown
- File Tools: cat, less, head, tail, grep
- Processes: whoami, id, ps, top, kill
- Networking Basics: ifconfig/ ip, ping, netstat, ss, curl, wget
- SSH: ssh user@ip = remote acces
- Scripting: can automate tasks with Bash scripts

## Windows Fundamentals 
- Key Directories for file system: C:\Users, C:\Windows,Program Files
- Powershell = more versatile for scripting
- Commands: ipconfig, ping, netstat
- Core Tools: Task Manager, Event Viewer,Services, Registry Editor
- Standard vs. admin users are managed through UAC

## Security Concepts 
- Authentication: verifying identity
- Authorization: granting permission
- Encryption
  - Symmetric = same key used for encryption and decryption (AES)
  - Asymmetric = public/ private key pairs
- Hashing
  - One way process for integrity and password storage
- Common Attacks
  - brute force, phising, SQL injection, privilege principle
- Cyber Hygiene
  - Strong passwords, regular patching, consistent backup
 
## Tools and Practice Labs 
- Gained Hands on Skills:
    - navigating and editing files in Linux terminal
    - using curl/ wget and woking with HTTP requests
    - running basic nmap scans to identify open ports
    - performing simple encryption/ decryption tasks
    - analyzing IPs, domains, and basic system logs
    - introduced tools: ping, curl, netstat, nmap, ssh
 
## Easy Go To Commands 
- Navigation: pwd, ls -l, cd dir/
- View Files: cat file, less file, head -n 20 file, tail -f file
- Search: grep "text" filename
- Permission: chmod 755 file, chown user: group file
- Network: ifconfig/ ip a, ping 8.8.8.8, curl http://example.com
- SSH: ssh user@host
- Windows: ipconfig, tasklist, Get-Process

## Reflection 
I completed the TryHackMe Pre-Security learning path to build a strong, practical foundation in cybersecurity. The rooms introduced key concepts in networking (IP addressing, ports, TCP/UDP), web technologies (HTTP methods, status codes, cookies, sessions), and core operating system skills in both Linux and Windows environments (file operations, permissions, SSH, PowerShell basics). Through interactive labs, I practiced hands-on commands (ls, grep, curl, ssh), explored essential tools (nmap, netstat), and developed a solid understanding of key security concepts such as encryption, hashing, authentication, and common attack methods. I applied these skills directly in my project by integrating AES encryption, user authentication, and secure file storage. My next steps are to strengthen my Linux scripting knowledge, implement password hashing, and explore containerized environments for secure testing.

