# url

https://github.com/kasini3000/kasini3000_agent_win7_x64.git

# kasini3000_agent_win7_x64

kasini3000_agent_win7_x64 is powershell + winrm on win7.on win2008r2.

powershell 5.1 for en-us zh-cn


use "setup_winrm_win7.bat" to setup winrm on win7.on win2008r2. 


# 安装说明 for win7 ,win2008r2。

1 需要开启windows update服务。如果不想更新其他系统补丁，可以先拔掉网线，再开启windows update服务。

2 假如你安装了powershell 3.0 需要先卸载。并卸载已经安装的任何beta版powershell。

3 powershell5.1和powershell6.0可以并存。

4 按照顺序安装1，2，3，4打头的软件。安装完后，运行【开启脚本运行权限.bat】。

5 1打头的软件包，是一个补丁。安装1的目的是为了能安装2。假如无法安装1，可以跳过，直接装2，3，4试试。

6 2打头的软件包，是 .net framework的安装包，安装2之后，如果要求重启，就重启。

7 3打头的软件包，是 .net的简体中文语言包。

上面.net framework 下载地址：

https://dotnet.microsoft.com/download/dotnet-framework/net48

8 4打头的软件包，是powershell5.1。

下载地址：
https://docs.microsoft.com/zh-cn/powershell/scripting/install/installing-windows-powershell?view=powershell-5.1

9 1，2，3，4都有微软的签名。无病毒，放心使用。
