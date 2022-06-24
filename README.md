# code-notes
1. Check ssh (same network)
```
sudo nmap -sS -p 22 192.168.0.0/24 | grep report
```
2. Check camera
```
v4l2-ctl --list-devices
```
3. Change mount point. (for example, from sd-card to ssd)
[This blog works](https://help.ubuntu.com/community/Partitioning/Home/Moving)
4. Install mediapipe on arm-chip ubuntu(jetson, raspberry pi...)
[This works for jetson](https://learningsky.io/install-mediapipe-089-on-nvidia-jetson-nano/)
