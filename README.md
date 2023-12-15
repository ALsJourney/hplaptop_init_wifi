# hplaptop_init_wifi
# hplaptop_init_wifi

Tested on HP 255 G10 With AMD Ryzen 5 7530U

## Run it
```bash
sudo make
sudo make install
# unload the kernel module
sudo modprobe -rv rtw_8852be
# load the kernel module
sudo modprobe -v rtw_8852be
```
