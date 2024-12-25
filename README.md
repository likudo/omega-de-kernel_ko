#EZ-FLASH  Omega Definitive Edition Kernel

--------------------------------------
This fork is Based on https://github.com/multi-vitamin/omega-de-kernel_korean

### Korean font

Galmuri11 (https://galmuri.quiple.dev)

### Differences from Original Kernel
1. Chinese changed to Korean
2. Corrected a broken first word error when Filename_loop function with long Korean file name
--------------------------------------

### How to build 

    1.We use devkitARM_r53, you can use the current version or newer.
    2.Set the following environment variables in system, or modify the value in build.bat, based on your installation path
 
        PATH,DEVKITARM,DEVKITPRO,LIBGBA

    3.Double click on build.bat under windows. If it goes well, you will get ezkernelnew.gba
    4.Double click on  Link_kernel_image.exe link the ezkernelnew.gba and image.bin to ezkernelnew.bin, that is the omegaDE kernel upgrade file
