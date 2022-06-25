# code-notes
1. root
```
sudo -s
```
2. Check ssh (same network)
```
sudo nmap -sS -p 22 192.168.0.0/24 | grep report
```
3. Check camera
```
v4l2-ctl --list-devices
```
4. Change mount point. (for example, from sd-card to ssd)
[This blog works](https://help.ubuntu.com/community/Partitioning/Home/Moving)
5. Install mediapipe on arm-chip ubuntu(jetson, raspberry pi...)
[This works for jetson](https://learningsky.io/install-mediapipe-089-on-nvidia-jetson-nano/)
