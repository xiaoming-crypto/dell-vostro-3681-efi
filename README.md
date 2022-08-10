# dell-vostro-3681-efi
此为黑苹果efi分享，持续更新
支持自带的Wi-Fi和蓝牙
睡眠无法唤醒（如有解决办法请写issues与我联系）

使用万能声卡驱动方法如下：
首先是先去恢复模式把sip给关了
在恢复模式（recovery）下终端输入
csrutil disable
csrutil authenticated-root disable
后回车
准备VoodooHDA.kext（https://sourceforge.net/projects/voodoohda/）和Hackintool（https://github.com/headkaze/Hackintool）
然后把VoodooHDA.kext拖进去L/E中（访达/macOS系统盘/资源库/extensions）
然后打开Hackintool，在工具中选择右下角的重建缓存并修复权限
在重建完后，应该就会弹出一个提示，这样就代表已经成功打进去了
然后点击去到安全性偏好设置里面，点击下面的允许
重启之后，不出意外就已经驱动成功了

请使用主板上的HDMI接口
支持的系统请看括号
建议使用最新的Monterey，比较完美

感谢名单
重启解决方案来自（https://github.com/zhtengw）
感谢杆杆大佬的参与更新与支持（https://github.com/Fu-Yuxuan-hub）
