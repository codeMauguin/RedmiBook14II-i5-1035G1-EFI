# RedmiBook14II-i5 1035G1-EFI
> Big Sur 11.5(20G71) OpenCore 0.7.2
> 
> 我已经从Ru.efi关闭CFG LOCK，修改了DVMT为96M--如果没有修改，在Config.plist中修改AppleXcpmCfgLock为True

1. 已知问题

   - 麦克风不能正常工作
   - 隔空传送、接力不能使用
   - 睡眠不是很正常（自己摸索吧）
   - 键盘中（ctrl，win，alt）乱了，可以自己调
   - 独显不能工作

2. 可以正常工作

   - 无线网（隐藏网络不能使用）
   - 蓝牙
   - 触摸板
   - 亮度显示（开机可能会暗一点）
   - USB内建

3. 小毛病

   -  开机会花屏，一会就好

   - 分辨率保持原样不会有什么问题，开启HIDPI的话容易切屏花屏，移动窗口花屏现象

     



## 此EFI是从黑果小兵的EFI仓库中Xiaomi Redmibook 16修改版	
