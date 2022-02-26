# RDP-clients Windows SRV 2012 R2
```markdown
echo $(egrep '^flags.*(vmx|svm)' /proc/cpuinfo | wc -l)
```
```markdown
su -
```
```markdown
mkdir /media/script && mount -t tmpfs -o size=1m tmpfs /media/script
```
```markdown
wget -P /media/script https://raw.githubusercontent.com/a2nk/RDP-clients/main/win2012.sh
chmod +x /media/script/*
/media/script/win2012.sh
```
