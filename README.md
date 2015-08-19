# Surface Pro 3 Linux Kernel 3.19.0-27.29

This is a custom kernel for the Surface Pro 3.
The kernel used was 3.19.0-27.29 but the files are named 3.19.0-27.31. This is solely for the purpose of avoiding the kernele being overwritten by a software update

The Kernel includes the patches from 
https://github.com/matthewwardrop/linux-surfacepro3.git
https://github.com/neoreeps/surface-pro-3

* buttons.patch
* cam.patch
* cahnge-default-console-loglevel.patch
* battery.patch
* wakeup.patch

## Installation
Open the terminal and navigate to your home folder  
``` cd ~ ```  

Clone the repo

``` git clone https://github.com/CarlosRoque/surface-pro-3-linux-kernel-3.19.0-27.29.git```

Navigate to the new directory and install the kernel

```cd surface-pro-3-linux-kernel-3.19.0-27.29```  

```sudo dpkg -i linux-headers* linux-image*```

restart
