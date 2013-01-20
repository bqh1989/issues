## Ubuntu 12.04之找不到qemu命令

得解决方案：    
使用qemu-system-i386或qemu-system-x86_64指令替换qemu指令。如果你想还是使用qemu指令，可以建立一条软链接：    
```
sudo ln -s /usr/bin/qemu-system-i386 /usr/bin/qemu
```
