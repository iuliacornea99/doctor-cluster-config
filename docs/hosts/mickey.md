# mickey

```
System:    Host: mickey Kernel: 6.1.29 x86_64 bits: 64 compiler: gcc v: 11.3.0 
           parameters: initrd=\efi\nixos\2syh801hdwh0z655snmzcb2swa9jvfrm-initrd-linux-6.1.29-initrd.efi 
           init=/nix/store/yvif91r9hx5jv41akhqb9zjwzgg08q2q-nixos-system-mickey-22.11.20230523.fc06fd7/init 
           console=tty0 console=ttyS0,115200 nohibernate loglevel=4 
           Console: N/A Distro: NixOS 22.11 (Raccoon) 
Machine:   Type: Server System: Dell product: PowerEdge R440 v: N/A serial: 3YBVXK3 Chassis: 
           type: 23 serial: 3YBVXK3 
           Mobo: Dell model: 04JN2K v: A09 serial: .3YBVXK3.CNFCP001B3002P. UEFI: Dell v: 2.12.2 
           date: 07/09/2021 
Memory:    RAM: total: 125.53 GiB used: 18.31 GiB (14.6%) 
           Array-1: capacity: 1024 GiB slots: 16 EC: Multi-bit ECC max-module-size: 64 GiB 
           note: est. 
           Device-1: A1 size: 32 GiB speed: spec: 3200 MT/s actual: 2666 MT/s type: DDR4 
           detail: synchronous registered (buffered) bus-width: 64 bits total: 72 bits 
           manufacturer: 00CE063200CE part-no: M393A4K40DB3-CWE serial: 206E7616 
           Device-2: A2 size: 32 GiB speed: spec: 3200 MT/s actual: 2666 MT/s type: DDR4 
           detail: synchronous registered (buffered) bus-width: 64 bits total: 72 bits 
           manufacturer: 00CE063200CE part-no: M393A4K40DB3-CWE serial: 2064040F 
           Device-3: A3 size: No Module Installed 
           Device-4: A4 size: No Module Installed 
           Device-5: A5 size: No Module Installed 
           Device-6: A6 size: No Module Installed 
           Device-7: A7 size: No Module Installed 
           Device-8: A8 size: No Module Installed 
           Device-9: A9 size: No Module Installed 
           Device-10: A10 size: No Module Installed 
           Device-11: B1 size: 32 GiB speed: spec: 3200 MT/s actual: 2666 MT/s type: DDR4 
           detail: synchronous registered (buffered) bus-width: 64 bits total: 72 bits 
           manufacturer: 00CE063200CE part-no: M393A4K40DB3-CWE serial: 206E764A 
           Device-12: B2 size: 32 GiB speed: spec: 3200 MT/s actual: 2666 MT/s type: DDR4 
           detail: synchronous registered (buffered) bus-width: 64 bits total: 72 bits 
           manufacturer: 00CE063200CE part-no: M393A4K40DB3-CWE serial: 206E764B 
           Device-13: B3 size: No Module Installed 
           Device-14: B4 size: No Module Installed 
           Device-15: B5 size: No Module Installed 
           Device-16: B6 size: No Module Installed 
PCI Slots: Slot: 2 type: x16 PCI Express 3 PCIe Slot 2 status: Available length: Short 
           Slot: 3 type: x16 PCI Express 3 PCIe Slot 3 status: In Use length: Short 
           Slot: 1 type: x8 PCI Express 3 Mezzanine 1 status: In Use length: Other 
           Slot: 8 type: x4 PCI Express 3 SFF-8639 (U.2) PCIe SSD Slot 8 in Bay 1 
           status: Available length: 2.5" drive form factor 
           Slot: 9 type: x4 PCI Express 3 SFF-8639 (U.2) PCIe SSD Slot 9 in Bay 1 status: In Use 
           length: 2.5" drive form factor 
           Slot: 7 type: x4 PCI Express 3 SFF-8639 (U.2) PCIe SSD Slot 7 in Bay 1 
           status: Available length: 2.5" drive form factor 
           Slot: 6 type: x4 PCI Express 3 SFF-8639 (U.2) PCIe SSD Slot 6 in Bay 1 
           status: Available length: 2.5" drive form factor 
CPU:       Info: 2x 10-Core model: Intel Xeon Gold 5215 socket: LGA2011 bits: 64 type: MT MCP SMP 
           arch: Cascade Lake family: 6 model-id: 55 (85) stepping: 7 microcode: 5003303 cache: 
           L2: 27.5 MiB 
           flags: avx avx2 lm nx pae sse sse2 sse3 sse4_1 sse4_2 ssse3 vmx bogomips: 120211 
           Speed: 1000 MHz min/max: N/A base/boost: 2500/4000 volts: 1.8 V ext-clock: 10400 MHz 
           Core speeds (MHz): 1: 1000 2: 1000 3: 2500 4: 2500 5: 2500 6: 2500 7: 2500 8: 2500 
           9: 2500 10: 2500 11: 2500 12: 1000 13: 2500 14: 2500 15: 2500 16: 2500 17: 2500 
           18: 2500 19: 1000 20: 2500 21: 1000 22: 2500 23: 2500 24: 2500 25: 2500 26: 1000 
           27: 2500 28: 2500 29: 1000 30: 2500 31: 2500 32: 2500 33: 2500 34: 2500 35: 2500 
           36: 2500 37: 1000 38: 2500 39: 2500 40: 2500 
           Vulnerabilities: Type: itlb_multihit status: KVM: VMX disabled 
           Type: l1tf status: Not affected 
           Type: mds status: Not affected 
           Type: meltdown status: Not affected 
           Type: mmio_stale_data mitigation: Clear CPU buffers; SMT vulnerable 
           Type: retbleed mitigation: Enhanced IBRS 
           Type: spec_store_bypass mitigation: Speculative Store Bypass disabled via prctl 
           Type: spectre_v1 mitigation: usercopy/swapgs barriers and __user pointer sanitization 
           Type: spectre_v2 
           mitigation: Enhanced IBRS, IBPB: conditional, RSB filling, PBRSB-eIBRS: SW sequence 
           Type: srbds status: Not affected 
           Type: tsx_async_abort mitigation: TSX disabled 
Graphics:  Device-1: Matrox Systems Integrated Matrox G200eW3 Graphics vendor: Dell 
           driver: mgag200 v: kernel bus-ID: 03:00.0 chip-ID: 102b:0536 class-ID: 0300 
           Display: server: No display server data found. Headless machine? tty: N/A 
           Message: Advanced graphics data unavailable in console for root. 
Audio:     Message: No device data found. 
Network:   Device-1: Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe vendor: Dell driver: tg3 
           v: kernel port: 2000 bus-ID: 04:00.0 chip-ID: 14e4:165f class-ID: 0200 
           IF: eno1 state: down mac: f4:ee:08:0b:f6:37 
           Device-2: Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe vendor: Dell driver: tg3 
           v: kernel port: 2000 bus-ID: 04:00.1 chip-ID: 14e4:165f class-ID: 0200 
           IF: eno2 state: down mac: f4:ee:08:0b:f6:38 
           Device-3: Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet vendor: Dell 
           driver: bnxt_en v: kernel port: 2000 bus-ID: 5e:00.0 chip-ID: 14e4:16d8 class-ID: 0200 
           IF: enp94s0f0np0 state: up speed: 10000 Mbps duplex: full mac: f4:ee:08:0a:ea:b5 
           IP v4: 131.159.102.10/24 type: dynamic scope: global broadcast: 131.159.102.255 
           IP v6: 2a09:80c0:102::10/128 type: dynamic noprefixroute scope: global 
           IP v6: fe80::f6ee:8ff:fe0a:eab5/64 scope: link 
           Device-4: Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet vendor: Dell 
           driver: bnxt_en v: kernel port: 2000 bus-ID: 5e:00.1 chip-ID: 14e4:16d8 class-ID: 0200 
           IF: enp94s0f1np1 state: down mac: f4:ee:08:0a:ea:b6 
           IF-ID-1: cni0 state: up speed: 10000 Mbps duplex: unknown mac: 82:23:6b:01:16:16 
           IP v4: 10.42.4.1/24 scope: global broadcast: 10.42.4.255 
           IP v6: fe80::3800:45ff:fe2c:bee5/64 scope: link 
           IF-ID-2: docker0 state: down mac: 02:42:36:8c:8c:49 
           IP v4: 172.17.0.1/16 scope: global broadcast: 172.17.255.255 
           IF-ID-3: tinc.retiolum state: unknown speed: 10 Mbps duplex: full mac: N/A 
           IP v6: 42:0:3c46:a85d:33c6:14ca:3cf7:8827/16 scope: global 
           IF-ID-4: veth39853723 state: up speed: 10000 Mbps duplex: full mac: 02:3e:ef:2a:44:84 
           IF-ID-5: veth7a73e2e5 state: up speed: 10000 Mbps duplex: full mac: 3e:8d:e9:6d:b4:2b 
           IF-ID-6: veth8454ad38 state: up speed: 10000 Mbps duplex: full mac: 22:0b:c3:e1:35:b6 
           IF-ID-7: vethb13d6675 state: up speed: 10000 Mbps duplex: full mac: 3e:39:a5:10:24:af 
           IF-ID-8: vethc11e5fb7 state: up speed: 10000 Mbps duplex: full mac: a2:2c:d0:6d:85:df 
           IF-ID-9: vethc846653c state: up speed: 10000 Mbps duplex: full mac: c6:83:16:a9:4d:94 
           IF-ID-10: vethdafe7bb0 state: up speed: 10000 Mbps duplex: full mac: 1e:67:4e:b3:dc:56 
           WAN IP: 131.159.102.10 
RAID:      Hardware-1: Broadcom / LSI MegaRAID 12GSAS/PCIe Secure SAS39xx driver: megaraid_sas 
           v: 07.719.03.00-rc1 port: c000 bus-ID: af:00.0 chip-ID: 1000.10e2 rev: class-ID: 0104 
           Device-1: zroot type: zfs status: ONLINE level: linear size: 1.45 TiB free: 1.39 TiB 
           allocated: 61.2 GiB 
           Components: Online: N/A 
Drives:    Local Storage: total: raw: 1.46 TiB usable: 2.91 TiB used: 1.43 TiB (49.2%) 
           ID-1: /dev/nvme0n1 maj-min: 259:0 vendor: Dell model: Ent NVMe P5600 MU U.2 1.6TB 
           size: 1.46 TiB block-size: physical: 512 B logical: 512 B speed: 63.2 Gb/s lanes: 4 
           rotation: SSD serial: PHAB1233010E1P9SGN rev: 1.1.5 temp: 27 Celsius C scheme: GPT 
           SMART: yes health: PASSED on: 1y 136d 2h cycles: 16 read-units: 6,809,876 [3.48 TB] 
           written-units: 47,161,996 [24.1 TB] 
Partition: ID-1: / raw-size: N/A size: 1.38 TiB used: 35.42 GiB (2.5%) fs: zfs 
           logical: zroot/root/nixos 
           ID-2: /boot raw-size: 1024 MiB size: 1022 MiB (99.80%) used: 34 MiB (3.3%) fs: vfat 
           block-size: 512 B dev: /dev/nvme0n1p1 maj-min: 259:1 
           ID-3: /home raw-size: N/A size: 680.07 GiB used: 529.25 GiB (77.8%) fs: nfs4 
           remote: nfs:/export/home 
Swap:      Alert: No swap data was found. 
Sensors:   Message: No ipmi sensor data found. 
           System Temperatures: lm-sensors cpu: 78.0 C mobo: N/A 
           Fan Speeds (RPM): lm-sensors N/A 
Info:      Processes: 606 
           Uptime: 15:02:09  up 12 days 14:47,  0 users,  load average: 0.78, 0.76, 0.61 
           wakeups: 0 Init: systemd v: 251 target: multi-user.target tool: systemctl Compilers: 
           gcc: 11.3.0 Packages: nix-default: 0 nix-sys: 395 lib: 64 nix-usr: 0 Client: Sudo 
           v: 1.9.13p3 inxi: 3.3.04 
```
![hardware topology](mickey.lstopo.svg)
