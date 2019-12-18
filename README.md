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
sudo apt install git
mkdir code
cd code
git clone git@github.com:robertmash2/rebuild.git

```
