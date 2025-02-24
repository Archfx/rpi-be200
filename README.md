## Install Drivers on your Raspberry Pi

Follow the below commands

```shell
git clone --recurse-submodules https://github.com/Archfx/rpi-be200
sudo cp rpi-be200/be200/iwl* /lib/firmware/
sudo reboot
```
> Tested on CM4 and Pi5 With PCIE BE200 WiFi cards