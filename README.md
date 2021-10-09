Linux kernel configurations
===========================
This repository is mainly to store my kernel configurations,
not sure if they are useful to other people but feel free
to check out if you want to.


How to use
----------
Copy to `.config` in linux source directory or load from
`make menuconfig`


`linux-5.14-thinkpad-x1t-quitelight.conf`
-----------------------------------------
### Kernel patches required 
`trackpoint.patch` from https://github.com/da-cali/linux-x1-tablet

### Description
Pretty minimal config that works well for Thinkpad X1 Tablet Gen 3.

It is not perfect, still includes some stuff not required by the
Thinkpad X1 tablet Gen3 but it is lightweight enough.

### Changes
- Added

### Unclaimed hardware

#### Xeon E3-1200 v5/v6 / E3-1500 v5 / 6th/7th/8th Gen Core Processor Gaussian Mixture Model
I have no idea what this is, or what it is supposed to be doing.

#### Sunrise Point-LP PMC
A memory controller, seems like there is no kernel module that supports this (or at least
linux-hardware doesn't know about any)
