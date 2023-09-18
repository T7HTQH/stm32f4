# <center> STM32Keil安装<br>
## 1. 进入[Keil官网](https://www.keil.com/)，点击Product Downloads进入下载界面<br>
![Alt text](picture/image.png)<br>
## 2. 点击MDK-Arm<br>
![Alt text](picture/image-1.png)<br>
## 3. 提交完对应信息后会弹出下载<br>
![Alt text](picture/image-2.png)<br>
## 4. 下载完之后直接双击打开就行了<br>
![Alt text](picture/image-3.png)
## 5.一路next，该agree的agree就好了，直到进入路径选择界面。如果有安装过51且没有卸载的话这里会默认使用keil的目录，打开Code目录看一眼，确保keil确实确实在这个文件里。如果没有装过keil就修改一下安装目录再next<br>
![Alt text](picture/image-4.png)<br>
## 6.接下来会让你再填一遍信息，随便填<br>
![Alt text](picture/image-5.png)<br>
## 7.安装完之后keil的快捷方式就会出现在桌面<br>
## 8.右键以管理员身份打开keil，点击左上角的File，点击Liscense Manager
![Alt text](picture/image-6.png)
## 9.把那一串CID复制下来，下个keil的注册机，不用拘泥于2022还是2023~~网上有，直接搜就行了，或者找我要~~
![Alt text](picture/image-7.png)
## 10.打开keil的注册机，记得关闭声音，把CID输入进去，把Target改成ARM，点击Generate会在下面一栏生成注册码，把那一串注册码复制下来
![Alt text](picture/image-8.png)
## 11.回到keil，把复制下来的注册码v到New License Code那一栏，点击 Add Lic就行了。安装完之后重新启动keil
![Alt text](picture/image-9.png)
## 12.如果不出意外的话再次打开会出现这个界面。点击OK
![Alt text](picture/image-10.png)
## 13. 在左边的一栏里找到这个
![Alt text](picture/image-11.png)
## 14. 点击前面的加号展开，找到对应的芯片型号展开，以STM32F401CBUX为例，展开到最后一级，点击芯片图标，会在右侧出现一个Device Specific的目录，点击目录下的Install，等待下方进度条跑完就可以关掉这个界面。
![Alt text](picture/image-12.png)
## 15. 由于keil5.37版本以后不再自带ARM5编译器，需要在网上找到编译器，下载下来最终是一个压缩包
![Alt text](picture/image-13.png)
## 16. 解压，在文件里找到名为setup.exe的文件，双击打开
![Alt text](picture/image-14.png)
## 17.一直next，直到
![Alt text](picture/image-15.png)
## 需要点击 Browse把安装路径更改至keilv5路径下的ARM文件内，之后等待安装完成。
## 17. 打开keil，随便选一个芯片新建一个工程，
![Alt text](picture/image-16.png)
## 随便起个名字点保存
![Alt text](picture/image-17.png)
## 随便选择一个芯片展开至最底层，点击具体芯片，点击OK建立工程 
![Alt text](picture/image-18.png)
## 会弹出来一个窗口，这个窗口暂时用不到，直接cancel 
![Alt text](picture/image-19.png)
## 点击上方“品”字形的按钮
![Alt text](picture/image-20.png)
## 点击folders/Esteension 选项卡，再点击地址栏后面的三个点，
![Alt text](picture/image-21.png)
## 点击下方ADD开头的按钮，进入keilv5/ARM目录下，点击确定，之后点击close按钮 
![Alt text](picture/image-22.png)
## 点击close后会回到这个界面，点击OK（不要直接X掉这个界面，点击OK才会保存）
![Alt text](picture/image-23.png)
## 之后点击魔术棒按钮，在右侧的ARM Compiler中应该能找到V5版本的Compiiler
![Alt text](picture/image-24.png)