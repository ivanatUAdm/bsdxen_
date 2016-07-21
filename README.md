# bsdxen
FreeBSD with Xen hypervisor

This is a set of scripts that generates a bootable image, ISO file or boot files only, that create a working minimal installation of FreeBSD suitable for work with Xen. This minimal installation gets completely loaded into memory.

The image may be written directly using dd(1) onto any bootable block device, e.g. a hard disk or a USB stick e.g. /dev/da0, or a bootable slice only, e.g. /dev/ada0p1

Build-time requirements

    FreeBSD 11 or higher installed. Tested on amd64 only. i386 is unusable to this tasks.
    Base and kernel from a FreeBSD 11 or higher distribution (release or snapshots, e.g mounted CDROM disc1 or ISO file)

Runtime requirements

    a minimum of 1024MB system memory, 8192MB and more higly recommended

Other information

See BUILD and INSTALL files for building and installation instructions.

This project is based on the scripts set mfsBSD by Martin Matuska http://mfsbsd.vx.sk
