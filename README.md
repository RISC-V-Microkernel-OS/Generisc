# Generisc
A microkernel Operating system written- and using only C code. The aim is to have maximum correctness in the code, and for the OS to be as reliable and minimal as possible. Everything possible should be in sandboxes/jails, with a "snapshotter" to fall back to last stable state. The OS is single-server and single-user(no-user), but ofcourse multithreaded. All of the parts in the OS will have generic names. The name "Generisc" stems from the Norwegian translation of "generic", which is "generisk" and we're targeting RISC hardware.

# OS
Operating system using only open source software. All components written in C.

# Target platform
SiFive HiFive Unleashed
  Using QEMU.
