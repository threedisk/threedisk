## Racknerd Benchmark

Thu Nov 10 04:24:56 PM WIB 2022
```
Basic System Information:
---------------------------------
Uptime     : 0 days, 0 hours, 0 minutes
Processor  : Intel(R) Xeon(R) CPU E5-2697 v2 @ 2.70GHz
CPU cores  : 3 @ 2699.990 MHz
AES-NI     : ✔ Enabled
VM-x/AMD-V : ❌ Disabled
RAM        : 2.9 GiB
Swap       : 3.0 GiB
Disk       : 41.2 GiB
Distro     : Ubuntu 22.04.1 LTS
Kernel     : 5.15.0-52-generic
```
```
fio Disk Speed Tests (Mixed R/W 50/50):
---------------------------------
Block Size | 4k            (IOPS) | 64k           (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 76.85 MB/s   (19.2k) | 1.11 GB/s    (17.3k)
Write      | 77.05 MB/s   (19.2k) | 1.11 GB/s    (17.4k)
Total      | 153.91 MB/s  (38.4k) | 2.22 GB/s    (34.8k)
           |                      |                     
Block Size | 512k          (IOPS) | 1m            (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 1.34 GB/s     (2.6k) | 1.29 GB/s     (1.2k)
Write      | 1.41 GB/s     (2.7k) | 1.38 GB/s     (1.3k)
Total      | 2.76 GB/s     (5.3k) | 2.67 GB/s     (2.6k)
```
```
iperf3 Network Speed Tests (IPv4):
---------------------------------
Provider        | Location (Link)           | Send Speed      | Recv Speed     
                |                           |                 |                
Clouvider       | London, UK (10G)          | 351 Mbits/sec   | 41.1 Mbits/sec 
Online.net      | Paris, FR (10G)           | 327 Mbits/sec   | 32.0 Mbits/sec 
Hybula          | The Netherlands (40G)     | 484 Mbits/sec   | 427 Mbits/sec  
Uztelecom       | Tashkent, UZ (10G)        | 274 Mbits/sec   | 37.2 Mbits/sec 
Clouvider       | NYC, NY, US (10G)         | 560 Mbits/sec   | 80.5 Mbits/sec 
Clouvider       | Dallas, TX, US (10G)      | 532 Mbits/sec   | 113 Mbits/sec  
Clouvider       | Los Angeles, CA, US (10G) | 637 Mbits/sec   | 629 Mbits/sec  
```
```
Geekbench 5 Benchmark Test:
---------------------------------
Test            | Value                         
                |                               
Single Core     | 601                           
Multi Core      | 1733                          
```
Full Test -> [https://browser.geekbench.com/v5/cpu/18545953](https://browser.geekbench.com/v5/cpu/18545953)


