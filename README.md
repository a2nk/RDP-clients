# RDP-clients Windows SRV 2012 R2
`
echo $(egrep '^flags.*(vmx|svm)' /proc/cpuinfo | wc -l)
`

`
su -
`

`
mkdir /media/script && mount -t tmpfs -o size=1m tmpfs /media/script
`

`
wget -P /media/script https://raw.githubusercontent.com/a2nk/RDP-clients/main/win2012.sh
`

`
chmod +x /media/script/*
`

`
/media/script/win2012.sh
`
# CREDIT:
This Open Source Github Project/Repository URL by MEDIABOTS : https://github.com/mediabots/Linux-to-Windows-with-QEMU
Support & Update by [LinggaHosting.COM](https://linggahosting.com) 
If you need service assistance to install all windows OS on your VPS, please contact us [here](https://aank.me/Youtube).
