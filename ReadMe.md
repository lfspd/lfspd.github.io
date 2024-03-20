## Linux From Scratch PD

This is the set of Linux packages for docker container.

The main features of the distro:
- supposed that applications will run in docker container in batch mode

  Distro does not contain X11, GUIs, mans, locales, tests, tutorials etc.

  <b>It doesn't require any OS. This is "fake" Linux, imitates Linux distribution.</b>
- all packages built from sources
- minimized by size (compiled with size optimization flags + stripped & cleaned)
- set of packages for scientific programming <b>[Readme/packages.md](https://github.com/lfspd/lfspd/blob/main/Readme/packages.md)</b>
- the latest versions of all the packages : glibc, gcc, perl, cmake, python etc.
- packages installed in <code>/usr /usr/local</code>. Greatly simpifies <b>setup scripts</b>
- customizable. Package not needed - comment it out & rebuild.

Based on the Linux From Scratch project https://www.linuxfromscratch.org/

## The LFSPD binaries will be located in 

 <b>[Distros](Distros)</b>
