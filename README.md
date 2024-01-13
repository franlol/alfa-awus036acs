######
VIDEO:
######

https://www.youtube.com/watch?v=hEXwOkyYNL0&ab_channel=DavidBombal


################
INSTALL DRIVERS:
################

$ sudo apt update
$ sudo apt upgrade -y
$ sudo apt dist-upgrade -y
$ sudo reboot now
$ sudo apt update
$ sudo apt install realtek-rtl88xxau-dkms
$ sudo apt install dkms
$ git clone https://github.com/aircrack-ng/rtl8812au
$ cd rtl8812au/
$ make
$ sudo make install
$ lsusb
$ iwconfig


#####
TEST:
#####

sudo wifite


############################
Install VBox extension pack:
############################

$ wget https://download.virtualbox.org/virtualbox/7.0.12/Oracle_VM_VirtualBox_Extension_Pack-7.0.12.vbox-extpack

$ sudo VBoxManage extpack install ./Oracle_VM_VirtualBox_Extension_Pack-7.0.12.vbox-extpack


########################
if still not work check:
########################

git clone https://github.com/morrownr/8821au-20210708.git

