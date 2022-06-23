# code-notes
1. check ssh (same network)
```
sudo nmap -sS -p 22 192.168.0.0/24 | grep report
```
2. check camera
```
v4l2-ctl --list-devices
```
