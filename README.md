# Xiaomi-Mi-Router-AC2100
LogFile (03.05.2021 17:03)
[    4.896105] Rebooting in 1 seconds..


===================================================================

     		MT7621   stage1 code May 28 2018 14:51:28 (ASIC)

     		CPU=50000000 HZ BUS=16666666 HZ

==================================================================

Change MPLL source from XTAL to CR...

do MEMPLL setting..

MEMPLL Config : 0x11100000

3PLL mode + External loopback

=== XTAL-40Mhz === DDR-1200Mhz ===

PLL4 FB_DL: 0x8, 1/0 = 531/493 21000000

PLL2 FB_DL: 0xe, 1/0 = 697/327 39000000

PLL3 FB_DL: 0x10, 1/0 = 580/444 41000000

do DDR setting..[00320381]

Apply DDR3 Setting...(use customer AC)

          0    8   16   24   32   40   48   56   64   72   80   88   96  104  112  120

      --------------------------------------------------------------------------------

0000:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

0001:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

0002:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

0003:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

0004:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

0005:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

0006:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

0007:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

0008:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

0009:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

000A:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

000B:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

000C:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

000D:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

000E:|    0    0    0    0    0    0    0    0    0    0    1    1    1    1    1    1

000F:|    0    0    0    0    1    1    1    1    1    1    1    1    1    1    0    0

0010:|    1    1    1    1    1    1    1    1    1    0    0    0    0    0    0    0

0011:|    1    1    1    0    0    0    0    0    0    0    0    0    0    0    0    0

0012:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

0013:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

0014:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

0015:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

0016:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

0017:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

0018:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

0019:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

001A:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

001B:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

001C:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

001D:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

001E:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

001F:|    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0    0

DRAMC_DQSCTL1[0e0]=13000000

DRAMC_DQSGCTL[124]=80000033

rank 0 coarse = 15

rank 0 fine = 72

B:|    0    0    0    0    0    0    0    0    0    0    1    1    1    0    0    0

opt_dle value:11

DRAMC_DDR2CTL[07c]=C287223D

DRAMC_PADCTL4[0e4]=000044B3

DRAMC_DQIDLY1[210]=08080708

DRAMC_DQIDLY2[214]=06040605

DRAMC_DQIDLY3[218]=07070606

DRAMC_DQIDLY4[21c]=07060707

DRAMC_R0DELDLY[018]=00002021

==================================================================

		RX	DQS perbit delay software calibration 

==================================================================

1.0-15 bit dq delay value

==================================================================

bit|     0  1  2  3  4  5  6  7  8  9

--------------------------------------

0 |    5 3 6 6 3 5 4 5 3 4 

10 |    6 6 6 7 5 6 

--------------------------------------



==================================================================

2.dqs window

x=pass dqs delay value (min~max)center 

y=0-7bit DQ of every group

input delay:DQS0 =33 DQS1 = 32

==================================================================

bit	DQS0	 bit      DQS1

0  (1~60)30  8  (1~58)29

1  (1~58)29  9  (1~60)30

2  (1~61)31  10  (1~62)31

3  (1~62)31  11  (2~60)31

4  (1~62)31  12  (1~62)31

5  (1~64)32  13  (1~64)32

6  (1~65)33  14  (1~62)31

7  (1~64)32  15  (1~62)31

==================================================================

3.dq delay value last

==================================================================

bit|    0  1  2  3  4  5  6  7  8   9

--------------------------------------

0 |    8 7 8 8 5 6 4 6 6 6 

10 |    7 7 7 7 6 7 

==================================================================

==================================================================

     TX  perbyte calibration 

==================================================================

DQS loop = 15, cmp_err_1 = ffff2000 

dqs_perbyte_dly.last_dqsdly_pass[0]=15,  finish count=1 

DQS loop = 14, cmp_err_1 = ffff0000 

dqs_perbyte_dly.last_dqsdly_pass[1]=14,  finish count=2 

DQ loop=15, cmp_err_1 = ffff0000

dqs_perbyte_dly.last_dqdly_pass[0]=15,  finish count=1 

dqs_perbyte_dly.last_dqdly_pass[1]=15,  finish count=2 

byte:0, (DQS,DQ)=(8,8)

byte:1, (DQS,DQ)=(8,8)

DRAMC_DQODLY1[200]=88888888

DRAMC_DQODLY2[204]=88888888

20,data:88

[EMI] DRAMC calibration passed




===================================================================

     		MT7621   stage1 code done 

     		CPU=50000000 HZ BUS=16666666 HZ

===================================================================



U-Boot 1.1.3 (Sep 21 2020 - 11:46:27)


Board: Ralink APSoC DRAM:  128 MB

Power on memory test. Memory size= 128 MB...OK!

relocate_code Pointer at: 87fa4000


Config XHCI 40M PLL 

******************************

Software System Reset Occurred

******************************

Allocate 16 byte aligned buffer: 87fe0190

Enable NFI Clock

# MTK NAND # : Use HW ECC

NAND ID [C8 D1 80 95 40]

Device found in MTK table, ID: c8d1, EXT_ID: 809540

Support this Device in MTK table! c8d1 

select_chip

[NAND]select ecc bit:4, sparesize :64 spare_per_sector=16

Signature matched and data read!

load_fact_bbt success 1023

load fact bbt success

[mtk_nand] probe successfully!

mtd->writesize=2048 mtd->oobsize=64,	mtd->erasesize=131072  devinfo.iowidth=8

..============================================ 

Ralink UBoot Version: 5.0.0.0

-------------------------------------------- 

ASIC MT7621A DualCore (MAC to MT7530 Mode)

DRAM_CONF_FROM: Auto-Detection 

DRAM_TYPE: DDR3 

DRAM bus: 16 bit

Xtal Mode=3 OCP Ratio=1/3

Flash component: NAND Flash

Date:Sep 21 2020  Time:11:46:27

============================================ 

icache: sets:256, ways:4, linesz:32 ,total:32768

dcache: sets:256, ways:4, linesz:32 ,total:32768 


 ##### The CPU freq = 880 MHZ #### 

 estimate memory size =128 Mbytes

#Reset_MT7530

set LAN/WAN WLLLL


Please choose the operation: 

   1: Load system code to SDRAM via TFTP. 

   2: Load system code then write to Flash via TFTP. 

   3: Boot system code via Flash (default).

   4: Entr boot command line interface.

   7: Load Boot Loader code then write to Flash via Serial. 

   9: Load Boot Loader code then write to Flash via TFTP. 

 4  3  2  1  0 

Booting System 2

..ranand_erase: start:80000, len:20000 

..Done!

done

   

3: System Boot system code via Flash.

## Booting image at bc600000 ...

   Image Name:   MIPS OpenWrt Linux-5.4.97

   Image Type:   MIPS Linux Kernel Image (uncompressed)

   Data Size:    2506130 Bytes =  2.4 MB

   Load Address: 80001000

   Entry Point:  80001000

.......................................   Verifying Checksum ... OK

OK

commandline uart_en=1 factory_mode=0

No initrd

## Transferring control to Linux (at address 80001000) ...

## Giving linux memsize in MB, 128


Starting kernel ...




OpenWrt kernel loader for MIPS based SoC

Copyright (C) 2011 Gabor Juhos <juhosg@openwrt.org>

Decompressing kernel... done!

Starting kernel at 80001000...


[    0.000000] Linux version 5.4.97 (builder@buildhost) (gcc version 8.4.0 (OpenWrt GCC 8.4.0 r15756-da283a8f2c)) #0 SMP Sun Feb 14 14:15:32 2021
[    0.000000] SoC Type: MediaTek MT7621 ver:1 eco:3
[    0.000000] printk: bootconsole [early0] enabled
[    0.000000] CPU0 revision is: 0001992f (MIPS 1004Kc)
[    0.000000] MIPS: machine is Xiaomi Mi Router AC2100
[    0.000000] Initrd not found or empty - disabling initrd
[    0.000000] VPE topology {2,2} total 4
[    0.000000] Primary instruction cache 32kB, VIPT, 4-way, linesize 32 bytes.
[    0.000000] Primary data cache 32kB, 4-way, PIPT, no aliases, linesize 32 bytes
[    0.000000] MIPS secondary cache 256kB, 8-way, linesize 32 bytes.
[    0.000000] Zone ranges:
[    0.000000]   Normal   [mem 0x0000000000000000-0x0000000007ffffff]
[    0.000000]   HighMem  empty
[    0.000000] Movable zone start for each node
[    0.000000] Early memory node ranges
[    0.000000]   node   0: [mem 0x0000000000000000-0x0000000007ffffff]
[    0.000000] Initmem setup node 0 [mem 0x0000000000000000-0x0000000007ffffff]
[    0.000000] percpu: Embedded 14 pages/cpu s26768 r8192 d22384 u57344
[    0.000000] Built 1 zonelists, mobility grouping on.  Total pages: 32480
[    0.000000] Kernel command line: console=ttyS0,115200n8 rootfstype=squashfs,jffs2
[    0.000000] Dentry cache hash table entries: 16384 (order: 4, 65536 bytes, linear)
[    0.000000] Inode-cache hash table entries: 8192 (order: 3, 32768 bytes, linear)
[    0.000000] Writing ErrCtl register=000020d0
[    0.000000] Readback ErrCtl register=000020d0
[    0.000000] mem auto-init: stack:off, heap alloc:off, heap free:off
[    0.000000] Memory: 120456K/131072K available (6060K kernel code, 204K rwdata, 1288K rodata, 1268K init, 238K bss, 10616K reserved, 0K cma-reserved, 0K highmem)
[    0.000000] SLUB: HWalign=32, Order=0-3, MinObjects=0, CPUs=4, Nodes=1
[    0.000000] rcu: Hierarchical RCU implementation.
[    0.000000] rcu: RCU calculated value of scheduler-enlistment delay is 25 jiffies.
[    0.000000] NR_IRQS: 256
[    0.000000] random: get_random_bytes called from start_kernel+0x340/0x558 with crng_init=0
[    0.000000] CPU Clock: 880MHz
[    0.000000] clocksource: GIC: mask: 0xffffffffffffffff max_cycles: 0xcaf478abb4, max_idle_ns: 440795247997 ns
[    0.000000] clocksource: MIPS: mask: 0xffffffff max_cycles: 0xffffffff, max_idle_ns: 4343773742 ns
[    0.000009] sched_clock: 32 bits at 440MHz, resolution 2ns, wraps every 4880645118ns
[    0.007802] Calibrating delay loop... 583.68 BogoMIPS (lpj=1167360)
[    0.042002] pid_max: default: 32768 minimum: 301
[    0.046773] Mount-cache hash table entries: 1024 (order: 0, 4096 bytes, linear)
[    0.053998] Mountpoint-cache hash table entries: 1024 (order: 0, 4096 bytes, linear)
[    0.064414] rcu: Hierarchical SRCU implementation.
[    0.069852] smp: Bringing up secondary CPUs ...
[    7.333217] Primary instruction cache 32kB, VIPT, 4-way, linesize 32 bytes.
[    7.333228] Primary data cache 32kB, 4-way, PIPT, no aliases, linesize 32 bytes
[    7.333240] MIPS secondary cache 256kB, 8-way, linesize 32 bytes.
[    7.333342] CPU1 revision is: 0001992f (MIPS 1004Kc)
[    0.102619] Synchronize counters for CPU 1: done.
[    7.394528] Primary instruction cache 32kB, VIPT, 4-way, linesize 32 bytes.
[    7.394538] Primary data cache 32kB, 4-way, PIPT, no aliases, linesize 32 bytes
[    7.394545] MIPS secondary cache 256kB, 8-way, linesize 32 bytes.
[    7.394603] CPU2 revision is: 0001992f (MIPS 1004Kc)
[    0.167316] Synchronize counters for CPU 2: done.
[    7.455905] Primary instruction cache 32kB, VIPT, 4-way, linesize 32 bytes.
[    7.455913] Primary data cache 32kB, 4-way, PIPT, no aliases, linesize 32 bytes
[    7.455921] MIPS secondary cache 256kB, 8-way, linesize 32 bytes.
[    7.455980] CPU3 revision is: 0001992f (MIPS 1004Kc)
[    0.225179] Synchronize counters for CPU 3: done.
[    0.255052] smp: Brought up 1 node, 4 CPUs
[    0.263493] clocksource: jiffies: mask: 0xffffffff max_cycles: 0xffffffff, max_idle_ns: 7645041785100000 ns
[    0.273174] futex hash table entries: 1024 (order: 3, 32768 bytes, linear)
[    0.280198] pinctrl core: initialized pinctrl subsystem
[    0.287050] NET: Registered protocol family 16
[    0.319923] workqueue: max_active 576 requested for napi_workq is out of range, clamping between 1 and 512
[    0.331205] clocksource: Switched to clocksource GIC
[    0.338018] NET: Registered protocol family 2
[    0.343423] tcp_listen_portaddr_hash hash table entries: 512 (order: 0, 6144 bytes, linear)
[    0.351731] TCP established hash table entries: 1024 (order: 0, 4096 bytes, linear)
[    0.359311] TCP bind hash table entries: 1024 (order: 1, 8192 bytes, linear)
[    0.366301] TCP: Hash tables configured (established 1024 bind 1024)
[    0.372741] UDP hash table entries: 256 (order: 1, 8192 bytes, linear)
[    0.379229] UDP-Lite hash table entries: 256 (order: 1, 8192 bytes, linear)
[    0.386418] NET: Registered protocol family 1
[    0.390732] PCI: CLS 0 bytes, default 32
[    0.483138] 4 CPUs re-calibrate udelay(lpj = 1167360)
[    0.489620] workingset: timestamp_bits=14 max_order=15 bucket_order=1
[    0.502501] random: fast init done
[    0.510434] squashfs: version 4.0 (2009/01/31) Phillip Lougher
[    0.516231] jffs2: version 2.2 (NAND) (SUMMARY) (LZMA) (RTIME) (CMODE_PRIORITY) (c) 2001-2006 Red Hat, Inc.
[    0.527789] Block layer SCSI generic (bsg) driver version 0.4 loaded (major 251)
[    0.537062] mt7621_gpio 1e000600.gpio: registering 32 gpios
[    0.542950] mt7621_gpio 1e000600.gpio: registering 32 gpios
[    0.548825] mt7621_gpio 1e000600.gpio: registering 32 gpios
[    0.555303] Serial: 8250/16550 driver, 16 ports, IRQ sharing enabled
[    0.565214] printk: console [ttyS0] disabled
[    0.569513] 1e000c00.uartlite: ttyS0 at MMIO 0x1e000c00 (irq = 19, base_baud = 3125000) is a 16550A
[    0.578496] printk: console [ttyS0] enabled
[    0.578496] printk: console [ttyS0] enabled
[    0.586754] printk: bootconsole [early0] disabled
[    0.586754] printk: bootconsole [early0] disabled
[    0.598519] mt7621-nand 1e003000.nand: Using programmed access timing: 31c07388
[    0.606103] nand: device found, Manufacturer ID: 0xc8, Chip ID: 0xd1
[    0.612451] nand: ESMT PSU1GA30DT
[    0.615773] nand: 128 MiB, SLC, erase size: 128 KiB, page size: 2048, OOB size: 64
[    0.623331] mt7621-nand 1e003000.nand: ECC strength adjusted to 4 bits
[    0.629875] mt7621-nand 1e003000.nand: Using programmed access timing: 21005134
[    0.637174] mt7621-nand 1e003000.nand: Using programmed access timing: 21005134
[    0.644470] Scanning device for bad blocks
[    2.626587] 10 fixed-partitions partitions found on MTD device mt7621-nand
[    2.633451] Creating 10 MTD partitions on "mt7621-nand":
[    2.638763] 0x000000000000-0x000000080000 : "Bootloader"
[    2.645566] 0x000000080000-0x0000000c0000 : "Config"
[    2.652025] 0x0000000c0000-0x000000100000 : "Bdata"
[    2.658174] 0x000000100000-0x000000140000 : "factory"
[    2.664692] 0x000000140000-0x000000180000 : "crash"
[    2.670888] 0x000000180000-0x0000001c0000 : "crash_syslog"
[    2.677774] 0x0000001c0000-0x000000200000 : "reserved0"
[    2.684328] 0x000000200000-0x000000600000 : "kernel_stock"
[    2.691348] 0x000000600000-0x000000a00000 : "kernel"
[    2.697626] 0x000000a00000-0x000007f80000 : "ubi"
[    2.705819] libphy: Fixed MDIO Bus: probed
[    2.737594] libphy: mdio: probed
[    2.741088] mt7530 mdio-bus:1f: MT7530 adapts as multi-chip module
[    2.751298] mtk_soc_eth 1e100000.ethernet eth0: mediatek frame engine at 0xbe100000, irq 21
[    2.761582] mt7621-pci 1e140000.pcie: Parsing DT failed
[    2.769322] NET: Registered protocol family 10
[    2.775312] Segment Routing with IPv6
[    2.779065] NET: Registered protocol family 17
[    2.783602] bridge: filtering via arp/ip/ip6tables is no longer available by default. Update your scripts to load br_netfilter if you need this.
[    2.796786] 8021q: 802.1Q VLAN Support v1.8
[    2.802801] mt7530 mdio-bus:1f: MT7530 adapts as multi-chip module
[    2.818300] libphy: dsa slave smi: probed
[    2.822757] mt7530 mdio-bus:1f wan (uninitialized): PHY [dsa-0.0:00] driver [Generic PHY]
[    2.832608] mt7530 mdio-bus:1f lan1 (uninitialized): PHY [dsa-0.0:02] driver [Generic PHY]
[    2.842320] mt7530 mdio-bus:1f lan2 (uninitialized): PHY [dsa-0.0:03] driver [Generic PHY]
[    2.852104] mt7530 mdio-bus:1f lan3 (uninitialized): PHY [dsa-0.0:04] driver [Generic PHY]
[    2.861856] mt7530 mdio-bus:1f: configuring for fixed/rgmii link mode
[    2.873093] DSA: tree 0 setup
[    2.876411] rt2880-pinmux pinctrl: pcie is already enabled
[    2.881906] mt7621-pci 1e140000.pcie: Error applying setting, reverse things back
[    2.889534] mt7621-pci-phy 1e149000.pcie-phy: PHY for 0xbe149000 (dual port = 1)
[    2.897110] mt7621-pci-phy 1e14a000.pcie-phy: PHY for 0xbe14a000 (dual port = 0)
[    3.004691] mt7621-pci-phy 1e149000.pcie-phy: Xtal is 40MHz
[    3.010273] mt7621-pci-phy 1e14a000.pcie-phy: Xtal is 40MHz
[    3.115961] mt7621-pci 1e140000.pcie: pcie2 no card, disable it (RST & CLK)
[    3.122912] mt7621-pci 1e140000.pcie: PCIE0 enabled
[    3.127787] mt7621-pci 1e140000.pcie: PCIE1 enabled
[    3.132672] mt7621-pci 1e140000.pcie: PCI coherence region base: 0x60000000, mask/settings: 0xf0000002
[    3.142140] mt7621-pci 1e140000.pcie: PCI host bridge to bus 0000:00
[    3.148510] pci_bus 0000:00: root bus resource [io  0x1e160000-0x1e16ffff]
[    3.155380] pci_bus 0000:00: root bus resource [mem 0x60000000-0x6fffffff]
[    3.162250] pci_bus 0000:00: root bus resource [bus 00-ff]
[    3.167772] pci 0000:00:00.0: [0e8d:0801] type 01 class 0x060400
[    3.173807] pci 0000:00:00.0: reg 0x10: [mem 0x00000000-0x7fffffff]
[    3.180073] pci 0000:00:00.0: reg 0x14: [mem 0x60400000-0x6040ffff]
[    3.186404] pci 0000:00:00.0: supports D1
[    3.190415] pci 0000:00:00.0: PME# supported from D0 D1 D3hot
[    3.196560] pci 0000:00:01.0: [0e8d:0801] type 01 class 0x060400
[    3.202601] pci 0000:00:01.0: reg 0x10: [mem 0x00000000-0x7fffffff]
[    3.208868] pci 0000:00:01.0: reg 0x14: [mem 0x60410000-0x6041ffff]
[    3.215216] pci 0000:00:01.0: supports D1
[    3.219227] pci 0000:00:01.0: PME# supported from D0 D1 D3hot
[    3.226446] pci 0000:01:00.0: [14c3:7615] type 00 class 0x000280
[    3.232519] pci 0000:01:00.0: reg 0x10: [mem 0x00000000-0x000fffff 64bit]
[    3.239468] pci 0000:01:00.0: 2.000 Gb/s available PCIe bandwidth, limited by 2.5 GT/s x1 link at 0000:00:00.0 (capable of 4.000 Gb/s with 5 GT/s x1 link)
[    3.254526] pci 0000:00:00.0: PCI bridge to [bus 01-ff]
[    3.259771] pci 0000:00:00.0:   bridge window [io  0x0000-0x0fff]
[    3.265863] pci 0000:00:00.0:   bridge window [mem 0x60000000-0x600fffff]
[    3.272645] pci 0000:00:00.0:   bridge window [mem 0x60100000-0x601fffff pref]
[    3.279864] pci_bus 0000:01: busn_res: [bus 01-ff] end is updated to 01
[    3.286711] pci 0000:02:00.0: [14c3:7603] type 00 class 0x028000
[    3.292766] pci 0000:02:00.0: reg 0x10: [mem 0x00000000-0x000fffff]
[    3.299195] pci 0000:02:00.0: PME# supported from D0 D3hot D3cold
[    3.306575] pci 0000:00:01.0: PCI bridge to [bus 02-ff]
[    3.311817] pci 0000:00:01.0:   bridge window [io  0x0000-0x0fff]
[    3.317907] pci 0000:00:01.0:   bridge window [mem 0x60200000-0x602fffff]
[    3.324690] pci 0000:00:01.0:   bridge window [mem 0x60300000-0x603fffff pref]
[    3.331908] pci_bus 0000:02: busn_res: [bus 02-ff] end is updated to 02
[    3.338564] pci 0000:00:00.0: BAR 0: no space for [mem size 0x80000000]
[    3.345171] pci 0000:00:00.0: BAR 0: failed to assign [mem size 0x80000000]
[    3.352136] pci 0000:00:01.0: BAR 0: no space for [mem size 0x80000000]
[    3.358744] pci 0000:00:01.0: BAR 0: failed to assign [mem size 0x80000000]
[    3.365701] pci 0000:00:00.0: BAR 8: assigned [mem 0x60000000-0x600fffff]
[    3.372487] pci 0000:00:00.0: BAR 9: assigned [mem 0x60100000-0x601fffff pref]
[    3.379706] pci 0000:00:01.0: BAR 8: assigned [mem 0x60200000-0x602fffff]
[    3.386491] pci 0000:00:01.0: BAR 9: assigned [mem 0x60300000-0x603fffff pref]
[    3.393707] pci 0000:00:00.0: BAR 1: assigned [mem 0x60400000-0x6040ffff]
[    3.400497] pci 0000:00:01.0: BAR 1: assigned [mem 0x60410000-0x6041ffff]
[    3.407285] pci 0000:00:00.0: BAR 7: assigned [io  0x1e160000-0x1e160fff]
[    3.414070] pci 0000:00:01.0: BAR 7: assigned [io  0x1e161000-0x1e161fff]
[    3.420861] pci 0000:01:00.0: BAR 0: assigned [mem 0x60000000-0x600fffff 64bit]
[    3.428174] pci 0000:00:00.0: PCI bridge to [bus 01]
[    3.433142] pci 0000:00:00.0:   bridge window [io  0x1e160000-0x1e160fff]
[    3.439924] pci 0000:00:00.0:   bridge window [mem 0x60000000-0x600fffff]
[    3.446707] pci 0000:00:00.0:   bridge window [mem 0x60100000-0x601fffff pref]
[    3.453928] pci 0000:02:00.0: BAR 0: assigned [mem 0x60200000-0x602fffff]
[    3.460713] pci 0000:00:01.0: PCI bridge to [bus 02]
[    3.465680] pci 0000:00:01.0:   bridge window [io  0x1e161000-0x1e161fff]
[    3.472462] pci 0000:00:01.0:   bridge window [mem 0x60200000-0x602fffff]
[    3.479250] pci 0000:00:01.0:   bridge window [mem 0x60300000-0x603fffff pref]
[    3.486989] mt7530 mdio-bus:1f: Link is Up - 1Gbps/Full - flow control off
[    3.494953] UBI: auto-attach mtd9
[    3.498311] ubi0: attaching mtd9
[    4.715913] ubi0: scanning is finished
[    4.736817] ubi0: attached mtd9 (name "ubi", size 117 MiB)
[    4.742336] ubi0: PEB size: 131072 bytes (128 KiB), LEB size: 126976 bytes
[    4.749200] ubi0: min./max. I/O unit sizes: 2048/2048, sub-page size 2048
[    4.755975] ubi0: VID header offset: 2048 (aligned 2048), data offset: 4096
[    4.762923] ubi0: good PEBs: 940, bad PEBs: 0, corrupted PEBs: 0
[    4.768921] ubi0: user volume: 0, internal volumes: 1, max. volumes count: 128
[    4.776130] ubi0: max/mean erase counter: 3/2, WL threshold: 4096, image sequence number: 674944404
[    4.785152] ubi0: available PEBs: 916, total reserved PEBs: 24, PEBs reserved for bad PEB handling: 20
[    4.794463] ubi0: background thread "ubi_bgt0d" started, PID 489
[    4.794488] hctosys: unable to open rtc device (rtc0)
[    4.806295] /dev/root: Can't open blockdev
[    4.810411] VFS: Cannot open root device "(null)" or unknown-block(0,0): error -6
[    4.817875] Please append a correct "root=" boot option; here are the available partitions:
[    4.826214] 1f00             512 mtdblock0 
[    4.826219]  (driver?)
[    4.832756] 1f01             256 mtdblock1 
[    4.832759]  (driver?)
[    4.839296] 1f02             256 mtdblock2 
[    4.839299]  (driver?)
[    4.845821] 1f03             256 mtdblock3 
[    4.845824]  (driver?)
[    4.852360] 1f04             256 mtdblock4 
[    4.852363]  (driver?)
[    4.858885] 1f05             256 mtdblock5 
[    4.858888]  (driver?)
[    4.865423] 1f06             256 mtdblock6 
[    4.865426]  (driver?)
[    4.871964] 1f07            4096 mtdblock7 
[    4.871967]  (driver?)
[    4.878488] 1f08            4096 mtdblock8 
[    4.878492]  (driver?)
[    4.885027] 1f09          120320 mtdblock9 
[    4.885030]  (driver?)
[    4.891586] Kernel panic - not syncing: VFS: Unable to mount root fs on unknown-block(0,0)
[    4.899850] Rebooting in 1 seconds..
