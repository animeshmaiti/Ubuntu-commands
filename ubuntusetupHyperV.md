### To blacklist the Hyper-V modules, you can use the following command to edit the blacklist configuration file:
```cmd
sudo nano /etc/modprobe.d/blacklist.conf
```
```cmd
blacklist hyperv_fb
blacklist hv_vmbus
blacklist hv_storvsc
blacklist hv_blkvsc
blacklist hv_utils
blacklist hv_netvsc 
```