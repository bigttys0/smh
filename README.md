https://www.youtube.com/c/RECESSIM/playlists

https://wiki.recessim.com/view/Gr-smart_meters_Setup_Guide
Download Ubuntu 20.04 iso - 
Use Live or Install into Virtualbox (2GB mem, 60GB hdd)



RTL-SDR - 
https://www.rtl-sdr.com/rtl-sdr-quick-start-guide/

sudo apt-get update
sudo apt-get install rtl-sdr

Some helpful links for before and after rtl-sdr is installed - 
http://manpages.ubuntu.com/manpages/trusty/man1/rtl_test.1.html
https://www.scivision.dev/rtlsdr-quickstart-linux/
https://osmocom.org/projects/rtl-sdr/wiki#Gnuradio-Source

Gnuradio Companion -
https://wiki.gnuradio.org/index.php/UbuntuInstall
If GRC throws Python mod not found error - https://wiki.gnuradio.org/index.php/ModuleNotFoundError

https://reveng.sourceforge.io/
https://reveng.sourceforge.io/readme.htm
Compile for Linux
   - gcc -O3 -Wall -ansi -c bmpbit.c cli.c model.c poly.c preset.c \reveng.c
   - cd contrib
   - gcc -O3 -Wall -ansi -c getopt.c
   - cd ..
   - gcc -o reveng bmpbit.o cli.o model.o poly.o preset.o reveng.o \contrib/getopt.o
