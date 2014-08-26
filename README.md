joxer/raspberry-pi-joxer-kernel
==========

Linux kernel release 3.12.26+ for the Raspberry Pi.

Install
-------

```text
sudo REPO_URI=https://github.com/joxer/raspberry-pi-joxer-kernel rpi-update
```




Sources
-------
* [raspberrypi/tools](https://github.com/raspberrypi/tools/archive/472c649d4d631c6f6f043a814a08ce7013afe4e5.tar.gz)
* [raspberrypi/firmware](https://github.com/raspberrypi/firmware/archive/6eda68af0e3f0897c5b72a3d44003f16ecdc9110.tar.gz)
* [raspberrypi/linux](https://github.com/raspberrypi/linux/archive/c37ed3586fc8b14f3dd21fa830952489e21bfa22.tar.gz)


Patches
--------
None

Kernel config
-------------
Default config: bcmrpi_defconfig



Added:
```text
88EU_AP_MODE=y
88EU_P2P=y
R8188EU=m
```


<p align="center">Built with <a href="https://github.com/notro/rpi-build/wiki">rpi-build</a></p>
