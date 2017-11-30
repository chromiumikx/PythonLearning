建立一个简单的PYQT程序时，运行出现找不到qt platform windows plugins问题。  
查到多方，pip重装过，也安装了QT(C++)，没有作用，实际上不需要再安装C++库。  
最后发现是环境变量没有配置，解决如下：  
PyQt5安装完后，需要增加系统变量：

>QT_QPA_PLATFORM_PLUGIN_PATH  
>C:\Users\username\AppData\Local\Programs\Python\Python35\Lib\site-packages\PyQt5\Qt\plugins # 这是PYQT plugins所在位置
