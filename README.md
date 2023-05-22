# ADB-Firmware-extraction
Pull firmware from android based devices. (Smart android TV, Android box, Android watch etc)
adb connect <IP>
adb shell
su
cat /proc/partitions
cd /dev/block
dd if=/dev/block/boot of=/sdcard/boot.img   // copy each partitons (recovery, system, bootloader, misc etc...)
adb pull /sdcard/boot.img


