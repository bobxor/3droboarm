# 3droboarm

#  Dependenies:
For Jetson Nano:

Disable console service:
```
systemctl stop nvgetty
systemctl disable nvgetty
udevadm trigger
```
Change permission of resource /dev/ttyTHS1 for rw access:
```
sudo chmod 777 /dev/ttyTHS1
```
Add pyserial dependency:
```
sudo apt update
sudo apt-get install python3-pip
pip3 install pyserial
```
