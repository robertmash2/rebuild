# rebuild

# Ubuntu 18.04
after install (fresh boot):

copy backed up folders from home:
.ssh
code
etc.



```
cd ~
wget https://download.jetbrains.com/python/pycharm-professional-2019.3.tar.gz?_ga=2.194651501.1183697466.1576636042-1424499299.1576636042
tar -xf pycharm-professional-2019.3.tar.gz
pycharm-professional-2019.3.tar.gz

wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
./Miniconda3-latest-Linux-x86_64.sh
rm Miniconda3-latest-Linux-x86_64.sh

sudo apt update
sudo apt install git coolkey libpcsclite1 pcscd pcsc-tools vim
wget --no-check-certificate https://dl.google.com/linux/linux_signing_key.pub 
sudo apt-key add linux_signing_key.pub

#mozilla/prefs/security/load ... /usr/lib/pkcs.../pkcs.so.11

mkdir code
cd code
git clone git@github.com:robertmash2/rebuild.git


#install nvidia driver
# latest version: https://launchpad.net/~graphics-drivers/+archive/ubuntu/ppa
# https://linuxhint.com/ubuntu_nvidia_ppa/
sudo add-apt-repository ppa:graphics-drivers/ppa
sudo apt install nvidia-driver-430





```
