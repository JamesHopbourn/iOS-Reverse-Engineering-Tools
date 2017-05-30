# iOS Security Command Tools

## Usage for iOS

First,installing required software in Cydia.Install "APT 0.6 Transitional" and “OpenSSH”.If you are iOS 10.2 that OpenSSH is default installed,so don't install OpenSSH again.

Second,SSH to your device.
Installation:

<pre><code>apt-get update</code></pre>

### iOS 7.1.2
<pre><code>apt-get install com.rheard.reveal-loader com.tigisoftware.filza com.saurik.afc2d bigbosshackertools com.codehex.whiteterminal com.saurik.substrate.safemode adv-cmds curl cycript odcctools developer-cmds dpkg file file-cmds findutils gawk git grep ldid less mobilesubstrate python nano netcat network-cmds sed shell-cmds sqlite3 syslogd system-cmds tcpdump top uikittools unrar unzip wget whois zip PreferenceLoader ldid</code></pre>

### iOS 8 and gen
<pre><code>apt-get install com.shmoopillc.flexible com.rheard.reveal-loader com.tigisoftware.filza com.saurik.afc2d bigbosshackertools com.fuyuchi.flex org.coolstar.iostoolchain com.autopear.installipa com.unlimapps.uaupdatetools  com.codehex.whiteterminal com.saurik.substrate.safemode adv-cmds curl cycript odcctools developer-cmds dpkg file file-cmds findutils gawk git grep ldid less mobilesubstrate python nano netcat network-cmds sed shell-cmds sqlite3 syslogd system-cmds tcpdump top uikittools unrar unzip wget whois zip make ldid PreferenceLoader</code></pre>

Third,download tar compress.

<pre><code>wget https://github.com/iOSteveReagan/iOS-Security-command-tools/raw/master/command.tar --no-check-certificate

mv command.tar /

cd /

tar -zxvf /command.tar </code></pre>

Done.

## iOS Store Apps Recommand
	- Surge
	- Workflow


## Usage for OS X
Install "Command Line Tools for Xcode"
<pre><code>xcode-select --install</code></pre>

Install "Homebrew"
<pre><code>/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew cask install hopper-disassembler reveal ifunbox imazing ios-app-signer burp-suite charles google-chrome beyond-compare impactor sublime-text2 paste xampp github-desktop surge alfred wireshark iterm2</code></pre>



# iOS-Reverse-Engineering-Tools
