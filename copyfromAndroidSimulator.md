1. To copy data from App mobile
2. Pre-Install Android Studio, Install Pixels 7, Root
3. Use super user
   
`cd C:\Users\ntthuong\AppData\Local\Android\Sdk\platform-tools`

`adb devices`

`adb shell`
or
`C:\Users\ntthuong\AppData\Local\Android\Sdk\platform-tools\adb.exe shell`

`su`

`cd /data/data/com.kidsandus.alumnos/app_files`

5. Copy data to place able to pull from adb

`cp *.mp3 /sdcard/Download`

Ctrl + C

`exit`

7. Copy from stimulator to PC

`C:\Users\ntthuong\AppData\Local\Android\Sdk\platform-tools\adb.exe pull /sdcard/Download/ D:/data`
