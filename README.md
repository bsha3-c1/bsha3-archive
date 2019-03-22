# BSHA3 wallets

Windows Wallet:
b3lwma_win.zip

Linux Wallet instructions:

Installing packages:

sudo apt-get update
sudo apt install build-essential gcc bsdmainutils libevent-dev libboost-all-dev pkg-config autoconf libssl-dev wget

Installing Berkeley DB:

wget http://download.oracle.com/berkeley-db/db-4.8.30.zip
unzip db-4.8.30.zip
cd db-4.8.30
cd build_unix/
../dist/configure --prefix=/usr/local --enable-cxx
make
make install

Ubuntu 16.04:
bsha3_u1604.zip

ubuntu 18.04:
bsha3_u1804.zip
