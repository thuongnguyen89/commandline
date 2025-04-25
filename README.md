# To copy data from App mobile
# Pre-Install Android Studio, Install Pixels 7, Root
cd C:\Users\ntthuong\AppData\Local\Android\Sdk\platform-tools
adb devices
adb shell
su
cd /data/data/com.kidsandus.alumnos/app_files
# Copy data to place able to pull from adb
cp *.mp3 /sdcard/Download
Ctrl + C
exit
# Copy from stimulator to PC
C:\Users\ntthuong\AppData\Local\Android\Sdk\platform-tools\adb.exe pull /sdcard/Download/ D:/data
================================================
C:\Users\ntthuong\AppData\Local\Android\Sdk\platform-tools\adb.exe shell
