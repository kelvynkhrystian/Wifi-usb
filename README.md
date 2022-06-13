# Wifi-usb
## instalação : vou salvar pq o meu nunca prestava kkk
 
 
### https://askubuntu.com/questions/1162974/wireless-usb-adapter-0bdac811-realtek-semiconductor-corp

sudo apt update
sudo apt install build-essential git dkms bc
git clone https://github.com/brektrou/rtl8821CU.git
cd rtl8821CU
chmod +x dkms-install.sh
sudo ./dkms-install.sh
sudo modprobe 8821cu
