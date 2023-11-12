Tips for install an extra older version MacOS on a higher version MacOS  
  
1.准备一个16G(or more)U盘,下载自己需要的旧版MacOS系统，并制作U盘系统备用  
  参考 https://support.apple.com/zh-cn/HT201372  
  
2.添加 APFS 宗卷  
  (1)打开“磁盘工具”（位于“应用程序”文件夹的“实用工具”文件夹中）。  
  (2)在边栏中，选择现有的 APFS 宗卷，如 Macintosh HD。  
  (3)从菜单栏中选取“编辑”>“添加 APFS 宗卷”，或者点按“磁盘工具”工具栏中的“添加宗卷”按钮 (+)。仅当选择的宗卷采用 APFS 格式时，这些选项才可用。  
  (4)为新宗卷键入任意名称，然后点按“添加”。  
  (5)退出“磁盘工具”。  
  ![image]([https://support.apple.com/zh-cn/HT208891](https://support.apple.com/library/content/dam/edam/applecare/images/zh_CN/macos/monterey/macos-monterey-disk-utility-add-volume.png))  
  
3.检查本机是否从可引导安装器启动，确保“启动安全性实用工具”已设为允许从外部介质或可移动介质启动  
  (1)将你的 Mac 开机，然后在看到 Apple 标志后立即按住 Command (⌘)-R 键（或Win+R）。Mac 会从“macOS 恢复”启动。  
  (2)当系统要求你选择一个你知道相应密码的用户时，请选择这样的用户，点按“下一步”，然后输入用户的管理员密码。  
  (3)当你看到“macOS 实用工具”窗口时，从菜单栏中选取“实用工具”>“启动安全性实用工具”(选择无安全性，允许从外部介质或可移动介质启动)。  
  (4)当系统要求你进行认证时，点按“输入 macOS 密码”，然后选取管理员帐户并输入相应密码。  
  ![image](https://cdsassets.apple.com/live/7WUAS350/images/macos/big-sur/locale/zh-cn/macos-big-sur-recovery-mode-startup-security-utility.png)  
  
4.安装macOS  
  (1)重启电脑(确认U盘已插入电脑)，在看到 Apple 标志后立刻按住Option键(或Alt键)，即可进入选择磁盘启动界面,选择U盘启动  
  ![image](https://support.apple.com/library/content/dam/edam/applecare/images/zh_CN/macos/monterey/macos-monterey-install-beta-software.png)  
  (2)在安装界面的「终端」工具里输入修改时间的命令  
  ![image](https://img-blog.csdnimg.cn/4cb90ef557b8429ab8996990275396a7.jpeg#pic_center)  
    date 0201010116（OS X El Capitan 10.11.6适用）  
    date 010514102017.30（macOS Sierra 10.12适用）  
    date 062614102014.30 （10.13、10.14适用）  
    date 121212122019 （10.15）  
    date 032208102015.20  
    date 112202022015  
    date 122014102015.30（10.10可用）  
  (3)选择安装位置, 选择第2步创建的宗盘，确认，下一步直至完成安装  
