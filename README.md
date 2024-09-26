## Tank 03 Mini PC information repository

![Tank](/Images/tank.png) 

This repository was created to gather all information about the Tank 03 Mini PC sold by Acemagic and Chatreey.

1. [Specs](#specs)
2. [How to open the device](#open)
3. [More pictures](#pics)
4. [How to reset bios](#bios)
5. [Drivers / Bios Warning](#drivers)

## <a href="#specs" id="specs">Specs</a>

The physical size is 17x17x17 cm (WxLxH)

This Mini PC comes in 2 CPU flavours, the Intel i7 12700H and the i9 12900H both sporting 14 cores / 20 threads (6 Performance + 8 Efficient cores) at 45W TDP.

![CPU](/Images/cpu_i12700h.png)

Graphic's card wise, all models come with Intel® Iris® Xe Graphics thanks to the Intel CPU and a second notebook graphic card from Nvidia, in 3 different models: RTX3050 (?) / RTX3070 (115W - Code Name: GA 104) / RTX3080 (?)

Several VRAM sizes where offered, but now seems only the 16GB versions are sold.

![CPU](/Images/gpu_rtx3070.gif)


It has 2x M2 2280 for Nvme or SSD + 1x M2 2230 (used by the Wifi Card).


(more to be added later)


## <a href="#open" id="open">How to open the device</a>

The cube has 8 screws hidden under the triangle pads on each of it's corner.  
Simply remove the pads and unscrew.

![CPU](/Images/screws.jpg)

The top lid has the wifi/BT antennas attached to it, so be careful when pulling it!.

![CPU](/Images/wifi.jpg)

Unscrew all 4 standoffs, and remove the metal bracket that covers the GPU cooler. The side walls of the cube will be released, giving access to the interior.

![CPU](/Images/standoff.jpg)

## <a href="#pics" id="pics">More pics</a>

GPU 80mm cooler fan, front view (behind the dial).

![CPU](/Images/gpu_cooler.jpg)

PCie GPU Slot (possible room for updates by replacing the graphics card?)

![CPU](/Images/pcie_gpuslot.jpg)

The 3 M2 slots and the board revision

![CPU](/Images/m2.jpg)  
  


## <a href="#bios" id="bios">How to reset bios</a>

If you are like me and scr€wed the bios into a unbootable state, you will find out there is no bios reset button or power up sequence that erases it back to default.

But there is a way to reset it :) !  

* Please remember first boots take a long time (in one case it tooks 3 minutes!), do not power off the device for at least 5 minutes. *

__BIOS RESET PROCEDURE:__

1. Power off device, remove mains plug.
2. Open device top lid and unscrew the standoff to remove the bracked that holds the side walls.
3. Disconnect the built in clock battery using a screw driver
4. Insert mains plug, power device on, and wait (really wait a few minutes)
5. Bios should be back to default.
6. Power off device again, remove mains plug
7. Reconnect the battery plug into position
8. Close lid and repeat step 4 (with faster boot now)

Battery plug location, viewed from the top (battery is a yellow component taped inside the front panel.


![CPU](/Images/battery.jpg)


## <a href="#drivers" id="drivers">Drivers</a>

Manufacturer tutorials and drivers (more recent than mine): https://www.chatreey.com/support/tank-model-mini-pc-drivers/

CUSTOM NVIDIA DRIVERS for Chinese NVIDIA LAPTOP CARDS, always up-to-date (1 or 2 versions behind latest nvidia): [FrankenDriver](https://github.com/arutar/FrankenDriver)

Drivers collected by me in 2023 (size is too big for Github), please retrieve them from: [MEGA (Size: 820Mb)](https://mega.nz/folder/db9yiAJD#0lUH8jqL39iFSJFptN68GA)


## WARNING ##

Flashing a new bios, will make windows deactivated after reboot, the "I changed my hardware" option will not work. 

Only solution that worked for me was to reinstall Windows 11!

