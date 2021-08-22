# nv-switch

Small program for switching the drivers of the second GPU, in a VFIO setup, between `nvidia` and `vfio` .

This is convenient for keeping the GPU usable (and power-managed) when not running a guest.

The program works (I use it on my machine), but I'm working on making usable in a generic way.
