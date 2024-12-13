Windows Fundamentals:
Microsoft first introduced the Windows operating system on November 20, 1985.
Windows Server 2008 and 2012 reached end of life for security updates on January 14, 2020.
|Operating System Names               |	Version Number |
|-------------------------------------|----------------|
|Windows NT 4	                        | 4.0            |
|Windows 2000	                        | 5.0            |
|Windows XP	                          | 5.1            |
|Windows Server 2003, 2003 R2	        | 5.2            |
|Windows Vista, Server 2008	          | 6.0            |
|Windows 7, Server 2008 R2            |	6.1            |
|Windows 8, Server 2012	              | 6.2            |
|Windows 8.1, Server 2012 R2	        | 6.3            |
|Windows 10, Server 2016, Server 2019	| 10.0           |

Use Get-WmiObject cmdlet - to find information about OS, and to start and stop services on local and remote computers. (More info: https://ss64.com/ps/get-wmiobject.html  &&  https://adamtheautomator.com/get-wmiobject/)
win32_OperatingSystem class - to find version and build number
Win32_Process class - to get a process listing 
Win32_Service class - to get a listing of services
Win32_Bios class - to get Basic Input/Output System (BIOS) information.
ComputerName parameter - to get information about remote computers

Assessing Windows:
------------------
1. Local Access Concepts
2. Remote Access Concepts:
   - Virtual Private Networks (VPN)
   - Secure Shell (SSH)
   - File Transfer Protocol (FTP)
   - Virtual Network Computing (VNC)
   - Windows Remote Management (or PowerShell Remoting) (WinRM)
   - Remote Desktop Protocol (RDP)
  
Remote Desktop Protocol:
-  uses a client/server architecture
-  RDP listens by default on logical port 3389
-  If we are connecting to a Windows target from a Windows host, we can use the built-in RDP client application called Remote Desktop Connection (mstsc.exe).
-  By default, remote access is not allowed on Windows operating systems, it must be allowed to connect
-  Other RDP Clients include Remmina and rdesktop
-  xfreerdp - to connect Windows target from Linux host. Benefits like Drive redirection
-  Syntax: xfreerdp /v:<targetIp> /u:htb-student /p:Password



