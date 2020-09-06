# 描述 Description
**This is an Artificial Intelligence Go project. The project is created by my friend Wang Qi, Dong yue and me.**
**这是一个人工智能围棋的项目，是由2015级上海建桥学院王奇，董越以及我共同完成的。**
# 演示视频 Demo Video
**[演示视频 Demo Video] (https://www.bilibili.com/video/BV1wb41177ah)**
---
# 各个文件夹介绍 Decription of each folder
## PikachuGo - 主要代码 Main Program Source Code
## PikachuGoNN - 神经网络训练代码 Source code of training Neural Networks
## PikachuGoDataSample - 神经网络训练后以及训练过程中的示例参数文件 Sample Parameter files of Training Neural Networks
## PikachuGoDataSet - 神经网络数据集以及训练后的参数 DataSet Of Neural Networks
---
# 关于如何运行 How to play PikachuGo
首先你需要下载python2 (>=2.7.15) 然后安装pip。安装后使用cmd或者Powershell在PikachuGo文件夹下，使用命令pip install -r requirements.txt 安装必要组件。
然后使用打谱软件（这里推荐Sabaki），在Engines -> Manage Engines 弹出的下方窗口，定位到PikachuGo文件夹下的run.bat，保存；然后Engines -> Attach 选择PikachuGo即可。

# 一些设置参数 Configs
使用任何支持Python的IDE或者写字板打开PikachuGo文件夹下的Config.py，里面有相应的参数介绍，修改后保存即可开始运行。
**不建议打开神经网络运算，因为没有做太多优化导致搜索速度比较慢，大约只有10playOuts/sec**



