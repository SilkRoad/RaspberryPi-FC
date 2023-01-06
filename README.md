# RaspberryPi FC-树莓派家庭游戏机
## 所需硬件
- 树莓派2B
- SD卡及读卡器
- 树莓派屏幕或电视机屏幕
- HDMI视频线
- 树莓派电源线
- 游戏手柄（北通）
- 电脑

## 安装
1. 下载[Retropie](https://retropie.org.uk/download/)镜像系统；
2. 下载[Raspberry Pi Imager](https://www.raspberrypi.com/software/)镜像软件并安装好；
3. 将SD卡插入读卡器，并插入电脑中；
4. 启动Raspberry Pi Imager镜像软件，选择第1步下载好的Retropie镜像系统，选择好要烧录的SD卡，点击write，等待烧录好即可；
5. 将写好系统的SD卡插入树莓派中，并上电启动树莓派；
6. 接入屏幕、接入手柄，按照自己的手柄类型进行按键的设置；
7. 至此，安装完成。

## 准备游戏文件
1. 将U盘格式化为 FAT32 or exFAT；
2. 在U盘中创建一个名为 `retropie`的文件夹；
3. 将该U盘插入树莓派中，并等待几分钟；
4. 从树莓派中取下U盘，并将其插入电脑中；
5. 将游戏文件考入到`retropie/roms/$CONSOLE` 目录中即可，例如`retropie/roms/NES`；
6. 将U盘插入树莓派中，游戏ROMs将自动拷入到树莓派Retropie系统中；
7. 移除U盘；
8. 重启游戏模拟器（`> Quit > Restart EmulationStation`），即可看到游戏。 
