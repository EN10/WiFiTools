# WiFiTools

A shell script for running different wifi and networking tools

Run
-

    sudo sh menu

Scripts
-

Monitor Mode:   `mon`

    airmon-ng start wlan0
    
Managed Mode:   `man`

    airmon-ng stop wlan0mon
    
Scan AP's:   `scan`

    airodump-ng wlan0mon

Randomise MAC:   `mac`

    ifconfig wlan0 down
    macchanger -r wlan0
    ifconfig wlan0 up