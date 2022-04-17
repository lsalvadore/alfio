# Alfio # 

Alfio is an rc service for managing services at boot time. It is
specifically designed for FreeBSD, but it might work on any other system
using rc.

This is how Alfio's menu looks at boot time (assuming you have 5 profiles
called "default", "no\_network", "job", "home" and "testing")
```
==================================================
=========== Alfio --- Services manager ===========
==================================================

Please select a profile:

1. default
2. no_network
3. job
4. home
5. testing

Insert a valid profile number:
```
# Installation #

It is recommended to install it through ports (`sysutils/alfio`) or
through packages (`pkg install alfio`).

If for some reason you need to install Alfio manually, then you should
replace every occurence of %%LOCALBASE%% in Alfio's script with the value
of the LOCALBASE variable on your system. You might want to replace the
%%LOCALBASE%% string in the man page as well.
