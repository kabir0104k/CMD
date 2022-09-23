# CMD

## Basic Commands 
```bash
> cd cd/ cd..(changing Directory)
> mkdir/md(Creating Folder)
> type nul>abc.txt/jpg/zip/mp3/mp4 (Exporting Any Extension File)
> rmdir/rd(Delete Folder)
> dir/ad(Only Folders)
> dir/a-d(Only Files)
> cls(Clear Screen)
> xcopy{Name With Extension} "Folder Name" (Copy Single File)
> xcopy{(*).Only Extension} "Folder Name" (Copy All File)
> Move{Name With Extension} "Folder Name" (Move Single File)
> Move{(*).Only Extension} "Folder Name" (Move All File)
> cd  Move abc.txt "C:\users\KABIR\Desktop (Move From Folder)
> del (.Extension)
> del (*.Extension)
```

---------
### Tasks & Services
```bash
> ren abc.txt = ABC.txt (Rename)
> tasklist (Show All Running Task)
> taskkill /pid Console No. (To Kill Task)
> net start (For Starting Services)
> net stop/start "Target" (For Stopping Services)
> driverquery(Installed Driver List)
> netsh advfirewall set all state off(Firewall Off)
```

---------
## WMIC Commands
```bash
> wmic cpu (CPU Information)
> wmic bios get serialnumber (BIOS Serial Number)
> wmic nic get macaddress/getmac (For Mac Address)
> wmic partition get name,size,type (Info Of HDD Partitions)
> wmic process list brief (Task Process)
> wmic useraccount get name (All User Details)
> wmic useraccount get name,sid (All User SID Privilege)
> wmic process where="abc.extension" call terminate (Terminate Task)
```

---------
## System Info
```bash
> vol D:(Serial No. Of HDD Partition)
> winver (For Windows Version)
> chkdsk (Health Status Of HDD)
> systeminfo (System Info)
```

---------
## User Management
```bash
> net user "Name" "Pass" /add (For Adding User)
> net user "Name" /del (For Deleting User)
> net user "Name" *(Bypass Password)
```

---------
## Best Utility
```bash
> copy con  Name.txt(Ctrl+Z)
> echo ________  > Name.txt (Exporting Written Text File)
> cipher /e (For Encrypting Files)
> cipher /d (For Decrypting Files)
> attrib +h +r +s  abc.Extension (Hide All File)
> attrib -h -r -s  abc.Extension (Show All File)
```

---------
## Drive Operations
```bash
> label D: (For Giv ing Name To Drive)
> Diskpart>list disk>select disk 2>clean>create partition primary>
> select partition 2>format quick>active>assign(For Bootable Pen Drive)
```

---------
## Network Shell
```bash
> netsh wlan show profiles (For Connected Wifi Networks)
> netsh wlan show profile name=KABIR key clear (For Wifi Pass)
```

---------
## Basic Network Essential
```bash
> hostname(For Getting Computer Name)
> ipconfig (For Getting Ip Address)
> ping 127.0.0.1 (For Checking Connection)
> tracert www.google.com (For Tracing Route Towards Destination)
> netstat -e (Getting Send Receive Data Info)
> nslookup www.google.com (For Converting Domain Into Ip)
```

---------
## Interesting Commands
```bash
> color ? (Change Terminal Colour)
> title "Name" (Change Terminal Name)
> mode 30,50,90 (Terminal Resizing)
> tree (D: Drive All Folder/Files Details)
> doskey/history (Cmd Current History)
> date (Current Date)
> time (Current Time)
> shutdown -s -t 05 (Shutdown Pc)
> restart  -r -t 05 (Restart Pc)
```
---------



#### Author / Creator : [`KABIR`](https://github.com/kabir0104k)
