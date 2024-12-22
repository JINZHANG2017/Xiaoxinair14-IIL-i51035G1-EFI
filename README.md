# Xiaoxinair14-IIL-i51035G1-EFI
小新air14IIL黑苹果EFI分享
# 联想小新air14IIL 黑苹果EFI(EFI文件在release处下载）
## 需要自行更新三码
## EFI来自QQ群，非本人原创，此处仅做搬运和分享，希望能帮助到有需要的朋友，少走弯路
## 本人仅做分享，无任何盈利行为，也希望看到的朋友不要把别人的成果拿去盈利
## 目前经本人测试所有硬件工作良好，无重启现象，合盖休眠能正常唤醒，蓝牙摄像头之类的都正常，比较完美。风扇声音安静很多
## 再次感谢群友无私分享的EFI，如有侵权，请联系
##  此版本为macos13.1版本EFI，如果使用macos12版本，需要自行替换无线网卡驱动，亲测12.7.6版本正常使用
##  如果是三星硬盘，需要更换
##  需要进入隐藏bios修改部分设置，具体操作如下，别的项目copy过来的，大佬给的步骤，我就不做修改了，自行查找翻译
##  再次感谢所有大佬的无私分享
To activate the Debug Bios;
Enter BIOS → disable OneKeyBattery → save and exit. Poweroff the laptop. Power button to turn on → F2 to enter the normal BIOS → Power button to turn off → then press, moving fast, the following keys in sequence
 F1 → 1 → Q → A → Z
 
 F2 → 2 → W → S → X
 
 F3 → 3 → E → D → C
 
 F4 → 4 → R → F → V
 
 F5 → 5 → T → G → B
 
 F6 → 6 → Y → H → N
Turn on the power button → F2 enters the hidden Debug BIOS.
Then go to;
Advanced → Power & Performance → CPU-Power Management Control → CPU Lock Configuration → CFG Lock → Disabled

Then go to;
Advanced → System Agent (SA) Configuration → Graphic Configuration → DVMT Pre-Allocated Selection → DVMT Pre-Allocated → Set to 160MB

save and exit.
