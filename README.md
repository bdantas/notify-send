# notify-send
Send notifications from shell scripts or the command line without a notification server

# What you need
0. GNU/Linux operating system and this script
1. **dzen2**
2. If desired, customize "user variables" at top of script

# Installation
```
$ sudo apt install dzen2
$ cd /tmp
$ wget https://github.com/bdantas/notify-send/archive/master.zip
$ unzip master.zip
$ sudo cp ./notify-send-master/notify-send /usr/local/bin/
$ sudo chmod a+x /usr/local/bin/notify-send
```
Note: If your operating system is not Debian-like, adjust the first step

# Usage
Run the script without any arguments for syntax and example usage
