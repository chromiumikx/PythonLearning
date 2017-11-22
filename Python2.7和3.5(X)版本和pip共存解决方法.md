# 安装2.7和3.5和改文件名

官网下载安装即可，路径建议为D:\Python27和D:\Python35， 看个人  
到安装文件夹下，分别将python.exe、pythonw.exe文件名改为

>python2.exe、pythonw2.exe 

>python3.exe、pythonw3.exe

进入命令行运行python2、python3会分别调用python2.7和python3.5

>python2 % 运行python2

>python3 % 运行python3

# 添加环境变量

分别手动添加系统环境变量PATH：python两版本的入口程序位置，两个pip 的入口程序位置

>D:\Python27  
>D:\Python27\Scripts  
>D:\Python35  
>D:\Python35\Scripts 

# 安装pip模块

下载[get-pip.py文件](https://bootstrap.pypa.io/get-pip.py)到目录：

>D:\Python27\Scripts  
>D:\Python35\Scripts

进入命令行，运行

>python2 get-pip.py % 安装pip于2.7的模块集

>python3 get-pip.py % 安装pip于3.5的模块集
