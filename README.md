# VscodeCPP_AutoSettings
## vscode三步自动化配置C++单cpp编译环境(Windows下配置)
#### 运行安装程序set_up.exe
> 下载项目至本地后,运行安装程序set_up.exe,在安装程序中选择MinGW64安装路径(路径不能为中文),程序会自动安装并设置环境变量并配置好.vscode\*.json文件,出现包含'done!'的提示窗口即成功.
#### 运行工作文件mymove.exe
- 选择.vscode工作环境路径(非中文路径).
- 在vscode打开包含.vscode所在的目录，即配置好了C++单cpp编译环境.
#### 问题补充及解决方案
> 需要手动解决
- 问题一
> 安装后不能编译运行程序(因环境变量需重启后才生效)
- 解决方案
> 重启下电脑

<br />


- 问题二
> 在使用C++终端运行功能中，输入中文，输出中文异常(其他功能无异常).
- 解决方案
> 将项目中的WindowsDebugLauncher.exe,替换掉'c:\Users\Lenovo\\.vscode\extensions\ms-vscode.cpptools-1.7.1\debugAdapters\bin\WindowsDebugLauncher.exe'(这是我的路径，大概都类似是'C:\用户\用户名\\.vscode\extensions\ms-vscode.cpptools-1.7.1\debugAdapters\bin\WindowsDebugLauncher.exe').


<br />


#### coderunnerC/C++插件配置
> 在环境变量txt中有较好的配置内容,可进行参考.


<br />


- 特别感谢
> 特别感谢 https://github.com/imba-tjd/build-miengine/actions 的WindowsDebugLauncher.exe,及时地解决了乱码问题.
