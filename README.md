# Termux-ADB


Install ADB & FastBoot Tools in Termux!
For devices with ARM or ARM64 processors only!

How to install
Silent installation:
Copy and paste the following command in Termux to silently install Tools:
apt update > /dev/null 2>&1 && apt --assume-yes install wget > /dev/null 2>&1 && wget https://github.com/thatshacker/Termux-ADB/raw/master/InstallTools.sh -q && bash InstallTools.sh
Common installation:
Copy and paste the following command in Termux to install Tools with logs output:
apt update && apt install wget && wget https://github.com/thatshacker/Termux-ADB/raw/master/InstallTools.sh && bash InstallTools.sh
How to uninstall
Silent uninstallation:
Copy and paste the following command in Termux to silently remove Tools:
apt update > /dev/null 2>&1 && apt --assume-yes install wget > /dev/null 2>&1 && wget https://github.com/thatshacker/Termux-ADB/raw/master/RemoveTools.sh -q && bash RemoveTools.sh
Common uninstallation:
Copy and paste the following command in Termux to remove Tools with logs output:
apt update && apt install wget && wget https://github.com/thatshacker/Termux-ADB/raw/master/RemoveTools.sh && bash RemoveTools.sh
Credits
thatshacker - Scripts development.

.
