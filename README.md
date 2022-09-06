# nv-switch

Small program for switching the drivers of the second GPU, in a VFIO setup, between `nvidia` and `vfio` .

This is convenient for keeping the GPU usable (and power-managed) when not running a guest.

The program works but I've discontinued, as, after many years of VFIO, I've moved back to a dual boot solution (VFIO always need hacks, in one way or another).
