# All_in_One
平时工作时的一个小工具（限android平台+python3.6.x)

此应用就是用于平时工作时的便利，因为在测试过程中有时要反正的抓取log和截图，都是一些常见的操作，但是又没有一个集中的tool. 

用法：
    导出APK to desk(前台正在使用的apk)　用法:
    -----------------------------------------
    cmd='8' , 将导出当前前台正在使用的apk至桌面
    cmd='8,', 仅输出当前信息的包信息
    
    
    Copy文件(MTKlog/DCIM/Copyfiles)至桌面 用法：
    -------------------------------------------
    1:仅删除mtklog文件夹
    可输入:'d m', 'd,m', 'd mtklog', 'd,mtklog', 'del mtklog', 'del,mtklog', 'del m', 'del,m'
    2:仅删除DCIM文件夹
    可输入:'d d','d,d',  'del d', 'del,d', 'del dcim','d dcim', 'del,dcim', 'd,dcim'
    3:仅删除Copyfiles文件夹
    可输入:'d cf', 'd c','d,cf', 'd,c', 'del cf', 'del c',  'del,cf', 'del,c', 
    4:复制Mtklog至桌面then删除手机中的Mtklog文件夹
    可输入：'2', '2,', '2m', 'mtklog', '2mtklog', 
    5:复制Mtklog/DCIM文件夹then删除手机中的Mtklog/DCIM文件夹 
    可输入:'2mp','mp','2md', 'md'
    6:复制DCIM文件夹至桌面then删除DCIM文件夹
    可输入：'2d', '2dcim', 'dcim'
    7:复制Copyfiles至桌面then询问是否删除copyfiles文件夹
    可输入：'2c', '2cf', 'cf', 'copyfiles', 'copyfile'
    
    
    打开MTKlog 用法：
    ----------------
    cmd = '3', 打开mtklog主界面
    cmd = ('3 0', '3,0'), 关闭mtklog
    cmd = ('3 1', '3,1'), 开启mtklog
