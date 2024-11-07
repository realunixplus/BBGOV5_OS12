# BBGOV5_OS12
1. console=ttyS0:115200
2. tx,rx,grnd
3. C77A12 | C76A12 | C72A12 | C71A6 | C72A6
4. gcc version 4.9.x 20150123

# UART Slell Command and Function
1. aml_sysrecovery : Burning with amlogic format package from partition sysrecovery
2. amlmmc : AMLMMC sub system
3. amlnf : aml nand sub-system
4. amlnf_test : AMLPHYNAND sub-system
5. autoscr : run script from memory
6. bootsys : bootsys - boot system
7. cbusreg : cbus register read/write
8. crc32 : checksum calculation
9. cvbs : CVBS sub-system
10. efuse : efuse read/write data commands
11. efuse_user : efuse user space read write ops
12. emmc : EMMC sub system
13. env : environment handling commands
14. exit : exit script
15. fatinfo : print information about filesystem
16. fatload : load binary file from a dos filesystem
17. fatls : list files in a directory (default /)
18. fatsize : determine a file's size
19. fdt : flattened device tree utility commands
20. forceupdate : forceupdate
21. get_rebootmode : get reboot mode
22. icache : enable or disable instruction cache
23. keyman : Unify key ops interfaces based dts cfg
24. keyunify : key unify sub-system
25. loop : infinite loop on address range
26. macreg : ethernet mac register read/write/dump
27. mmc : MMC sub system
28. mmcinfo : display MMC info
29. mw : memory write (fill)
30. normal : normal - enter norm mode
31. open_scp_log : print SCP messgage
32. osd : osd sub-system
33. printenv : print environment variables
34. readconf : readconf- read config from conf partition
35. reboot : set reboot mode and reboot system
36. reset : Perform RESET of the CPU
37. rsvmem : reserve memory
38. run : run commands in an environment variable
39. safe : safe - enter safe mode
40. sdc_burn : Burning with amlogic format package in sdmmc
41. sdc_update : Burning a partition with image file in sdmmc card
42. set_usb_boot : set usb boot mode
43. setenv : set environment variables
44. systemoff : system off
45. update : Enter v2 usbburning mode
46. upgrade : burn image into flash
47. upgrade_d : burn image into flash
48. usb : USB sub-system
49. usb_burn : Burning with amlogic format package in usb
50. usb_update : Burning a partition with image file in usb host
51. usbboot : boot from USB device

# Virtual kernel memory layout
1. modules : 0xffffff8000000000 - 0xffffff8008000000   (   128 MB)
2. fixed   : 0xffffffbefe7fd000 - 0xffffffbefec00000   (  4108 KB)
3. memory  : 0xffffffc000000000 - 0xffffffc080000000   (  2048 MB)



