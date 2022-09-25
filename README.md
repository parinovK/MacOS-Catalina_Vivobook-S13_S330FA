# Awesome Hackintosh Mac OS Catalina on ***Asus Vivobook S13-S330FA***
![MacOS Catalina on Asus Vivobook S13 S330FA](https://github.com/parinovK/MacOS-Catalina_Vivobook-S13_S330FA_Clover/blob/main/MacOS_Catalina.png)
# System specification

    1.Name:           Asus Vivobook S13 S330FA-EY044T
    2.CPU:            Intel Core i3-8145U (2 cores, 4 threads)
    3.GPU:            Intel UHD Graphics 620
    4.External GPU:   NO
    4.Wifi:           Intel Dual Band Wireless-AC 8265 - with bluetooth 
    5.Card Reader:    Realtek_CardReader(RTL8411B_RTS5226_RTS5227)
    7.Audio:          Conexant Audio CX8050
    8.Touchpad:       ELAN1204

# What is work?
1.Wi-Fi (pls download HeliPort for connect to Wi-Fi - https://openintelwireless.github.io/HeliPort/)  
2.Speakers  
3.AirPlay (tested on Samsung TV)  
4.Keyboard & Touchpad  
5.Asus fn-keys (increase/decrease the brightness of the display, speaker volume, keyboard backlights, off touchpad)

# What doesn't work?
1.Bluetooth  
2.Card Reader (Maybe? not tested)  
3.No HID for Asus fn-keys 

# Problem solving
1) if speakers do not work - check clover-arameters and replace "alcid=21" with "alcid=3"  
2) -v for OS startup log
