# RedmiBook14II-i5 1035G1-EFI
> Big Sur 11.5(20G95) OpenCore 0.7.2
> 
> 我已经从Ru.efi关闭CFG LOCK，修改了DVMT为160M--如果没有修改，在Config.plist中修改AppleXcpmCfgLock为True

## 我的配置

| CPU    | i5 1035G1                              |
| ------ | -------------------------------------- |
| 显卡   | MX350(黑苹果中不起作用)                                   |
| 主板   | I/O - 3482 for Intel 495 Series 芯片组   |
| 主硬盘 | 三星MZNLH512HALU-00000（PM881）           |
| 网卡   | AC 9560                                 |
| 声卡   | 英特尔 英特尔智音技术音频控制器              |



1. 已知问题

   - 麦克风不能正常工作
   - 隔空传送、接力不能使用,若想体验，请更换苹果支持的网卡
   - 苹果没有这个显卡的版本，无法使用独显

2. 可以正常工作

   - 无线网（隐藏网络不能使用）
   - 蓝牙
   - 触摸板
   - 亮度显示（开机可能会暗一点）
   - USB内建
   - 睡眠（如果不正常:添加引导参数 `-noDC9`)

3. 小毛病
   -  开机会花屏，一会就好(开机亮度稍暗，睡眠在唤醒就正常）
   -  如果遇到黑屏无法亮屏，请合上盖子等待睡眠后唤醒即可
   - 分辨率保持原样不会有什么问题
   - 开启HIDPI,请开机就睡眠在唤醒即可正常使用（睡眠后 hidpi使用正常）

# 下载

- [EFI](https://github.com/codeMauguin/RedmiBook14II-i5-1035G1-EFI/releases/download/0.7.2%402.0/EFI.zip)


## 此EFI是从Xiaomi Redmibook 16 EFI 原作者[Redmibook 16](https://github.com/Aa244750146/Redmibook-16-Hackintosh.git)修改版	
