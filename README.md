<h1 align="center">Dell-Vostro-3681</h1>
<h3 align="center">戴尔 成就3681 黑苹果 OpenCore 引导配置</h3>
<br>

## Disclaimer / 免责声明

Your warranty is now void. Please do some research if you have any concerns before utilizing my project. I am not responsible for any loss, including but not limited to Kernel Panic, device fail to boot or can not function normally, storage damage or data loss, atomic bombing, World War III, The CK-Class Restructuring Scenario that SCP Foundation can not prevent, and so on.

你的保修将完全失效。如果您有任何疑虑，请在使用我的项目之前先进行一些研究。我对任何损失均不负责，包括但不限于 Kernel Panic、设备无法启动或无法正常工作、硬件损坏或数据丢失、原子弹爆炸、第三次世界大战、SCP 基金会无法避免的 CK 级现实重构等。

### 睡眠无法唤醒（如有解决办法请写[issues](https://github.com/17374363415/dell-vostro-3681-efi/issues)与我联系）（已解决）

## Dell Vostro 3681 Practical Manual / 使用手册 
https://www.dell.com/support/home/zh-cn/product-support/product/vostro-3681-desktop/docs

## Hardware Specifications / 硬件配置

| Specifications | Details |
|:---|:---|
| Computer Model | Dell Vostro 3681 |
| CPU | Intel Core i3-10100 |
| Memory | DDR4 2666 Mhz. 8 GB |
| NVMe SSD | default |
| Integrated Graphics | Intel UHD Graphics 630 |
| Wireless Card | Intel Wireless-AC 3165/9260 |

## Drive sound card / 驱动声卡

1.重启至`恢复模式`     
2.在`终端`中运行
```
csrutil disable
```

```
csrutil authenticated-root disable
```      
3.重启回系统并准备[VoodooHDA.kext](https://sourceforge.net/projects/voodoohda/)和[Hackintool](https://github.com/headkaze/Hackintool)      
4.将VoodooHDA.kext放进L/E中`（访达/系统盘/资源库/extensions）`           
5.打开Hackintool，在工具中选择右下角的`重建缓存`并`修复权限`        
6.到`安全性偏好设置`里面，点击`允许`         
7.重启并享受


## 注意事项
- 请使用主板上的HDMI接口
- 支持的系统请看括号
- 建议使用最新的系统，比较完美

**务必阅读上述资料**


## End / 结语
本项目所提供的EFI支持`macOS Ventura`

欢迎各位积极提交[Issue](https://github.com/17374363415/dell-vostro-3681-efi/issues)和[Pull request](https://github.com/Fu-Yuxuan-hub/ASUS-TUF-GAMING-B460M-PLUS-HACKINTOSH/pullshttps://github.com/17374363415/dell-vostro-3681-efi/pulls)


## 感谢名单
重启解决方案来自[zhtengw](https://github.com/zhtengw)
感谢[杆杆](https://github.com/Fu-Yuxuan-hub)大佬的参与更新与支持
睡眠解决方案来自[freechinanet](https://github.com/freechinanet)
