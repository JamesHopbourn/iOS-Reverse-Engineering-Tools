# iOS Security command tools

## Usage

First,installing required software in Cydia.Install "APT 0.6 Transitional" and OpenSSH.If you are iOS 10.2 that OpenSSH is default install,so don't install OpenSSH again.

Second,SSH to your device.
Installation
====================================
apt-get update
### iOS 7.1.2
apt-get install com.fuyuchi.flex2 com.rheard.reveal-loader eu.heinelt.ifile com.tigisoftware.filza com.saurik.afc2d net.limneos.classdump-dyld bigbosshackertools com.fuyuchi.flex org.coolstar.iostoolchain com.autopear.installipa com.unlimapps.uaupdatetools  com.codehex.whiteterminal com.saurik.substrate.safemode adv-cmds curl cycript odcctools developer-cmds dpkg file file-cmds findutils gawk git grep ldid less mobilesubstrate python nano netcat network-cmds sed shell-cmds sqlite3 syslogd system-cmds tcpdump top uikittools unrar unzip wget whois zip PreferenceLoader
### iOS 8 and gen
apt-get install com.shmoopillc.flexible com.rheard.reveal-loader eu.heinelt.ifile com.tigisoftware.filza com.saurik.afc2d net.limneos.classdump-dyld bigbosshackertools com.fuyuchi.flex org.coolstar.iostoolchain com.autopear.installipa com.unlimapps.uaupdatetools  com.codehex.whiteterminal com.saurik.substrate.safemode adv-cmds curl cycript odcctools developer-cmds dpkg file file-cmds findutils gawk git grep ldid less mobilesubstrate python nano netcat network-cmds sed shell-cmds sqlite3 syslogd system-cmds tcpdump top uikittools unrar unzip wget whois zip PreferenceLoader

Third,download tar compress.

wget -P / https://github.com/iOSteveReagan/iOS-Security-command-tools/raw/master/command.tar --no-check-certificate

tar -zxvf /command.tar 

Done.