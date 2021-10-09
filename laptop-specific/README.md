Laptop configurations
=====================

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
- Moved some modules to builtins and disabled bay trail (f537cacab66f690cb264c986f87748fe31535a05)

### Unclaimed hardware

#### Xeon E3-1200 v5/v6 / E3-1500 v5 / 6th/7th/8th Gen Core Processor Gaussian Mixture Model
I have no idea what this is, or what it is supposed to be doing.

#### Sunrise Point-LP PMC
A memory controller, seems like there is no kernel module that supports this (or at least
linux-hardware doesn't know about any)
