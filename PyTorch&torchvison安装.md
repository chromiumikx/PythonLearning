## 1. 环境版本问题
> Windows：10  
Cuda：9.0（CuDNN：7.0）  
Python：3.6  

## 2. 安装方法
先安装完Anaconda，便于管理python环境。

在Anaconda（GUI界面中）中新建一个Python3.6环境，激活进入命令行。

运行：
> conda install pytorch cuda90 -c pytorch  

完成后再运行：
> pip install torchvision

即在conda中使用pip命令（不必用pip3，因为conda已经有环境管理了）安装torchvision。

安装完成。

## 3. 测试
进入上述的Python3.6环境，运行 `python` 进入Python命令行模式，运行：
> import torch

没有报错则说明安装成功。

## 4. 如果CUDA工作不正常，就要关掉了（暂时没遇到）
cudnn.enabled = False
