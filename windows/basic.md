## Sistem info

`Get-WmiObject -Class Win32_OperatingSystem | select Version,BuildNumber`

`Win32_Process` to get a process listing, `Win32_Service` to get a listing of services 'Win32_Bios' to get Basic Input/Output System (BIOS) information.
More info https://ss64.com/ps/get-wmiobject.html and https://adamtheautomator.com/get-wmiobject/

## Remote conections

    Virtual Private Networks (VPN)
    Secure Shell (SSH)
    File Transfer Protocol (FTP)
    Virtual Network Computing (VNC)
    Windows Remote Management (or PowerShell Remoting) (WinRM)
    Remote Desktop Protocol (RDP)

RDP listens by default on logical port 3389 (mstsc.exe https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/mstsc)
From Linux systems, we can use https://linux.die.net/man/1/xfreerdp to acces by rdp
