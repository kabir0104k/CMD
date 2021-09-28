# CMD


## Basic Commands 

1. > cd cd/ cd..(changing Directory)
2. > mkdir/md(Creating Folder)
3. > type nul>abc.txt/jpg/zip/mp3/mp4 (Exporting Any Extension File)
4. > rmdir/rd(Delete Folder)
5. > dir/ad(Only Folders)
6. > dir/a-d(Only Files)
7. > cls(Clear Screen)
8. > xcopy{Name With Extension} "Folder Name" (Copy Single File)
9. > xcopy{(*).Only Extension} "Folder Name" (Copy All File)
10. > Move{Name With Extension} "Folder Name" (Move Single File)
11. > Move{(*).Only Extension} "Folder Name" (Move All File)
12. > cd  Move abc.txt "C:\users\KABIR\Desktop (Move From Folder)
13. > del (.Extension)
14. > del (*.Extension)

### Tasks & Services

15. > ren abc.txt = ABC.txt (Rename)
16. > tasklist (Show All Running Task)
17. > taskkill /pid Console No. (To Kill Task)
18. > net start (For Starting Services)
19. > net stop/start "Target" (For Stopping Services)
20. > driverquery(Installed Driver List)
21. > netsh advfirewall set all state off(Firewall Off)
## WMIC Commands
22. > wmic cpu (CPU Information)
23. > wmic bios get serialnumber (BIOS Serial Number)
24 .> wmic nic get macaddress/getmac (For Mac Address)
25. > wmic partition get name,size,type (Info Of HDD Partitions)
26. > wmic process list brief(Task Process)
27. > wmic process where="abc.extension" call terminate (Terminate Task)
## System Info
28. > vol D:(Serial No. Of HDD Partition)
29. > winver (For Windows Version)
30. > chkdsk (Health Status Of HDD
31. > systeminfo (System Info)
## User Management
32. > net user "Name" "Pass" /add (For Adding User)
33. > net user "Name" /del (For Deleting User)
34. > net user "Name" *(Bypass Password)
## Best Utility
35. > copy con  Name.txt(Ctrl+Z)
36. > echo ________  > Name.txt (Exporting Written Text File)
37. > cipher /e (For Encrypting Files)
38. > cipher /d (For Decrypting Files)
39. > attrib +h +r +s  abc.Extension (Hide All File)
40. > attrib -h -r -s  abc.Extension (Show All File)
## Drive Operations
41. > label D: (For Giv ing Name To Drive)
42. > Diskpart>list disk>select disk 2>clean>create partition primary>
43. > select partition 2>format quick>active>assign(For Bootable Pen Drive)
## Network Shell
44. > netsh wlan show profiles (For Connected Wifi Networks)
45. > netsh wlan show profile name=KABIR key clear (For Wifi Pass)
## Basic Network Essential
46. > hostname(For Getting Computer Name)
47. > ipconfig (For Getting Ip Address)
48. > ping 127.0.0.1 (For Checking Connection)
49. > tracert www.google.com (For Tracing Route Towards Destination)
50. > netstat -e (Getting Send Receive Data Info)
51. > nslookup www.google.com (For Converting Domain Into Ip)
## Interesting Commands
52. > color ? (Change Terminal Colour)
53. > title "Name" (Change Terminal Name)
54. > mode 30,50,90 (Terminal Resizing)
55. > tree (D: Drive All Folder/Files Details)
56. > doskey/history (Cmd Current History)
57. > date (Current Date)
58. > time (Current Time)
59. > shutdown -s -t 05 (Shutdown Pc)
60. > restart  -r -t 05 (Restart Pc)
