## 常规更新

下载[winxp_with_sp3_x86_dl.txt](https://github.com/CNMan/MicrosoftHotfixesList/raw/master/winxp_with_sp3_x86/winxp_with_sp3_x86_dl.txt)和[embedded_chs_dl.txt](https://github.com/CNMan/MicrosoftHotfixesList/raw/master/winxp_with_sp3_x86/embedded_chs_dl.txt)中的全部文件以及[WindowsUpdateAgent-7.6-x86.exe](http://download.windowsupdate.com/windowsupdate/redist/standalone/7.6.7600.320/WindowsUpdateAgent-7.6-x86.exe)

和.cmd、.reg放在同一个文件夹

依次运行1~7，每一步都需重启

## .NET

若需.NET，下载[.net.txt](https://github.com/CNMan/MicrosoftHotfixesList/raw/master/winxp_with_sp3_x86/.net.txt)中的全部文件，以及：

[ Microsoft .NET Framework 版本 1.1，简体中文版 ](http://www.download.windowsupdate.com/msdownload/update/v3-19990518/cabpool/dotnetfx_1938f49476b928257b84f8d94a8ef4b.exe)

[ Microsoft .NET Framework 版本 1.1 简体中文语言包 ](http://www.download.windowsupdate.com/msdownload/update/v3-19990518/cabpool/langpack_7b299d728d9254f08fc3ac9b859759d.exe)

[ Windows XP 更新程序 (KB961118) ](http://download.windowsupdate.com/msdownload/update/software/crup/2009/02/windowsxp-kb961118-x86-chs_c458964259e9f53b8703afa3e465a232ddef3a81.exe)

[ 用于 Windows XP 和 Windows Embedded 的 Windows PowerShell 2.0 和 WinRM 2.0 (KB968930) ](http://download.windowsupdate.com/msdownload/update/software/updt/2009/11/windowsxp-kb968930-x86-chs_e4f5fe5d846f70c3bcbcc7819c3f2191133bc069.exe)

注：.NET安装时需联网，依次运行.net_1.1_install.cmd、.net_1.1_update.cmd、.net_2.0_3.0_3.5_install.cmd、.net_2.0_3.0_3.5_update.cmd、.net_2.0_3.0_3.5_update2.cmd、.net_4_install.cmd、.net_4_update.cmd，每一步都需重启，安装过程比较费时，请耐心等待。

## 以下更新可选安装：

[Windows Installer 4.5](https://download.microsoft.com/download/2/6/1/261fca42-22c0-4f91-9451-0e0f2e08356d/WindowsXP-KB942288-v3-x86.exe)

[ MSXML 6.0 RTM 安全性更新 (925673) ](http://www.download.windowsupdate.com/msdownload/update/v3-19990518/cabpool/msxml6-kb925673-enu-x86_571e99946aa6674ee6a70cf5801682ec323c7ae0.exe)

[Microsoft Visual C++ Redistributable Package 2005/2008/2010/2012/2013/2015/2017](https://github.com/CNMan/MicrosoftHotfixesList/tree/master/Microsoft_Visual_C++_Redistributable_Package)

## 以下更新不安装：

[ 用于 Windows XP 的 Windows 搜索 4.0 (KB940157) ](http://www.download.windowsupdate.com/msdownload/update/software/ftpk/2008/06/windowssearch-kb940157-xp-x86-chs_9df57daf8814565225b7a2a02c9fe71ffa25f482.exe)

[ Windows XP 安全更新程序 (KB963093) ](http://download.windowsupdate.com/msdownload/update/software/secu/2009/06/windowsserver2003.windowsxp-kb963093-x86-enu_c53606bca846117e1cebe7dd9a37251cb84aa41d.exe)

[ Windows Live 软件包 ](http://download.windowsupdate.com/msdownload/update/software/ftpk/2009/09/wlsetup-web_60f50d71da76dc27ed8d6545700cb2d6456d99d2.exe)

[ Feature Pack - Microsoft Security Essentials - 4.4.304.0 (KB2902907) ](http://download.windowsupdate.com/d/msdownload/update/software/ftpk/2013/11/mseinstall_72bfcac02f8103100ec6beb50c1115f29a3be5be.exe)

[ 必应 Bing 输入法 1.3 ](http://download.windowsupdate.com/d/msdownload/update/software/ftpk/2014/01/bingpinyinsetup_1.3.1.02_external_mu_0d991c067d825a8412e786005bb0084a88e5bb4e.exe)

[ 设备健康助手 1.0 (KB2938861) ](http://download.windowsupdate.com/d/msdownload/update/software/ftpk/2014/04/devicehealth_mu_cc698b85ab9072e1f0a33121e32e5dab6c4e1747.exe)

[ Microsoft Silverlight (KB2977218) ](http://download.windowsupdate.com/c/msdownload/update/software/uprl/2014/07/silverlight_91ca5fcf9fd82f2059401514a2ba66fee471af5f.exe)

[ Skype Windows桌面版7.3可选更新(kb2876229) ](http://download.windowsupdate.com/d/msdownload/update/software/ftpk/2015/04/skypesetupfull(7.3.0.101)_4d484d9d57be74b90fa99a84b1ef84be739c960b.exe)

## 安装完成后可用Windows Update MiniTool或Microsof Update检测是否有遗漏。

## 参考资料

[Command-line switches for Windows software update packages](https://support.microsoft.com/en-us/help/262841/command-line-switches-for-windows-software-update-packages)

```
/q	/quite	安静模式 - 与无人值守模式相同，但不显示状态或错误信息。	Quiet mode - same as unattended mode, but no status or error messages are displayed.
/z	/norestart	安装完成后不重新启动计算机。	Do not restart the computer when the installation is finished.
/n	/nobackup	不为备份卸载文件。	Do not back up files for uninstall.
/o	/overwriteoem	不经提示即覆盖 OEM 文件。	Overwrite OEM files without prompting.
```
