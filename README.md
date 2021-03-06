kernel-lenovo-x230
==================

Highly optimised Kernels for Ubuntu and generic config for the lenovo thinkpad x230 with the following mods 

PF kernel fork (https://pf.natalenko.name/) 
-------------------------------------------
* mainline update 
* ck patchset with BFS 
* BFQ I/O scheduler 
* TuxOnIce 
* UKSM 

Other Patches
-------------
* Intel Haswell PState Driver Patches 
* GCC 4.8 arch based optimisations 

Options
-------
* Config and modules optimised for hardware and most commonly used devices 
* BFS enabled 1000 HZ RT PREEMPT SMP x86_64 Kernel 
* LZ4 compression (3.11) and LZO (3.10) make sure you have required libs and dev files installed (liblz4 or liblzo2)
* Multiple hardware crypto and compression options switched on 
* AVXI mtune -03 build optimisations for 3rd Gen Intel Core processors 
* Namespaces support 
* Openvswitch GRE support 

