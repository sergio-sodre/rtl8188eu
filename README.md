# rtl8188eu
Realtek Semiconductor Corp. RTL8188EUS 802.11n Wireless Network Adapter
git clone git://github.com/lwfinger/rtl8188eu
cd rtl8188eu
make
sudo make install
sudo depmod -a
sudo update-initramfs -u
sudo modprobe 8188eu
