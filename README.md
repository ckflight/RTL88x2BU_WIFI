# Driver for RTL88x2BU WIFI Adaptors

Tested on raspberry pi with 2020-02-13-raspbian-buster-lite.img and /usr/src/linux-headers-4.19.97+ linux kernel headers.

   # Update raspberry pi and install libraries
   
	sudo apt update
	sudo apt upgrade
	sudo reboot
	sudo apt install flex bison build-essential libncurses5-dev bc python python3 git libelf-dev

   # Install raspberry pi kernel headers:

	sudo apt install raspberrypi-kernel-headers

   # Compile and install rtl8822bu drivers
	
	sudo git clone https://github.com/ckflight/RTL88x2BU_WIFI
	cd rtl8822bu
	sudo nano Makefile

   	sudo make
	sudo make install
	sudo reboot
