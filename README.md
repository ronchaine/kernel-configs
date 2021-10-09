Linux kernel configurations
===========================
This repository is mainly to archive kernel configurations,
not sure if they are useful to other people but feel free
to check out if you want to.

I've often ran into a situation I would like to know how
a specific kernel was configured to handle a situation,
and I though it would be useful to have an archive for
kernel configurations.

How to use
----------
Pick a file and Copy to `.config` in linux source directory or
load from `make menuconfig`.

Or use as a reference with your `grep`-equivalent.

Directory structure
-------------------
### distro-defaults

Default configurations for various distribution kernel packages,
mostly for reference.


### laptop-specific

These are configurations for specific laptops, that are quite
minimal and not guaranteed to work on any other system
