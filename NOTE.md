# Installation
## Clone Git
```git clone http://github.com/zrafa/xinu-x86-gui```

## Prepare Environment
for ```make```:  
```
sudo apt-get install gawk
sudo apt-get install bison
sudo apt-get install flex
```

for ```make run-qemu```:  
```
sudo apt-get install xorriso
sudo apt-get install mtools
sudo apt-get install qemu-system-x86
```

## Make ISO file
```
cd xinu-x86-gui/compile
make clean
make
make run-qemu
```






ISO img for boot (on other plantform)