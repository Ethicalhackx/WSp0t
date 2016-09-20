# WSp0t
A tool that creates and starts your hotspot without worries! 

![Alt text](http://i68.tinypic.com/2dj734i.jpg "Screenshot")

# Installation
```
git clone https://github.com/Biprodeep/WSp0t

cd WSp0t

sudo ./Setup_Debian
```
# Use
```
sudo wsp0t
```
# Note
Its a pretty useful tool for you if you want a quick hotspot!
This project uses the famous https://github.com/oblique/create_ap
This tool actually atuomates all troubles of the create_ap script and manages all problems itself.

# Side_Talk
For now this setup is for users with distributions that have Debian base.
For arch users, don't run the setup file just do this.
```
git clone https://github.com/Biprodeep/WSp0t
cd WSp0t
sudo pacman -S util-linux procps hostapd iproute2 iw haveged dnsmasq iptables create_ap; 
cp wsp0t /usr/bin
cp wooo /usr/bin
```
Now run the script! :)

./Enjoy
