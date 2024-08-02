# Android Debloater

## about
- This is essentially an android debloater script that I wrote for my huawei machine. 
- It targets all of google apps installed in it as well as other bloatware and spyware like huawei apps, meta apps, even the microsoft swiftkey keyboard.	
## installation
Requires adb.
on debian:
```
sudo apt install adb
```
## usage
Turn on usb debugging from developer mode. 
Then clone this repo if you havent already (just copy the content 
from debloat.sh and paste in a new file with .sh extension). Give the file 
executable rights if required. Then run it.

``` 
git clone https://github.com/ioresolution/android-debloater
cd android-debloater 
chmod +x debloat.sh
./debloat.sh
```

