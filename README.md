#### Windows Update

http://update.microsoft.com/windowsupdate

#### Microsof Update

http://update.microsoft.com/microsoftupdate

#### WHDownloader

![WHDownloader](https://i.imgur.com/tVDxmm3.png)

[http://forums.mydigitallife.info/forums/56-WHDownloader](http://forums.mydigitallife.info/forums/56-WHDownloader)

#### Windows Update MiniTool

![Windows Update MiniTool](https://i.imgur.com/yE528o1.png)

[http://forum.ru-board.com/topic.cgi?forum=5&topic=48142#2](http://forum.ru-board.com/topic.cgi?forum=5&topic=48142#2)

#### 清理WinSxS

```
dism.exe /online /cleanup-image /analyzecomponentstore
```

![](https://i.imgur.com/zhuE6Z2.png)

```
dism.exe /online /cleanup-image /startcomponentcleanup /resetbase
```

![](https://i.imgur.com/Z80vJlV.png)

#### Windows Update PowerShell Module

[https://gallery.technet.microsoft.com/scriptcenter/2d191bcd-3308-4edd-9de2-88dff796b0bc](https://gallery.technet.microsoft.com/scriptcenter/2d191bcd-3308-4edd-9de2-88dff796b0bc)


#### RSS

[http://blogs.msdn.com/b/winsdk/rss.aspx](http://blogs.msdn.com/b/winsdk/rss.aspx)

#### Microsoft Hotfixes Full Description

[https://support.microsoft.com/en-us/kb/KBArticleNumber](https://support.microsoft.com/en-us/kb/KBArticleNumber)

#### Microsoft Hotfixes Download

[https://support.microsoft.com/en-us/hotfix/kbhotfix?kbnum=KBArticleNumber&kbln=en-us](https://support.microsoft.com/en-us/hotfix/kbhotfix?kbnum=KBArticleNumber&kbln=en-us)

#### Microsoft Hotfixes KBArticleNumber and Short Description

[http://blogs.msdn.com/b/winsdk/archive/2014/10/15/october-2014-hotfixes.aspx](http://blogs.msdn.com/b/winsdk/archive/2014/10/15/october-2014-hotfixes.aspx)

```
2873531 Checks that call the IsAlive and LooksAlive methods are not executed based on the resource default settings in Windows
2968741 Error 0x80070057 when SQL Server communicates to a web server using stored procedure in Windows 8 or Windows Server 2012
2979583 Additional thick line is printed on a page that has an Excel chart in Windows
2981330 WTSQuerySessionInformation API function always returns zero bytes for WTSIncomingBytes and WTSOutgoingBytes
2987849 Logon fails after you restrict client RPC to DC traffic in Windows Server 2012 R2 or Windows Server 2008 R2
2988609 You cannot print fax by using a fax modem in Windows
2991246 "Access is denied" error when you perform a backup or run "vssadmin list writers" on a cluster node in Windows Server 2012
2991247 SMB 3.0 Transparent Failover feature does not work after you disconnect a drive cable in Windows
2995054 "400 Bad Request" error when you send a message that contains a lowercase "get" to the Gateway
2995392 Stop error 0x000000D1 after you install the Hyper-V role in Windows Server 2012 R2
2996207 Network printers that use TCP/IP port cannot print after first document has printed in Windows
2996502 Sitka fonts cannot be printed correctly by using an XPS print driver in Windows
2996534 Rotated images in PowerPoint 2013 are printed incorrectly when you use XPS in Windows
2996807 Print jobs are intermittently processed slowly through Windows 8.1-based or Windows Server 2012 R2-based printer servers
2996808 Gray conversion of the RGB color is printed incorrectly through a PCL 6 version 4 driver in Windows
2996883 DFSR stops replication after an unexpected shutdown in a Windows 8.1 or Windows Server 2012 R2 environment
2998553 Too much UAL diagnostic information is logged in application event log in Windows Server 2012 R2 or Windows Server 2012
2998556 Windows Server 2012-based cluster freezes after you enable the data deduplication feature
2998984 You cannot dock MicroStation toolbars after you install update 2973201 in Windows
2999237 An application connection fails through a dual-use socket that is redirected by using a WFP callout driver
3000064 The computer restarts unexpectedly after you install security update MS14-045 on Windows 7 or Windows Server 2008 R2
3000406 Windows Journal crashes when you import a Word document that contains pictures Windows 7 or Windows Server 2008 R2
3000435 Virtual Machine Management Service memory leak triggers Windows Server 2008 R2 crash
Bonus Hotfix!
2732597 0x80070091 error when you drag and drop a folder in a WebDAV shared folder in Windows
UPDATE: Yesterday I was kidding about the bonus hotfix. But it turns out 5 hotfixes were missing from the above list. Here they are:
2957486 Ls command takes a long time to list shared files in two windows on a Windows Server 2008 R2-based NFS server 
2993228 0x00000093 Stop error when you enable the BranchCache functionality on a file server in Windows 8 or Windows Server 2012
2995055 Error 0x80070001 when you try to optimize a CSV volume in Windows Server 2012 R2
2995635 "DIR_Error" occurs when you try to obtain the properties of the RODC in a different domain
2998097 "Specified account does not exist" error message when domain users try to change their password in UPN format in a different domain
```

[http://blogs.msdn.com/b/winsdk/archive/2014/11/19/windows-hotfixes-for-november-2014.aspx](http://blogs.msdn.com/b/winsdk/archive/2014/11/19/windows-hotfixes-for-november-2014.aspx)

```
2884176 Large backlogs on Windows Server 2008 R2 SP1-based or Windows Server 2012 R2-based DFSR servers
2912095 Lightweight Directory Services auditing Event ID 4662 is missing user information
2957486 Ls command takes a long time to list shared files in two windows on a Windows-based NFS server
2968741 Error 0x80070057 when SQL Server communicates to a web server using stored procedure in Windows 8 or Windows Server 2012
2979127 You can't perform token-based activation in Windows 8.1
2979933 Sharp increase in CPU usage occurs when a folder is renamed in Windows
2983628 File Server Resource Manager Quota filters are not decremented correctly in Windows Server 2008 SP2
2990941 Update to support NVM Express by using native drivers in Windows 7 or Windows Server 2008 R2
2995478 Wmiprvse.exe memory leak when a program queries disk or partition storage information in Windows Server 2012
2996205 ifAdminStatus variable of 0 in NIC Teaming interface in Windows Server 2012 or Windows Server 2012 R2
2996802 TRIM and UNMAP activities for thin provisioning on one volume block all activities on other volumes
2996928 Backup task fails with a time-out error in Windows Server 2012 or Windows Server 2008 R2
2998082 gMSA-based services can't log on after a password change in a Windows Server 2012 R2 domain
2998530 Disc is ejected unexpectedly when an application is writing to a CD or DVD drive in Windows 7 or Windows Server 2008 R2
2999802 Solid lines instead of dotted lines are printed in Windows 8.1
3000123 iSCSI SAN server that's running Windows Server 2012 R2 restarts unexpectedly on a high-speed network
3001232 Print jobs fail in Windows 7 and Windows Server 2008 R2
3001264 "0x80073B92" error when you perform a Bare Metal Recovery on a Windows 7 or Windows Server 2008 R2-based UEFI computer 
3001265 "Access Denied" error and all objects and child OUs under OU are deleted in GPMC in Windows 7 or Windows Server 2008 R2
3001522 Error when you call an Excel application object on Windows 8 or Windows Server 2012
3001526 The input of Chinese (Traditional) Quick characters is very slow in Windows 7 and Windows Server 2008 R2
3002286 Delay in accessing a file server when a Windows 7-based computer connects to the file server
3002288 DFSR service freezes when it calls a method on a Windows-based server
3002297 The SMB Redirector may hang when the SMB protocol is used in Windows 7 SP1 or Windows 8.1
3002301 A memory leak in nonpaged pool memory occurs when a domain controller is running Windows Server 2008 R2
3002650 Virtual machine live migration is unsuccessful on a server that is running Windows Server 2008 R2
3002858 "0x0000009F" Stop error when you put the computer in sleep mode or hibernation in Windows 8.1 or Windows Server 2012 R2
3002859 Miracast display resolution changes after you shut down and then restart a Windows 8.1-based computer
3002869 Graphics adapter crashes or timing data is incorrect when you try to analyze the GPU performance of an application
3003385 "Access Violation" error when AzMan processes business rules in Windows 7 SP1 or Windows Server 2008 R2 SP1
3003689 Exit code improvements for Task Scheduler event log in Windows 8 and Windows Server 2012
3004070 VSS task schedule is not created as you configure if shadow copy storage is on another share disk in Windows Server 2012
3004098 Memory leak occurs when you create or delete CSV snapshots by using a VSS hardware provider in Windows Server 2012
3004182 Memory leak when transiting web pages that contain the Windows Media Player ActiveX control in Windows
3004383 Outlook clients are disconnected when the RPC Client Access service spikes to 100 percent CPU usage
3004543 Windows 7 or Windows Server 2008 R2 cannot renew IP address from a Windows Server 2012 R2-based DHCP server
3005781 Error occurs when you print an A3 size document in Windows 8.1 or Windows 7
3006207 Windows Journal crashes when you import a Word document that contains pictures in Windows 8 or Windows Server 2012
3007006 Memory usage of the Msdtc.exe process increases on Windows 7 or Windows Server 2008 R2
3007196 DSCP value is missing in the SYN-ACK packet during a TCP connection in Windows 7 SP1 or Windows Server 2008 R2 SP1
3007593 Stop error occurs when an SIS volume on a Windows Server 2008 R2-based server is accessed by Mac OS X clients
3008193 "Server Failure" error when you query some domain on a Windows Server 2008 R2-based DNS server
3008288 Handle leak occurs when you execute WMI queries in Windows Server 2008 SP2
```

[http://blogs.msdn.com/b/winsdk/archive/2014/12/10/hotfix-list-for-december-2015.aspx](http://blogs.msdn.com/b/winsdk/archive/2014/12/10/hotfix-list-for-december-2015.aspx)

```
2500511 Windows crashes when you try to run the "sysprep /generalize" command after you run the "mountvol /n" command in Windows 7 or in Windows Server 2008 R2
2535094 Server stops responding when you lock or unlock files on a network by using the SMB2 protocol in Windows
2896881 Long logon time when you use the AddPrinterConnection VBScript command to map printers for users during logon process in Windows
2914743 You receive Stop error 0xD1 in Windows Server 2012 R2 or Windows 8
2957699 Confusing message from Work Folders in Action Center when you change or disconnect the network in Windows 8.1
2957701 The FSRM UI stops responding when there are many storage reports to monitor on a server that is running Windows Server 2012 R2
2961042 Printer server goes offline when you wake up the computer at another network location in Windows
2965917 A computer freezes during startup after filter drivers are installed in Windows 7 or Windows Server 2008 R2
2974005 Stop error 0x0000007E in Windows 7 or Windows Server 2008 R2
2978137 Update lets OEMs prevent specific non-video AVStream devices from being used on Windows 8.1 devices
2993229 Copy-on-write method for a snapshot CSV volume doesn't occur for a two-node cluster in Windows Server 2012 R2
2999802 Solid lines instead of dotted lines are printed in Windows
3000461 A wireless, high-quality print job to a WSD port is automatically canceled on a Windows 8.1 computer
3001267 You cannot connect to a network printer by using the CNAME for the print server in a Windows Server 2012 R2 DNS environment
3003385 "Access Violation" error when AzMan processes business rules in Windows
3006112 Surrogate pair characters in fallback font are displayed as squares in Windows 7 or Windows Server 2008 R2
3006114 Update to support vertical forms of punctuation for SimSun font in Windows 8 or Windows Server 2012
3006139 Chinese IME toggle hotkey cannot be disabled in Windows 7 or Windows Server 2008 R2
3007054 PIN-protected printing option always shows when you print a document within a Windows Store application in Windows
3008558 Servers restart unexpectedly when the Lsass.exe process crashes in Windows Server 2008 R2 or Windows 7
3009016 Network adapter is displayed on the taskbar and in the VAN UI in Windows 8.1
3009197 "0x0000009F" Stop errors when you restart the computer in Windows 7
3009350 Excel freezes when you import an .xml file in Windows 7 or Windows Server 2008 R2
3009621 VMware virtual machines freeze when they shut down or restart in Windows 7 or Windows Server 2008 R2
3009736 MP4 file cannot be played on a non-Windows-based device if it was created in Windows 7 or Windows Server 2008 R2
3012325 Windows APN database entries update for DIGI, Vodafone, and Telekom mobile operators in Windows 8.1 and Windows 8
3012696 An IPP printer stops responding after you cancel a print job from PowerPoint in Windows 7 or Windows Server 2008 R2
3012714 "0x80070016 ERROR_BAD_COMMAND" error when Hyper-V replication stops in Windows Server 2012
3012982 Update to enable Schannel crypto APIs to be called from a DPC-level driver in Windows 8.1 and Windows Server 2012 R2
3013102 "Command not found" error when you run a command in the C shell for SUA in Windows 7 or Windows Server 2008 R2
3013108 RDS License Manager shows no issued free or temporary client access licenses in Windows Server 2012 R2
3013125 "Unable to connect to the computer" error when you try to manage iSCSI virtual disks in Windows Server 2012
3013486 Windows Server 2012 R2-based cluster freezes after you enable data deduplication
3013488 Long wait to reset WSUS server when you import CSA files in Windows Server 2012 R2 or Windows Server 2012
3014300 CredUIPromptForWindowsCredentials API does not select the smart card logon certificate from the pvInAuthBuffer parameter
3014591 File duration is incorrect in a file that is created by Media Foundation MPEG-4 file sink in Windows
3014793 Stop error 0xC2, 0x50, or 0xCC after you restart a computer that's running Windows 7 or Windows Server 2008 R2
3014795 A third-party switch extension to the Microsoft VM switch cannot be disabled on Windows Server 2012 R2
3015999 Stop Error 0x27 occurs when you try to move a folder on a network share from one place to another on Windows 7 SP1 or Windows Server 2008 R2 SP1
3016350 Windows Photo Viewer cannot print single pages or custom page ranges on Windows 7 SP1 or Windows Server 2008 R2 SP1
3016375 You get a restricted IP address after the wireless interface is re-enabled in Windows 7 or Windows Server 2008 R2
```

[http://blogs.msdn.com/b/winsdk/archive/2015/01/14/hotfix-list-for-january-2015-short.aspx](http://blogs.msdn.com/b/winsdk/archive/2015/01/14/hotfix-list-for-january-2015-short.aspx)

```
2877237 FIX: Stop error 0x00000133 occurs on a computer that is running Windows 8 or Windows Server 2012
3009980 Computer freezes when the cursor is focused to an edit box and you change the focus repeatedly in Windows
```

[http://blogs.msdn.com/b/winsdk/archive/2015/02/11/hotfixes-for-february-2015.aspx](http://blogs.msdn.com/b/winsdk/archive/2015/02/11/hotfixes-for-february-2015.aspx)

```
2616886 Group membership is emptied on a Windows Server 2008 R2-based or Windows Server 2008-based RODC
2972254 Hyper-V virtual machines cannot be connected to sometimes when TCP connections reconnect in Windows
3002286 Delay in accessing a file server when a Windows 7-based computer connects to the file server
3004544 You are repeatedly prompted for credentials when you access intranet sources by using certification-based SSO in Windows
3004545 You cannot access virtual machines that are hosted on Azure hosting services through a VPN connection in Windows
3005788 Printing preferences window appears behind a RemoteApp window in Windows 7 or Windows Server 2008 R2
3006137 Hotfix changes the currency symbol of Lithuania from the Lithuanian litas (Lt) to the euro (€) in Windows
3007058 "Print to file" feature does not work through a Windows-based printer server that uses a version 4 printer driver
3012660 "The update is not applicable to your computer" error when you install update 2853587 in Windows 7 SP1 with AD LDS
3013174 "No Computer Found" error on front panel of USB scanner when you scan documents in Windows 7 or Windows Server 2008 R2
3013808 "0x00000024" Stop error caused by the Ntfs.sys file in Windows Vista SP2 or Windows Server 2008 SP2
3014176 Windows does not change the client certificates in subsequent HTTP requests after the initial connection
3015354 Update of multimedia class device drivers fails after you upgrade Windows
3015693 "0x000000AB" Stop error in Windows Server 2012-based RDS server when you log off from a Remote Desktop session
3016331 Virtual machines restart unexpectedly when Resource Host Monitor is stopped in Windows Server 2008 R2
3018489 "No host bus adapter is present" error when querying SAS cable issues in Windows Server 2012
3018775 "STATUS_NONE_MAPPED" error returns by Windows Server 2012 R2 DC when resolving SIDs from SIDHistory of a migrated object
3018886 You are prompted for a username and password two times when you access Windows Server 2012 R2 AD FS server from intranet
3019224 "Not able to connect to printer" error when you try to connect to a printer on a computer that is running Windows 7 or Windows Server 2008 R2
3019272 It takes a long time to log on to a domain-joined computer that runs Windows 8.1 or Windows Server 2012 R2
3019274 L3 cache size is reported incorrectly from Windows Management Instrumentation interface in Windows
3019276 You cannot selectively restore files from a data deduplication backup in Windows Server 2012 R2 or Windows Server 2012
3019282 Print Spooler service crashes when you print documents on a network shared printer in Windows
3020396 Sysprep.exe process crashes when you use the SCVMM tool to create a VM template of a Windows Server 2012 image
3020398 Shared screen flashes when an attendee joins or leaves a multiparty session in an application in Windows 7
3020773 Time-out failures after initial deployment of Device Registration service in Windows Server 2012 R2
3020813 You are prompted for authentication when you run a web application in Windows Server 2012 R2 AD FS
3021052 Monitor that uses the WMI service stops working for the cluster service in Windows Server 2012
3021064 "0x0000003B" Stop error and losing remote session on remote server in Windows 7 or Windows Server 2008 R2
3021169 Computer freezes when updating network driver or installing network filter driver in Windows 7 or Windows Server 2008 R2
3022235 USB SD card reader loses capability to detect media change in Windows
3022332 "Windows has detected an IP address conflict" error in Windows Server 2012 R2 or Windows Server 2008 R2 NLB nodes
3022333 Hotfix to avoid a deadlock situation on a CSV file system volume on Windows Server 2012 R2
3022773 Dnscache service no longer sends update packets to the DNS server
3022780 DNS server does not respond with IP address to a CNAME query for a delegated zone in Windows Server 2008 R2
3023161 Remote session disconnects when you are connected to a server by remote desktop in Windows 7 or Windows Server 2008 R2
3023557 WSAEINVAL error when many applications make WCF calls to connect to web in Windows 7 SP1 or Windows Server 2008 R2 SP1
3023569 Windows Process Activation Service crashes with an access violation in Windows 7 SP1 or Windows Server 2008 R2 SP1
3023894 Cluster fixes for deadlock and resource time-out issues in Windows Server 2012 R2 Update 1
3024260 OK and Cancel buttons are missing from the Local Devices and Resources dialog box in the Norwegian language pack
3024331 "XACT_E_CONNECTION_DOWN" error on SQL Server instances after you restart MS DTC in Windows 8 or Windows server 2012
3024681 Program icons are missing from network tiles in the Windows Modern UI
3025078 You are not prompted for username again when you use an incorrect username to log on to Windows Server 2012 R2
3025080 Operation fails when you try to save an Office file through Web Application Proxy in Windows Server 2012 R2
3025087 Lsass.exe process and Windows Server 2012 R2-based domain controller crashes when the server runs under low memory
3025097 "Invalid device" error when you try to rename a file on a Network File System client that is running Windows 8.1 or Windows Server 2012 R2
3025101 "Not support" error when you click Open with Explorer on SharePoint in Windows 7 or Windows Server 2008 R2
3025426 RRAS phonebook and registry key go out of sync on an S2S VPN in Windows 8.1 or Windows Server 2012 R2
3026286 Internal sites cannot be accessed through VPN in Windows 7 SP1 or Windows Server 2008 SP1
3026679 Network interface IP address is not updated when you resume a computer from sleep in Windows 7 or Windows Server 2008 R2
3026738 RemoteApp window is too large or too small when you use RDP to run a RemoteApp application in Windows Server 2012 R2
3026771 "0x0000007E" Stop error after you perform a VSS backup job in Windows 7 or Windows Server 2008 R2
3026773 VSS snapshot disappears after system starts in Windows 7 or Windows Server 2008 R2
3027108 "0x0000003B" Stop error when you mount a virtual hard disk driver in Windows on a computer that has 4K sector disks
3027110 Hyper-V hosts freeze in black screen if cluster nodes shut down unexpectedly in Windows 8.1 or Windows Server 2012 R2
3027113 Can't save a dump file when the system crashes and the Round Robin MPIO policy is used in Windows Server 2012
3027115 Custom values for various MPIO timers in Windows Server 2012 R2 may not be honored
3027127 "Round Robin with Subset" load balancing policy is lost after computer restarts in Windows 7 or Windows Server 2008 R2
3027174 Insufficient MBCS file name support on the FTP client in Windows Server 2012 and Windows 8
3027577 "0x0000007F" Stop error when you run both data encryption and antivirus software in Windows 7 or Windows Server 2008 R2
3031417 Deduplication fixes for optimization job schedule and resiliency to hardware failures in Windows Server 2012 R2
3031420 "100060" time-out error when you drain VM roles for CAU during VM live migration on Windows Server 2012 R2 compute nodes
```

[http://blogs.msdn.com/b/winsdk/archive/2015/03/12/hotfix-releases-for-windows-march-2015.aspx](http://blogs.msdn.com/b/winsdk/archive/2015/03/12/hotfix-releases-for-windows-march-2015.aspx)

```
981538 You receive broken messages in the Ftp command output logs on a computer that is running Windows
2688074 An access violation occurs on a domain controller that is running Windows Server 2008 R2 or Windows Server 2008
2928562 Event 55 when you copy an encrypted folder to EFS shared folder in Windows
2970653 A SQL Server that is running in a Hyper-V virtual machine takes a long time to restore a database to a dynamic VHD
3003689 Exit code improvements for Task Scheduler event log in Windows 8 and Windows Server 2012
3004070 VSS task schedule is not created as you configure if shadow copy storage is on another share disk in Windows
3012644 Items disappear or are duplicated on All Programs menu after moving icons in Windows 7 or Windows Server 2008 R2
3014069 Performance regressing in Hyper-V guest system in Windows Server 2012 R2 or Windows 8.1
3014136 PowerShell transcript file doesn't contain the correct information in Windows Server 2012 R2
3014406 Startup delay occurs after you disable IPv6 in Windows
3014783 "RDS busy" or "The Group Policy Client failed logon" error when you log on to an application in Windows Server 2008 R2
3016407 Message Queueing resource takes long time during startup and failover in Windows Server 2012 R2 or Windows Server 2012
3018454 XPS printing fails if your preferred printer settings have decimal data in Windows
3020717 VMMS crashes when you perform live migration and request VM information at the same time in Windows Server 2012 R2
3021052 Monitor that uses the WMI service stops working for the cluster service in Windows
3021190 IME freezes for a while when you input text in Windows
3021946 Frozen application dialog box appears if you tap the screen after you select language during OOBE process in Windows
3022752 A custom authentication package causes an error on a computer that is running Windows 8.1
3022776 Update to add support for Generic Routing Encapsulation in Windows 8.1 and Windows Server 2012 R2
3023555 A short delay is experienced in IPsec connections if RSS feeds are enabled on a computer that is running Windows Server 2012 R2
3023869 Crash on Windows 8.1 or Windows Server 2012 R2 when a WPF driver calls the FwpsConstructIpHeaderForTransportPacket0 function
3024252 NBL tracking buffer is too small when you troubleshoot NBL issues in Window 8.1 or Windows Server 2012 R2
3025370 You cannot access server share in System Center 2012 R2 Configuration Manager in Windows
3027123 Premature events on Windows Server 2012 R2 when you run RRAS together with VPN static pools
3027174 Insufficient MBCS file name support on the FTP client in Windows
3027577 "0x0000007F" Stop error when you run both data encryption and antivirus software in Windows 7 or Windows Server 2008 R2
3029348 "0x00000133" Stop error on CHT or BYT platform computers that are running Windows 8.1 or Windows Server 2012 R2
3030039 "0xC000021B" error when you insert an NBL that contains multiple net buffers for IPv6 in Windows
3031085 "0x000000D5" Stop error on a ConfigMgr server that is running Windows Server 2008 R2 SP1
3031311 Duplicate SPNs cannot be detected in Windows 7 SP1 or Windows Server 2008 R2 SP1
3031436 Windows Store apps cannot be updated automatically when proxy service is used in Windows
3032331 "0x0000007E" Stop error on a multiple sockets server that is running Windows Server 2012 R2
3032590 "STATUS_TRUSTED_RELATIONSHIP_FAILURE" error when you log on to Office 365 from AD FS proxy in Windows
3033446 Wi-Fi connectivity issues or poor performance on CHT platform computers in Windows 8.1
3033917 AD FS cannot process SAML response in Windows Server 2012 R2
3033918 Disk resource does not come online in Windows Server 2012 R2 or Windows Server 2008 R2-based failover cluster
3033930 Hotfix increases the 64K limit on RIO buffers per process for Azure service in Windows
3035025 Hotfix for update password feature so that users are not required to use registered device in Windows Server 2012 R2
3035444 "0x000000F5" Stop error when data deduplication is enabled on Windows Server 2012
3035465 PowerShell 3.0 might not execute switch statements in Windows 8 or Windows Server 2012
3035899 DirectAccess clients cannot establish connections when you use an authenticated web proxy from extranet in Windows
3036150 Remote desktop users can see the printers of the other users in Windows 7 SP1 or Windows Server 2008 R2 SP1
3036155 Scanning application crashes upon close after you perform a scan in Windows
3036575 "0x000000C2" Stop error when you transfer large files over SMB 2.0 in Windows Server 2012
3036579 CA server freezes when you use an Eseutil utility to defrag an .edb database file in Windows Server 2012 R2
3036606 Windows 8.1 mobile broadband may not auto-reconnect after it resumes from connected standby
3036614 "0x000000D1" Stop error when you fail over a cluster group in Windows Server 2012 R2
3036965 Printing preferences window appears behind a RemoteApp window in Windows
3037317 xHCI controller disappears after you rescan the hardware in Device Manager in Windows 8.1
3037924 You cannot do System Image Backup to Blu-ray media in Windows
3037941 Files are replaced even though they are not changed when you run Robocopy command in Windows 7 or Windows Server 2008 R2
3038002 UHS-3 cards cannot be detected in Windows on Surface devices
3038017 Client computer does not obtain IP address from a DHCP failover that is running Windows Server 2012 R2
3038022 Background download of files cannot be resumed in Windows 8.1 or Windows RT 8.1
3038024 DNS names cannot be resolved and other DNS related issues occur in Windows Server 2012 R2
```

[http://blogs.msdn.com/b/winsdk/archive/2015/04/21/windows-hotfix-list-for-april-2015.aspx](http://blogs.msdn.com/b/winsdk/archive/2015/04/21/windows-hotfix-list-for-april-2015.aspx)

```
2745955 You cannot connect to a Windows Server-based cluster file share resource from a client computer when a cluster failover occurs
2884176 Large backlogs on Windows -based DFSR servers
2959626 Reliability improvements for Remote Desktop Session Host and RemoteApp
3013776 System freezes when you use a domain account to start an application in Windows
3027174 Insufficient MBCS file name support on the FTP client in Windows
3027578 I/O failure during MPIO path failover in Windows Server 2008 R2 SP1
3029432 The logon process for new users takes significantly longer as the number of user profiles increases on Windows Server 2008 R2
3030736 "550 The process cannot access the file" error when you try to download a file in Windows
3031598 Hyper-V host crashes and has errors when you perform a VM live migration in Windows 8.1 and Windows Server 2012 R2
3031987 Hotfix rollup 3031987 for the .NET Framework 3.5.1 on Windows 7 SP1 and Windows Server 2008 R2 SP1
3031988 Hotfix rollup 3031988 for the .NET Framework 3.5 on Windows 8 and Windows Server 2012
3031989 Hotfix rollup 3031989 for the .NET Framework 3.5 SP1 on Windows 8.1 and Windows Server 2012 R2
3035446 Offline files stop syncing after the location of home folder is changed in Windows 7 SP1 or Windows Server 2008 R2 SP1
3036089 "0x80070003" error when a Group Policy preference is applied to a domain-joined computer in Windows Server 2008
3036173 "0x00000050" Stop error when Hyper-V host crashes in Windows Server 2012 R2
3036542 "This page failed to load" error when you run Windows Store apps in Windows 8.1 or Windows RT 8.1
3037318 Event ID 1511 when you start a task with some specific settings in Windows 8 or Windows Server 2012
3039095 Update adds user name information to Directory Services event ID 1644 in Windows 8.1 or Windows Server 2012 R2
3041832 CPU usage is high on an Exchange Server 2013 server in Windows 8.1 or Windows Server 2012 R2
3042121 Hotfix enables AD FS token replay protection for Web Application Proxy authentication tokens in Windows Server 2012 R2
3042127 "HTTP 400 - Bad Request" error when you open a shared mailbox through WAP in Windows Server 2012 R2
3042816 AD DS or AD LDS responds slowly to LDAP query that has an undefined attribute and an OR clause in Windows Server 2012
3042825 Domain controllers crash after password sync is enabled in Identity Management for UNIX in Windows Server 2012 R2
3042841 Files cannot be copied when drive redirection is enabled in Windows 8.1 or Windows Server 2012 R2
3042842 Files cannot be copied when drive redirection is enabled in Windows 7 or Windows Server 2008 R2-based RDP 8.1 client
3042843 "Your computer can't connect to the remote computer" error because RD Gateway service freezes in Windows Server 2012 R2
3043762 "The process cannot access the file" error when you open files from NFS server in Windows Server 2008 R2 SP1
3044108 Update to improve battery performance and power schemes in Windows 8.1 or Windows Server 2012 R2
3044424 Work Folders may stop synching after the original AD FS certificate expires in Windows Server 2012 R2
3044428 "0x00000027" or "0x00000050" Stop error in the Rdbss.sys driver in Windows 7 SP1 or Windows Server 2008 R2 SP1
3044457 "STATUS_PURGE_FAILED" error when you perform VM replications by using SCVMM in Windows Server 2012 R2
3044738 Performance improvement for WinHTTP when lots of HTTP requests are received in Windows
3045882 Private key is not exported when you export a certificate in Windows 7 SP1 or Windows Server 2008 R2 SP1
3045923 You cannot unlock a remote session by entering a PIN code after you plug in the smart card in Windows
3046304 You cannot open files on ReFS in Windows 8.1 or Windows Server 2012 R2 if the file names contain Greek characters
3046465 USB devices drain battery fast on a computer that is running Windows 8.1 or Windows Server 2012 R2
3046481 DFS Namespaces deployment causes slow access or access time-out when you access DFS share in Windows Server 2012 R2
3046795 System crashes and you cannot change CPU frequency on Intel SKL platform in Windows 8.1 or Windows Server 2012 R2
3046826 You cannot upgrade Hyper-V integration components or back up Windows virtual machines
3047278 Performance improvement for WinHTTP when lots of HTTP requests are received in Windows 8 or Windows Server 2012
3047296 RDP session becomes unresponsive when you connect to a Windows Server 2012 R2-based computer
3047646 Domain controllers restart unexpectedly and the Lsass.exe process crashes in Windows Server 2012 R2
3047732 HTTP 404" error when you access a website with URL redirection in Windows
3047733 "No CA servers can be detected, and OTP cannot be configured." error when you enable OTP in Windows Server 2012 R2
3048161 4K resolution cannot be used to display videos in a Miracast session in Windows
3048469 Kernel debugging over network does not work on a Windows virtual machine
3048474 WMI provider cannot start when you manage Hyper-V or failover cluster in Windows 8 or Windows Server 2012
```

[http://blogs.msdn.com/b/winsdk/archive/2015/05/14/hotfix-releases-for-windows-may-2015.aspx](http://blogs.msdn.com/b/winsdk/archive/2015/05/14/hotfix-releases-for-windows-may-2015.aspx)

```
2672277 Some services are preloaded unexpectedly on an IIS 7.5 server in Windows
3018489 "No host bus adapter is present" error when querying SAS cable issues in Windows Server 2012 R2 or Windows Server 2012
3025091 Shared Hyper-V virtual disk is inaccessible when it's located in Storage Spaces on a Windows Server 2012 R2-based computer
3033937 32-bit applications do not receive events when the WscRegisterForChanges function is used on 64-bit Windows 8.1
3036169 Reliability improvement update for Windows 8.1 and Windows Server 2012 R2: May 2015
3036614 "0x000000D1" Stop error when you fail over a cluster group in Windows Server 2012 or Windows Server 2012 R2
3041673 You cannot enter PIN on a PIN pad device after you insert a smart card into a Windows-based computer
3042534 the Sleep option is missing on a Windows 8.1-based computer that uses the Intel Skylake chipset
3042816 AD DS or AD LDS responds slowly to LDAP query that has an undefined attribute and an OR clause in Windows Server 2012
3042836 The Remote Desktop Active X control Mstscax.dll leaks thread handles in Windows 8.1
3042839 Mstscax.dll file leaks handles on a Remote Desktop Protocol 8.1 client in Windows 7 or Windows Server 2008 R2
3044759 Black screen when you resume a laptop from hybrid shutdown in Windows
3045634 You cannot make a PPP connection after you reconnect a PLC device in Windows 8
3045682 You cannot restore files and folders from Server Essentials Backup on a Windows-based computer
3046394 WWAN device may disappear from charm bar on Intel BYT platform that is running Windows 8.1 or Windows Server 2012 R2
3046797 Single tunnel throughput drops after you install April 2014 update rollup on Windows Server 2012 R2
3046798 VPN gateway becomes unresponsive and a connection can't be established in Windows Server 2012 R2
3046799 Azure services overbill when you use point-to-site VPN service in Windows Server 2012 R2
3047280 "The URL cannot be resolved" error during network location server setup for a DirectAccess server in Windows Server 2012 R2
3047295 Virtual memory allocations for a 32-bit process fail in Windows Server 2012 R2
3048476 Application may not function correctly when it uses WMI queries in Windows
3048824 A w3wp.exe process crashes when a performance counter value is requested while the worker process shuts down
3049448 Resolution of external DNS records on a Windows Server 2012 R2 Hyper-V guest cluster fails through a Hyper-V Network Virtualization Gateway
3049605 Transparent graphic elements are filled when printed as XPS to a Windows 8.1 or Windows Server 2012 R2 Version 4 printer driver
3049843 You cannot access DPAPI data after an administrator resets your password on a Windows Server 2012-based domain controller
3050205 An IP Address Management error occurs in Windows Server 2012 R2 when a DNS record is deleted
3050293 Cluster resources are not initialized correctly after Rhs.exe process crashes on a Windows Server 2008 SP2-based cluster
3051395 No Wi-Fi connection if a Wi-Fi profile uses two or more SSIDs in Windows 8.1
3051472 DNS name resolution and DNSSEC validation fail in Windows Server 2012 R2
3051475 Cookies are not passed as part of a session when you make an HTTP connection in Windows 7 or Windows Server 2008 R2
3051690 System becomes unresponsive when you use xcopy command to copy files in Windows Server 2012 R2
3053660 The ScriptShapeOpenType function returns bad data in the target array for the pwLogClust parameter in Windows
3053744 Applications play 5.1-channel audio content that uses only two channels in Windows
3054187 "Before you can print, you need to select a printer" error when you try to print from a 32-bit application in Windows 8.1 and Windows Server 2012 R2
3054249 Backup application that calls the VSS service becomes unresponsive when the DFSR service is running in Windows
3054251 Stop Error in Rdbss.sys and unsaved documents in Windows 7 SP1 or Windows Server 2008 R2 SP1
3054290 Start screen and modern applications are displayed unexpectedly in German in Windows 8.1
3055292 Microsoft Hyper-V does not start on an AMD Carrizo-based computer that is running Windows 8.1 or Windows Server 2012 R2
3055343 Stop error code 0xD1, 0x139, or 0x3B and random crashes in Windows Server 2012 R2
3055778 Office 365 integration is unsuccessful if the Rights Management service is installed on Windows Server 2012 R2 Essentials
3056066 Backups fail for VMs with pre-existing software snapshots that use shadow storage set to a different drive in Windows 7 and Windows Server 2008 R2
```

[http://blogs.msdn.com/b/winsdk/archive/2015/06/11/the-real-hotfix-list-of-june-2015.aspx](http://blogs.msdn.com/b/winsdk/archive/2015/06/11/the-real-hotfix-list-of-june-2015.aspx)

```
3009986 A copy or move operation is unsuccessful if a symbolic link is included in Windows 7 or Windows Server 2008 R2
3024391 Incorrect dimensions are returned for a large custom page size when you use a PostScript driver and have update 2977285 installed on Windows 8.1
3045682 You cannot restore files and folders from Server Essentials Backup on a Windows-based computer
3046101 Server may freeze during startup when ALUA-capable storage is used in Windows Server 2012 R2 or Windows Server 2012
3047154 Promiscuous mode in Microsoft_Windows_NDIS_PacketCapture provider is not supported on Windows Server 2012 R2
3047295 Virtual memory allocations for a 32-bit process fail in Windows Server 2012 R2 or Windows Server 2012
3049443 Live migration of virtual machine to another host fails on a Windows Server 2012 R2-based Hyper-V host server
3052122 Update adds support for compound ID claims in AD FS tokens in Windows Server 2012 R2
3052480 Unexpected ASP.NET application shutdown after update 3000850 is installed in Windows Server 2012 R2
3053666 MTU size settings changes are not retained in Windows 8.1 or Windows Server 2012 R2
3055615 A Windows Server 2012 R2 server becomes slow and unresponsive if update 2927901 is installed
3056053 Snapshot contents are not accessible when Server for NFS has handle signing enabled
3058201 Events that contain "Waiting for stable state for group" fill Cluster.log on Windows Server 2012 R2 failover clusters during node drain
3060678 Snapshots are not deleted after you perform a backup operation by using VSS in Windows Server 2012 R2
3060738 Significant delays occur when obtaining data from Active Directory in Excel 2013 on a computer that is running Windows 7
3061460 Interrupts to the Intelligent Platform Management Interface driver are missed in Windows Server 2012 R2
3062558 Edge server sees increased traffic for name resolutions when update 295673 is installed in Windows Server 2012 R2
3062563 Limited connectivity through a manual proxy setup in Internet Explorer and Windows 8.1 Enterprise
3062567 Setup of an existing multi-node DirectAccess cluster fails through the UI or PowerShell in Windows 8.1 or Windows Server 2012 R2
3063060 Network connectivity dropped when time is adjusted on a DHCP client that is running Windows 7 SP1 or Windows Server 2008 R2 SP1
3063075 Many ID 129 events are logged when you run a Windows Server 2012 R2 virtual machine in Windows Azure
3063283 Update to improve the backup of Hyper-V Integrated components in Hyper-V Server 2012 R2
3063853 Clients are stuck in a "Connecting" state when they try to connect to a DirectAccess server that is running on Windows Server 2012 R2
3064222 Stop error code "Stop A: 0xA" when you run Windows Server 2008 R2 on a VMWare VM and use the VMware Memory Ballooning technique on a NUMA node
```

[http://blogs.msdn.com/b/winsdk/archive/2015/07/15/hotfixes-and-patches-for-windows-for-july-2015.aspx](http://blogs.msdn.com/b/winsdk/archive/2015/07/15/hotfixes-and-patches-for-windows-for-july-2015.aspx)

```
3060682 "The specified server cannot perform the requested operation" error occurs when GPO backup is unsuccessful and dynamic updates are disabled in Windows Server 2012 R2 
3061817 Windows 8.1 does not prompt for a smart card when the "Interactive Logon: Require Smart Card" Group Policy Object is enabled
3062586 "0x000000D1" Stop error on a Windows Server 2012-based cluster
3062960 "Object reference not set to an instance of an object" error when "Turn on Module Logging" is enabled and update 3000850 is installed on Windows Server 2012 R2
3064307 A memory leak occurs in the Local Security Authority Subsystem Service during a high Secure Sockets Layer workload in Windows Server 2012
3064749 Cannot resolve a subdomain name because the negative cache is counting down on a DNS server that is running Windows Server 2012 R2
3066044 Custom Tool tile is not displayed on the troubleshooting menu in Windows Server 2012 R2
3066427 You cannot compress Windows image files because of memory leak in Windows 8.1
3066685 Strong key protection cannot be enforced in Windows 8.1 and Windows Server 2012 R2
3067900 Rotated italic text flows in the wrong direction when it's printed on a PCL6 printer in Windows 8.1
3068362 Remotely managed Server Manager does not find connected storage connected in Windows Server 2012 R2
3068441 "Err (800704c3)" error occurs when you enable the host, file receive location and file send port for BizTalk 2013 R2 on a server that is running Windows Server 2012 R2
3068443 The Cluster service on remaining nodes stops unexpectedly when a Windows Server 2012 Failover cluster node experiences a power outage
3068444 "An unrecoverable failure occurred inside the filter manager" error on a failover cluster node that hosts shared VHDx files
3068445 Virtual machines that host on Windows Server 2012 R2 may crash or restart unexpectedly
3069129 Blank page is displayed when you try to access RemoteApps on a Windows Server 2012 R2-based RD Web Access server
3070078 AD FS 2.1 throws an exception when you authenticate against an encryption certificate in Windows Server 2012
3070080 Home realm discovery does not work correctly for a non–claims-aware relying party trust on Windows Server 2012 R2
3070083 Domain join against a Windows Server 2012 R2-based domain controller fails if SPN is not unique in the forest
3070714 "0x000000B8" Stop error during MPIO path failover in Windows Server 2008 R2 SP1
3070746 Hotfix for certain devices to support MSI-X interrupt mode in Windows 8.1 or Windows Server 2012 R2
3071712 Mmc.exe crashes when you open properties of an AD object in Active Directory Users and Computers in Windows Server 2012
3071787 "0x0000007E" Stop error after you install service packs or hotfixes in Windows
3072380 Hyper-V cluster unnecessarily recovers the virtual machine resources in Windows Server 2012 R2
3072381 "0xc000017" error when you restart a UEFI-based computer in Windows
3072401 File system corrupts when you delete a file that has 4 GB-1 bytes of size on FAT32 system in Windows
```

[http://blogs.msdn.com/b/winsdk/archive/2015/08/12/windows-august-2015-hotfix-list.aspx](http://blogs.msdn.com/b/winsdk/archive/2015/08/12/windows-august-2015-hotfix-list.aspx)

```
2966038 Printer managed by custom print providers is not visible in Devices and Printers in Windows
3071345 Start screen customization is disabled for a Windows Embedded 8.1 Industry Pro-based computer
3073902 NDES stops working after you restart a Windows Server 2012 R2-based CA server
3073922 Groups may not be assigned correctly after a node failure on a Windows Server 2012 R2-based failover cluster
3075161 Computer might crash during storage enumeration stack in Windows Server 2012 R2
3075610 Trust relationships are lost on secondary AD FS server after you add or remove claims provider in Windows Server 2012 R2
3075623 Configuring registry policy processing causes MUP to ignore Group Policy setting in Windows 7 or Windows Server 2008 R2
3075872 Application might stop working when it is used in Windows
3076946 CSV VSS writer does not report components after a deduplication volume is added to CSV in Windows Server 2012 R2
3076950 "STATUS_CONNECTION_RESET" error when an application reads a file in Windows Server 2012 R2 or Windows Server 2012
3077354 Computer freezes when WFP leaks nonpaged pool memory in Windows Server 2012 R2
3078405 "0x0000004A" or "0x0000009F" Stop error occurs in Windows 8.1
3078411 Tenant VMs lose network connectivity if NAT gateway VM exhausts all TCP/IP ephemeral ports in Windows Server 2012 R2
3078412 Rhs.exe process crashes during offline of IP address resource in Windows Server 2008 R2 SP1
3078689 The prompt is not displayed to the correct user in Windows Server 2012 R2-based RDS server
3078919 eMMC device is not detected as a storage device by Windows 8.1 or Windows Server 2012 R2
```

[http://blogs.msdn.com/b/winsdk/archive/2015/09/09/windows-hotfix-list-for-september-2015.aspx](http://blogs.msdn.com/b/winsdk/archive/2015/09/09/windows-hotfix-list-for-september-2015.aspx)

```
2877115 Error message when you try to perform a LUN resynchronization in Windows Server 2012 or Windows Server 2008 R2 SP1
2921629 Stop Error 0x133 in the Netft.sys driver occurs in a node that is running Windows Server 2012 or Windows Server 2008 R2
3012714 Hyper-V storage migration failure and "ERROR_BAD_COMMAND" error in Windows Server 2012 R2 or Windows Server 2012
3025091 Shared Hyper-V virtual disk is inaccessible when it's located in Storage Spaces on a Windows Server 2012 R2-based computer
3067902 Can't connect to RemoteApps if Terminal Services Easy Print driver freezes in Windows Server 2008 R2
3069129 Blank page is displayed when you try to access RemoteApps on a Windows-based RD Web Access server
3073062 DPM server takes too long to complete backup tasks in Windows Server 2012 R2
3073629 Redirected printers go offline after print spooler is restarted on a Windows Server 2012 R2-based RD Session Host server
3073630 Remote Desktop Easy Print runs slowly in Windows Server 2012 R2
3075623 Configuring registry policy processing causes MUP to ignore Group Policy setting in Windows
3076953 Cluster services go offline when there's a connectivity issue in Windows Server 2012 R2 or Windows Server 2012
3077665 Stop error 0xD1 when you set the SIO_LOOPBACK_FAST_PATH flag in Windows 8 or Windows Server 2012
3078420 0xC2 or 0xD1 Stop error on cluster nodes that are running Windows Server 2012 R2
3078584 0x133 or 0x13C Stop error occurs in Windows 8.1 or Windows Server 2012 R2
3078627 Offline Files network shares might not be available in Windows 8.1
3078630 32-bit applications can't change local Group Policy on 64-bit version of Windows 8.1 or Windows Server 2012 R2
3078631 Windows Server Backup fails despite sufficient space on the target volume in Windows Server 2012 R2
3078632 Backup software can't take server backups in Windows Server 2008 R2 SP1
3078634 Virtual machines don't respond to your operation in SCVMM in Windows Server 2012
3080140 User files are available offline when SMB shares don't allow client caching in Windows 7 or Windows Server 2008 R2
3080777 Dsamain.exe process crashes when AD LDS instance raises an exception in Windows 8.1 or Windows Server 2012 R2
3080778 AD FS does not call OnError when MFA adapter throws an exception in Windows Server 2012 R2
3080780 Super user can't access or recover expired content in Windows Server 2012 R2
3082808 File filtering and device locking features can't be enabled by using custom UMDF drivers for WPD devices in Windows
3083424 "SYNC_E_METADATA_INVALID_OPERATION" error when Work Folders stops syncing in Windows Server 2012 R2
3084952 Users can't log on to a Windows Server 2012 R2-based server through remote desktop because of RDSLS database corruption
3087856 Non-queued commands are sent to disk controller on a Windows Server 2012 R2-based Hyper-V host server
3087873 "0x0000007E" Stop error after you install hotfix 2990941 in Windows 7 SP1 or Windows Server 2008 R2 SP1
```

[http://blogs.msdn.com/b/winsdk/archive/2015/10/26/10647755.aspx](http://blogs.msdn.com/b/winsdk/archive/2015/10/26/10647755.aspx)

```
3030736 "550 The process cannot access the file" error when you try to download a file in Windows
3044546 An updated reservation may disappear on a DHCP failover cluster in Windows Server 2012 or Windows Server 2012 R2
3049591 Transparent areas are printed as black when you use a v4 XPS printer driver in Windows
3053667 Users can't connect to virtual machines that are running Windows 8.1 or Windows Server 2012 R2 by remote desktop
3077354 Computer freezes when WFP leaks nonpaged pool memory in Windows Server 2012 R2 or Windows Server 2012
3084093 Child nodes under protected OU are deleted in Windows Server 2012 R2
3084426 System becomes unresponsive when file system minifilter drivers are installed in Windows 8 or Windows Server 2012
3084787 Event ID 4102 when DFS Replication cloning fails on a Windows Server 2012 R2-based cluster
3084953 OOBE crashes when you enter SIM card PIN in Windows 8.1
3084956 You can’t log on to a domain-joined computer in Windows 8 or Windows Server 2012
3084983 SetOptions or GetOptions method doesn't work for PRINTER_PROPERTY features in Windows
3086644 System freezes after you start a backup task for virtual machines in Windows Server 2012 R2
3090322 Space doesn't regenerate upon reallocation in Windows Server 2012 R2
3090973 Reenlist can't be called when SQL Server receives transaction outcome from MSDTC in Windows Server 2012 R2
3091057 Cluster validation fails in the "Validate Simultaneous Failover" test in a Windows Server 2012 R2-based failover cluster
3091061 Update to add CSVFS tracing for performance issues during backup operations in Windows Server 2012 R2
3091342 Computer crashes after you install update 3000850 in Windows 8.1
3091402 Site-to-site VPN goes down when you set a VNet-to-VNet connection in Azure in Windows 8.1 or Windows Server 2012 R2
3091403 High CPU usage for 12 seconds on a multiple-network-adapters computer in Windows Server 2012 R2 or Windows Server 2012
3092002 Set-Acl cmdlet fails although delegated admins have "Change Permissions" enabled in Windows Server 2012 R2
3092003 Page loads repeatedly and authentication fails when users use MFA in Windows Server 2012 R2 AD FS
3092005 Group Policy settings are set back to factory settings in GPMC in Windows Server 2012 R2
3092006 Subfolders disappear from FSRM console after you rename the root folder in Windows Server 2012 R2 or Windows Server 2012
3092695 Licensing report file is corrupted in Windows Server 2012 R2 RDS environments for large report files
3093550 All ScriptProperty members are invoked when you run the Add-Member PowerShell command in Windows 8.1
3093571 Update to replicate multiple VM groups and VMs that use shared VHDs in Windows Server 2012 R2 or Windows Server 2012
3093803 Error 0x800704C9 occurs when you try to copy file to NFS share in Windows 8 or Windows Server 2012
3093899 VMs that run on CSVs fail if DCM can't query volumes in Windows Server 2012 R2
3093900 0x50 Stop error and users can't access documents on shared folders or home folders in Windows Server 2012 R2
3094197 Files aren't fully optimized and a deduplication cache lock contention issue occurs in Windows Server 2012 R2
3094199 Application module can't receive correct process status after security update 3045999 is installed in Windows
3094202 Directory listing fails when sharing violations occur on Windows Server 2012 R2 or Windows Server 2012-based NFS server
3094446 Authentication through proxy fails in Windows Server 2012 or Windows Server 2008 R2 SP1
3095308 VMs may not get additional memory although they're set to use Dynamic Memory in Windows Server 2012 R2
3095319 You receive an error message when you use GPMC to manage audit policies in Windows 8.1 or Windows Server 2012 R2
3095663 VSS_E_PROVIDER_VETO error occurs when you restore a LUN from backup in Windows Server 2012 R2
3095711 Update to support LTO-7 tape drives in Windows Server 2012 R2 and Windows Server 2012
3095737 Azure Backup takes a long time to back up data with a guest OS that's running Windows Server 2012
```

[http://blogs.msdn.com/b/winsdk/archive/2015/11/11/hotfixes-for-november-2015.aspx](http://blogs.msdn.com/b/winsdk/archive/2015/11/11/hotfixes-for-november-2015.aspx)

```
3040017 XPS driver is slower than GDI driver to print files in Windows
3063109 Virtual machine crashes and WAL consistency is not maintained for Guest clustered VMs in Windows Server 2012 R2
3078414 NFS service freezes on a Windows Server 2012 cluster and a client computer can't access NFS share
3080141 Cluster service freezes on a Windows Server 2012 R2 or Windows Server 2012-based failover cluster
3086918 Original file is lost with new file not being saved in WebDAV folder in Windows 8.1
3091411 User connection fails when many connections are made to Windows Server 2012 R2-based RD Connection Broker
3092604 Network is corrupted between Guest OS and external network for VMs hosted on Windows 8.1 or Windows Server 2012 R2
3092688 UPD profiles corrupted when a network connectivity issue occurs in Windows Server 2012 R2
3095113 Update to enable WSUS support for Windows 10 feature upgrades
3095682 File Explorer shows thumbnail contents even though files are marked with offline flag in Windows
3098841 Application crashes with access violation error in Windows 7 or Windows Server 2008 R2
3100460 Video stops playing unexpectedly when another video pauses in the same application in Windows 8 or Windows Server 2012
3100474 Can't connect to wireless network when you resume the computer from hibernate mode in Windows
3100477 A large file upload or a large repository clone fails on VSO in Windows Server 2012 R2
3100527 System becomes unresponsive and crashes on Windows Server 2012 R2-based file servers
3100530 Windows backup fails with no sufficient free space on target volume in Windows Server 2012
3101217 Client requests take a long time to execute or COM+ application freezes in Windows 7 SP1 or Windows Server 2008 R2 SP1
3101694 "0x000000D1" Stop error in Pacer.sys when there's heavy QoS traffic in Windows Server 2012 R2
3101705 Schema load failures or SPF failures in Windows Server 2012 R2 in Turkey
3101718 Application freezes when you switch the system from DC mode to AC mode in Windows 8.1 or Windows Server 2012 R2
3102236 Group membership removal operation fails when this operation is for a deleted user account in Windows Server 2008 R2
3102242 Computer crashes or restarts unexpectedly when it's resumed from sleep mode in Windows
3102354 Hyper-V generation 2 virtual machines can't start with some pass-through disks in Windows Server 2012 R2
3102770 The chkdsk command together with the spotfix option doesn't fix extended volumes corruption in Windows Server 2012 R2
3103000 RemoteApp windows disappear and screen flickers when you switch between windows in Windows 8.1 or Windows Server 2012 R2
3103616 WMI query doesn't work in Windows Server 2012
3105881 Can't access applications when device authentication is enabled in Windows Server 2012 R2-based AD FS server
```

[http://blogs.msdn.com/b/winsdk/archive/2015/12/09/hotfixes-for-december-2015.aspx](http://blogs.msdn.com/b/winsdk/archive/2015/12/09/hotfixes-for-december-2015.aspx)

```
2920591 High CPU usage and performance issues occur when access-based enumeration is enabled in Windows 7 Service Pack 1 or Windows Server 2008 R2 Service Pack 1
3084463 WSUSutil.exe csaimport fails upon import in Windows Server 2012 R2 or Windows Server 2012
3095319 You receive an error message when you use GPMC to manage audit policies in Windows 8.1 or Windows Server 2012 R2
3102997 Data is corrupted after iSCSI sessions or paths recover in Windows Server 2012 R2 or Windows Server 2012
3102998 Application can't connect to iSCSI servers in Windows Server 2012 R2 or Windows Server 2012
3106296 Can't connect to a wireless network when you resume the computer from hibernation
3107128 Search result is incomplete if search criteria contain digits in Windows
3108319 VSS backup of the PI Data server fails and the computer crashes in Windows 8.1 or Windows Server 2012 R2
3109093 Applications can't communicate over TCP loopback path in Windows 8.1 or Windows Server 2012 R2
3109099 Update adds support for the slow timer in LACP in Windows Server 2012 R2
3109156 Applications may freeze when ADSI APIs waits infinitely for server to respond in Windows Server 2012 R2
3109600 Users can't log on to Outlook Web App client from a browser in Windows
3109973 Backup fails with a "File Not Found" error on a Windows Server 2012 R2 cluster
3114133 Windows Server Backup fails when you back up multiple volumes in Windows Server 2012 R2
```

[http://blogs.msdn.com/b/winsdk/archive/2016/01/13/hotfix-for-january-2016.aspx](http://blogs.msdn.com/b/winsdk/archive/2016/01/13/hotfix-for-january-2016.aspx)

```
3047331 "0x00000050" Stop error on a failover cluster that is running Windows Server 2012 R2 or Windows Server 2012
```

[http://blogs.msdn.com/b/winsdk/archive/2016/02/10/hotfix-list-for-february-2016.aspx](http://blogs.msdn.com/b/winsdk/archive/2016/02/10/hotfix-list-for-february-2016.aspx)

```
3007507 "HTTP Error 500.19" error when you browse an IIS 8.5 website in Windows
3090343 Cluster service stops during the VSS backup in a Windows Server 2012 R2 or Windows Server 2012-based Hyper-V cluster
3123593 A multi-site failover cluster goes into a split brain situation in Windows Server 2012 R2
3133689 UBPM doesn't set environmental variables correctly when you run scheduled tasks in Windows Server 2012 R2
```
