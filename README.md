### CamHD Compute Engine Server Build ###

Notes and links researching the new CamHD Compute Engine server.

#### Motherboard ####

1x [Supermicro X10DAC](http://www.supermicro.com/products/motherboard/xeon/c600/x10dac.cfm)
 - [http://a.co/87nLQiv](http://a.co/87nLQiv)
 - [review](https://www.servethehome.com/supermicro-x10dac-workstation-motherboard-sas3-review)
 - onboard 8-port 12 Gb/s SAS 3008 HBA
 - $508

#### Case ####

1x [Supermicro SuperChassis 846BA-R920B](http://www.supermicro.com/products/chassis/4U/846/SC846BA-R920B)
 - [http://a.co/6cDFI4Q](http://a.co/6cDFI4Q)
 - $1249

1x [Supermicro 2x2.5" Hotswap Adapter MCP-220-84606-0N](http://www.wiredzone.com/supermicro-components-hard-drives-accessories-mcp-220-84606-0n-10022043)
 - $60

#### Processors ####

2x [Intel Xeon E5-2699 v4](https://ark.intel.com/products/91317/Intel-Xeon-Processor-E5-2699-v4-55M-Cache-2_20-GHz)
 - [http://a.co/i1vo6oW](http://a.co/i1vo6oW)
 - [https://www.newegg.com/Product/Product.aspx?Item=9SIADGX5SX2234](https://www.newegg.com/Product/Product.aspx?Item=9SIADGX5SX2234)
 - E5-2696 v4 (OEM tray version) is supposedly the same as the 2699, but rated for 150W
 - this processor originally released at about $4k msrp, but no retail versions appear to be available
 - most available units appear to be "new pulls" or tray oem processors from unknown retailers
 - $1800/ea (OEM tray)

#### Heat Sinks ####

2x [Supermicro 4U Active CPU Heat Sink Socket LGA2011 (SNK-P0050AP4)](http://store.supermicro.com/heatsink/4u-active-cpu-cooler-snk-p0050ap4.html)
 - $43/ea

#### Memory ####

8x [Samsung M393A4K40BB1-CRC 32GB DDR4-2400 LP ECC Reg Server Memory](http://a.co/1hc4rOO)
 - $314/ea

#### HBAs ####

2x [Microsemi Adaptec HBA 1000-8i](https://storage.microsemi.com/en-us/support/sas/sas/aha-1000-8i)
 - two internal mini SAS HD (SFF-8643)
 - hardware raid not required.
 - $200/ea

#### Cabling ####

6x [Internal Mini SAS HD Cable SFF-8087 (backplane) --> SFF-8643 (HBAs)](http://a.co/eJLChUG)
 - $17/ea

#### Hard Drives / Volumes ####

2x [SAMSUNG 850 PRO 256GB SSD MZ-7KE256BW](https://www.newegg.com/Product/Product.aspx?Item=N82E16820147360)
 - $140/ea
 - mount: /
 - ext4 RAID 1 (mdadm)

14x [Seagate Enterprise 10TB SAS 12Gb/s 0000NM0206](https://www.newegg.com/Product/Product.aspx?Item=1Z4-002P-00509)
 - $416/ea
 - mount: /data
 - btrfs RAID 6

2x [WD Gold Enterprise 10TB SATA 6Gb/s WD101KRYZ](https://www.newegg.com/Product/Product.aspx?Item=N82E16822235131)
 - $0/ea (own)
 - mount: /home
 - btrfs RAID 1

#### UPS ####

??

#### Summary ####

| Item | Qty | Each | Total |
| --- | ---: | ---: | ---: |
| Supermicro motherboard (X10DAC) | 1 | 508 | 508 |
| Supermicro chassis (846BA-R920B) | 1 | 1,249 | 1,249 |
| Supermicro hotswap adapter (MCP-220-84606-0N) | 1 | 60 | 60 |
| Intel Xeon E5-2699 v4 | 2 | 1,800 | 3,600 |
| Supermicro heat sink (SNK-P0050AP4) | 2 | 43 | 86 |
| Samsung memory (M393A4K40BB1-CRC) | 8 | 314 | 2,512 |
| Adaptec HBA (1000-8i) | 2 | 200 | 400 |
| SAS cabling (SFF-8087 --> SFF-8643) | 6 | 17 | 102 |
| Samsung SSD (MZ-7KE256BW) | 2 | 140 | 280 |
| Seagate 10 TB SAS drives (0000NM0206) | 14 | 416 | 5,824 |
| WD 10 TB SATA drves (WD101KRYZ) | 2 | 0 | 0 |
| | | | **$14,621** |


