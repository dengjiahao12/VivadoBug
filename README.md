# VivadoBug
#本仓库用来放置在使用Vivado的时候遇到的BUG以及解决方法。
#基于AX7015的用户使用文档。

### 1、在cource_s1_ALINX_ZYNQ(AX7015)开发平台基础教程V1.09.pdf中 ### 

在走到**4.4添加管脚约束**时候，点击软件中的Open Elaborated Designed出现闪退的问题。
解决方法：修改系统名字和安装目录的文件名，**不能有中文，一点都不能有**(好娇惯的软件)

<img width="533" alt="image" src="https://github.com/dengjiahao12/VivadoBug/assets/144973506/17110a3e-5263-4f3a-9aba-75c28f9d084a">

修改系统名字不能有中文

<img width="746" alt="image" src="https://github.com/dengjiahao12/VivadoBug/assets/144973506/47f949ff-8cc3-4882-bcb3-1b13207288ad">

选择重命名这台电脑，不能有中文，然后重启就ok了。

<img width="1096" alt="image" src="https://github.com/dengjiahao12/VivadoBug/assets/144973506/e188e8d7-e2e4-42c7-9b9b-33d39ef801f0" style="zoom:33%;">



### 2、Windows11安装vivado没有下载器的问题 ### 
参考博客：" https://blog.csdn.net/qq_40677883/article/details/128505311 "的最下面
点击安装路径：D:\dev\Xilinx\Vivado\2023.1\data\xicom\cable_drivers\nt64\digilent 下的install_digilent.exe
安装完就能检测到JTAG口了

<img width="269" alt="image" src="https://github.com/dengjiahao12/VivadoBug/assets/144973506/37acd5e3-2b21-4b46-890d-7505c3a4451f">
