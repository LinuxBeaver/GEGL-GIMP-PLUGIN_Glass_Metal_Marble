If you found this plugin in the top twenty something plugins download. Go to the release section on Github to find the presets file it needs.

# Glass Metallic Marble Text GEGL Gimp Plugin
GEGL plugin that strongly benefits from built in presets. User will have to follow one special direction to get built in presets.
![image](https://github.com/LinuxBeaver/Glass_Metallic_Marble_Text_GEGL_Gimp_Plugin/assets/78667207/dba6fa67-80ea-422d-b016-4d46cd357b06)


## SPECIAL LOCATION TO PUT GimpGegl-lb-gmm-config.settings -THIS IS NOT WHERE THE PLUGIN GOES
**THIS IS THE PRESET LIST**
*if you have 2.99 replace 2.10 with 2.99 or 3.0 when Gimp 3 is released.

**Windows Normal**  
C:\Users\USERNAME\AppData\Roaming\GIMP\2.10\filters

**Linux Normal**
                        
/home/USERNAME/.config/GIMP/2.10/filters

**Linux Flatpak and Chrome book**         
/home/USERNAME/.var/app/org.gimp.GIMP/config/GIMP/2.10/filters




## OS specific location to put GEGL Filter binaries 

**Windows**

C:\Users\USERNAME\AppData\Local\gegl-0.4\plug-ins
 
**Linux**
 
 /home/(USERNAME)/.local/share/gegl-0.4/plug-ins
 
**Linux (Flatpak)**
 
 /home/(USERNAME)/.var/app/org.gimp.GIMP/data/gegl-0.4/plug-ins


## Compiling and Installing
Linux

To compile and install you will need the GEGL header files (libgegl-dev on Debian based distributions or gegl on Arch Linux) and meson (meson on most distributions).

meson setup --buildtype=release build
ninja -C build


If you have an older version of gegl you may need to copy to ~/.local/share/gegl-0.3/plug-ins instead (on Ubuntu 18.04 for example).
Windows

The easiest way to compile this project on Windows is by using msys2. Download and install it from here: https://www.msys2.org/

Open a msys2 terminal with C:\msys64\mingw64.exe. Run the following to install required build dependencies:

pacman --noconfirm -S base-devel mingw-w64-x86_64-toolchain mingw-w64-x86_64-meson mingw-w64-x86_64-gegl

Then build the same way you would on Linux:

meson setup --buildtype=release build
ninja -C build

## More previews of this based Gimp plugin here

![image](https://github.com/LinuxBeaver/Glass_Metallic_Marble_Text_GEGL_Gimp_Plugin/assets/78667207/9360d991-453f-4847-b0d1-3aabeb963829)


![image](https://github.com/LinuxBeaver/Glass_Metallic_Marble_Text_GEGL_Gimp_Plugin/assets/78667207/80f24b26-69a4-4625-ae41-cba1e44030f5)

![image](https://github.com/LinuxBeaver/Glass_Metallic_Marble_Text_GEGL_Gimp_Plugin/assets/78667207/503f4a30-c443-4818-9cea-e33d5529cf83)

![image](https://github.com/LinuxBeaver/Glass_Metallic_Marble_Text_GEGL_Gimp_Plugin/assets/78667207/b2b4eb50-66d0-450e-ad41-1155039bfcb8)

![image](https://github.com/LinuxBeaver/Glass_Metallic_Marble_Text_GEGL_Gimp_Plugin/assets/78667207/ff58a225-9eda-496b-be75-0a0ed2f60eb1)

![image](https://github.com/LinuxBeaver/Glass_Metallic_Marble_Text_GEGL_Gimp_Plugin/assets/78667207/0c768cc8-1056-4834-a39b-cc256e545b17)

![image](https://github.com/LinuxBeaver/Glass_Metallic_Marble_Text_GEGL_Gimp_Plugin/assets/78667207/7db54acc-754b-4fad-ac48-c6debb95779e)



