compile this code - g++ screensaver.cpp -o screensaver -lsfml-graphics -lsfml-window -lsfml-system -lX11
than ./screensaver
if you dont have screensaver on your computer install it first it calls xscreensaver
**if you want to set as a screensaver on your linux system follow this steps**
1.sudo cp screensaver /usr/local/bin/screensaver
(in terminal type sudo cp name of your programe /copy this path from your file system/programe name hit enter to copy)
2.nano ~/.xscreensaver (open configuaration file)
3.below of **programs** "my custom screensaver"  screensaver \n\ CTRL+O to save it
4.sudo nano /usr/share/xscreensaver/config/screensaver.xml(**To write description of this programe create xml file)**
5.save it


