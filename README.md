# SwiftNode-Installer
### Bash installer for swiftnode on Linux

#### This shell script comes with 4 cronjobs: 
1. Make sure the daemon is always running: `makerun.sh`
2. Make sure the daemon is never stuck: `checkdaemon.sh`
3. Make sure swiftcash is always up-to-date: `upgrade.sh`
4. Clear the log file every other day: `clearlog.sh`

#### On the client-side, add the following line to swiftnode.conf

`SN01 VPS-IP-ADDRESS:8544 SWIFTNODE-GEN-KEY COLLATERAL-TX-ID COLLATERAL-TX-OUTPUT`

#### Login to your vps as root, download the install.sh file and then run it, enter the SwiftNodeKey you got above when asked for SwiftNode GenKey:
```
wget https://raw.githack.com/swiftcashproject/swiftnode-installer/master/install.sh -O install.sh
bash ./install.sh
```

#### Run the qt wallet, go to SwiftNodes tab, choose your node and click "Start alias" at the bottom.

#### You're good to go now. GO $SWIFT! https://swiftcash.cc
