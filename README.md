# dev
Miscellaneous configs, script and utils for my DEV environment

* latexthat.sh <file.tex> triple-compile file.tex to get bibliography and
in-document references straight, then clean the destination folder of scruff
files and finally open the resulting PDF with evince
* backup.py picks files of predefined extensions in predefined directories
(and their subdirectories), zips them and finally sends the zipped archive
to your gmail account
* cheatsheet.html is yet another vim / xmonad / shell cheatsheet
* setup.sh adjust my laptop xmonad configuration to an external monitor

## network manager on debian

```
$ # list wifi networks:
$ nmcli dev wifi list
$ # connect to a wifi network
$ nmcli dev wifi connect <NETWORK NAME/SSID> password <PASSWORD>
$ # show status:
$ nmcli c show
$ # delete an existing connection
$ nmcli connection delete <NETWORK NAME/SSID>
$ # restart network manager
$ sudo service network-manager restart
```

## launching VPN

```
$ cd ~/ipvanish
$ sudo openvpn --config desired_config.ovpn
```

## changing keyboard layout

```
$ setxkbmap fr
$ setxkbmap us
```

