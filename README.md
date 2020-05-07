# macOS-Mojave-Inspiron-5547

![img](https://s1.ax1x.com/2020/05/07/YmfznI.png)


## 电脑配置: 
  - Intel (R) Core (TM) i5-4210U 
  - 无线网卡：AC3160
  - Ethernet Realtek RTL 8106E （这个不太确定，但是以上的驱动能有线上网）
  - Intel HD4400
  - AMD R7 265（不确定是260还是265，但反正装不上驱动，无所谓）
  
 ## 完美适配:
  - 声卡可用，耳机、外放均可，可调节声音
  - USB （没有测试3.0速度，但三个口子都可以用）
  - 电池电量可显示，插上、拔下电源均有响应
  - 睡眠、关机和重启适配
  - 有线网络可上网
  - 可调节显示屏亮度
  -触摸板日常可用
  
## 未测试: 
  - 触摸板多手势懒得测试，用鼠标
  
  ## 未适配: 
  - AMD 显卡没有相应驱动
  - 无线和蓝牙没有驱动，不过我的电脑的无线被我拆机时拔断了，本来就没用
  - Caps Lock，即大小写切换键不灵敏，不知道是我电脑问题还是系统问题
  - 重启是有概率假死，这边建议要么关机，要么待机，别重启！
   
本配置主要从一位俄罗斯老哥那里抄的，有线上网则是黑果小兵的镜像中自带的，我都统一挑拣放上面了，制作完启动U盘后，把上面的EFI文件夹覆盖U盘里的EFI即可。
Extension则是要装完系统后自行安装，请自行百度kext wizard及使用教程。

这边放一下使用的MAC镜像文件，是黑果小兵收集的。开始先测试了10.15.3的镜像，卡在了apfs_module_start:1683。后下的是10.14.2的镜像，完美适配。
https://mirrors.dtops.cc/iso/MacOS/daliansky_macos/10.14/

再放一篇我所参考的教程，依旧感谢黑果小兵。
https://blog.daliansky.net/MacOS-installation-tutorial-XiaoMi-Pro-installation-process-records.html






