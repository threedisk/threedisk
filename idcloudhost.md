## IdCloudHost

Thu Nov 10 09:46:38 UTC 2022
```
Basic System Information:
---------------------------------
Uptime     : 0 days, 0 hours, 4 minutes
Processor  : QEMU Virtual CPU version 2.5+
CPU cores  : 1 @ 2099.998 MHz
AES-NI     : ❌ Disabled
VM-x/AMD-V : ❌ Disabled
RAM        : 971.2 MiB
Swap       : 0.0 KiB
Disk       : 29.0 GiB
Distro     : Ubuntu 22.04 LTS
Kernel     : 5.15.0-25-generic
```
```
fio Disk Speed Tests (Mixed R/W 50/50):
---------------------------------
Block Size | 4k            (IOPS) | 64k           (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 15.37 MB/s    (3.8k) | 109.23 MB/s   (1.7k)
Write      | 15.39 MB/s    (3.8k) | 109.80 MB/s   (1.7k)
Total      | 30.77 MB/s    (7.6k) | 219.03 MB/s   (3.4k)
           |                      |                     
Block Size | 512k          (IOPS) | 1m            (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 202.58 MB/s    (395) | 221.30 MB/s    (216)
Write      | 213.35 MB/s    (416) | 236.04 MB/s    (230)
Total      | 415.93 MB/s    (811) | 457.34 MB/s    (446)
```
```
iperf3 Network Speed Tests (IPv4):
---------------------------------
Provider        | Location (Link)           | Send Speed      | Recv Speed     
                |                           |                 |                
Clouvider       | London, UK (10G)          | 371 Mbits/sec   | 114 Mbits/sec  
Online.net      | Paris, FR (10G)           | 485 Mbits/sec   | 112 Mbits/sec  
Hybula          | The Netherlands (40G)     | 475 Mbits/sec   | 299 Mbits/sec  
Uztelecom       | Tashkent, UZ (10G)        | 471 Mbits/sec   | 179 Mbits/sec  
Clouvider       | NYC, NY, US (10G)         | 462 Mbits/sec   | 86.2 Mbits/sec 
Clouvider       | Dallas, TX, US (10G)      | 455 Mbits/sec   | 120 Mbits/sec  
Clouvider       | Los Angeles, CA, US (10G) | 423 Mbits/sec   | 138 Mbits/sec  
```