下载[winxp_with_sp3_x86_chs_dl.txt](https://github.com/CNMan/MicrosoftHotfixesList/raw/master/winxp_with_sp3_x86/winxp_with_sp3_x86_chs_dl.txt)中的全部文件

和.cmd、.reg放在同一个文件夹

依次运行1~14，若无需.NET，则可选择跳过，每一步都需重启，安装过程比较费时，请耐心等待。

## 以下更新可选安装：

[ MSXML 6.0 RTM 安全性更新 (925673) ](http://download.microsoft.com/download/1/9/2/192290ae-adf5-46e3-867c-8d70f0967c23/msxml6-KB925673-chs-x86.exe)

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
