# Driver for RTL88x2BU WIFI Adaptors

   # Update raspberry pi and install libraries

	sudo apt-get update
	sudo apt update
	sudo apt upgrade
	sudo reboot
	sudo apt-get install flex bison
	sudo apt-get install build-essential libncurses5-dev bc python git
	sudo apt install libelf-dev

   # Install raspberry pi kernel headers:

	sudo apt install raspberrypi-kernel-headers

   # Install rtl8822bu drivers
	
	sudo git clone https://github.com/ckflight/RTL88x2BU_WIFI
	cd rtl8822bu
	sudo nano Makefile

   	sudo make
	sudo make install
	sudo reboot
