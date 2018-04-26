# 安装2.7和3.5和改文件名

官网下载安装即可，路径建议为D:\Python27和D:\Python35， 看个人

到安装文件夹下，分别将python.exe、pythonw.exe文件名改为

>python2.exe、pythonw2.exe 

>python3.5.exe、pythonw3.5.exe

进入命令行运行python2.7、python3.5、python3.6会分别调用python2.7和python3.5、python3.6

>python2.7 % 运行python2.7

>python3.5 % 运行python3.5

>python3.6 % 运行python3.6

# 添加环境变量

分别（手动）添加系统环境变量PATH：python两版本的入口程序位置，两个pip 的入口程序位置

>D:\Python27\  
>D:\Python27\Scripts\  
>D:\Python35\  
>D:\Python35\Scripts\  
>D:\Python36\  
>D:\Python36\Scripts\ 

# 安装pip模块

运行

>python2.7 -m pip install --upgrade --force-reinstall pip % 安装pip于2.7的模块集

>python3.5 -m pip install --upgrade --force-reinstall pip % 安装pip于3.5的模块集

>python3.6 -m pip install --upgrade --force-reinstall pip % 安装pip于3.6的模块集

使用时可以直接在命令行中输入

>pip2.7

>pip3.5

>pip3.6

分别调用2.7、3.5和3.6版本的pip模块
