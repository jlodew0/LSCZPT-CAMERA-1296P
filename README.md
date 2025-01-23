# LSCZPT-CAMERA-1296P
Dualband zoom pan tilt camera available in action Belgium.
![alt text](https://raw.githubusercontent.com/jlodew0/LSCZPT-CAMERA-1296P/refs/heads/main/3007325_8712879163671-111_01_20241219145120.avif?raw=true)

UART output:
U-Boot 2013.10.0-V3.1.28_bchV1.0.03 (Jun 11 2024 - 21:50:55)

DRAM:  64 MiB
efuse_read:0x00000003
8 MiB
sd detect gpio mode:84!
mmc_sd: 0
In:    serial
Out:   serial
Err:   serial
Net:   led init.
red led init:1.
No ethernet found.
MMC: detect card present
mmc/sd share pin!
send cmd 8 error, status = 2004
block rw command 8 is failed!
MMC: ak mmc mmc_send_if_cond Err!
* Bad device mmc 0 *
KERNEL: size:0x00180000, offset:0x00040000

Booting kernel from Legacy Image at 80008000 ...
   Image Name:   Linux-4.4.192V2.1
   Image Type:   ARM Linux Kernel Image (uncompressed)
   Data Size:    1570664 Bytes = 1.5 MiB
   Load Address: 80008000
   Entry Point:  80008040
   Verifying Checksum ... OK
   XIP Kernel Image ... OK
   kernel loaded at 0x80008000, end = 0x80187768
using: FDT

Booting Linux on physical CPU 0x0
Linux version 4.4.192V2.1 (hutong@ubuntu) (gcc version 4.9.4 (Buildroot 2018.02.                                                             7_V1.0.03-g9ff3371) ) #1 Wed Apr 27 10:24:15 CST 2022
CPU: ARM926EJ-S [41069265] revision 5 (ARMv5TEJ), cr=0005317f
CPU: VIVT data cache, VIVT instruction cache
Machine model: ak3918ev330 dev board
Memory policy: Data cache writeback
ANYKA CPU AK39XXEV330 (ID 0x20160101)
Built 1 zonelists in Zone order, mobility grouping on.  Total pages: 16256
Kernel command line: console=ttySAK0,115200n8 root=/dev/mtdblock5 rootfstype=squ                                                             ashfs init=/sbin/init mtdparts=spi0.0:200K@0x0(UBOOT),4K@0x32000(ENV),4K@0x33000                                                             (ENVBK),48K@0x34000(DTB),1536K@0x40000(KERNEL),1024K@0x1C0000(ROOTFS),256K@0x2C0                                                             000(CONFIG),13312K@0x300000(APP) mem=64M memsize=64M
