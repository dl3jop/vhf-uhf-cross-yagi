# vhf-uhf-satellite-yagi

## Introduction
This repo contains simulations, pictures and 3D models to built your own dual-band 2m (VHF) and 70cm (UHF) yagi.
The simulation assumes 4 elements on 2 m and 7 elements on 70 cm. If you need another configuration you must modify the simulation accoringly to determine the new spacings and element sizes.

Note:
Consider this project as work-in-progress. I initially did not plan to release this so all of this documentation is written afterwards 

## Materials needed
The materials I used or this built are:

* 4mm aluminium rods for the elements. These are quite fragile, consider using larger aluminum tubes for a more rigid setup
* 10x10mm aluminium tube for the boom. If you built a small yagi, you can get away with 1m pre-cut pieces from the hardware store. For the 4/7 elements version I used a 2m rod and cut it to length myself.
* coaxial feedline of your choice. I used short runs of RG-58CU cable
* cable shoes and M2 screws to attach the coax to the elements. I don't really like this solution. Maybe you have a better idea?
* cable ties if you want to mount your coax along the boom
* glue of your choice to glue fix teh 3d printed element mounts to the boom. I used 2 component adhesive

Note:
You can use painters or electrical tape to mark the initial element positions when fitting the 3D printed mounts


## Simulations
The simulations are done using MMana-Gal. The design frequencies are 145.9 MHz and 436.5 MHz, the mid point of the 2 m and 70 cm amateurradio satellite band. As this simualtion hast two diffrent antennas you must specify the right driven element to get right results:
* w2c is the 2 m driven  element
* w6c is the 70 cm driven element
Note:
Instead of changing the excitation amplitude to the desired element, make sure the the driven element is always source 1 as I ran into aborting simulations when setting the amplitude of source one to zero and the amplitude of source two to one.

## 3D Files
Currently there is no 3D model of the antenna. Did I already say that I never intend to publish this? ;D Maybe it will come in the future.
Included files:
* boom handle
* standard element mount
* driven element mount
