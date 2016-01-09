# bitshiftvariations
Port to perl from the the bitshiftvariations program in c written by Rob Miles

To run this you need to have perl installed which comes by default with Windows and Linux.

RUNNING UNDER WINDOWS:

  You need to download [SoX](http://sox.sourceforge.net/) which will translate the raw output of the perl script to audio. To run this script place all
  the files in this repository in the same directory as SoX and launch the provided batch script to run the perl script.

RUNNING UNDER LINUX:

  You need `aplay` to hear anything from this script. It can be installed using 'pacman -S alsa-lib alsa-utils' on Arch Linux
  and using `sudo apt-get install alsa alsa-utils`. You can then use the provided bash script to run the perl script.
