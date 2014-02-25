ns-allinone-2.35 Mac OS X 10.9 installer patch
============================================

This is a patch for The Network Simulator (ns-2) all-in-one package v2.35 installer, for Mac OS 10.9.

I ran into trouble when trying to install this now-3-year-old package to Mac OS X 10.9.1, due to some configuration errors. I searched for a good solution to this problem and I ran into [this](https://www.mail-archive.com/ns-users@isi.edu/msg20094.html "Brian Adamson's guide") page.


I followed the instructions and it worked properly. I wanted to automate this process for future use, so I changed the instal script a bit and added 4 patches.

To use this install script:

1. Copy all 5 files (the 'install64' script and 4x .patch files) to the unpacked folder of ns-allinone-2.35 package
2. Run the script with: `sudo ./install64`

Disclaimer: I only tested on my system (Mac OS X 10.9.1, Cygwin not installed, RMBP 15"), so I can't guarantee it will work for you. This software is provided as-is and I am not liable for any change/damage inflicted upon your system through the use of this software.

I would like to thank Brian Adamson for making his solution public and taking his time to explain it step-by-step.
