### openwrt_bpi-r4_mtk_builder

Run on Ubuntu 24.04 or later

`sudo apt update`

`sudo apt install build-essential clang flex bison g++ gawk gcc-multilib g++-multilib gettext git libncurses-dev libssl-dev python3-setuptools rsync swig unzip zlib1g-dev file wget`

`git clone https://github.com/Rahzadan/openwrt_bpi-r4_mtk_builder.git`

`chmod 776 -R openwrt_bpi-r4_mtk_builder`

`cd openwrt_bpi-r4_mtk_builder`

`./build1.sh`

After build completes, run:

`./build2.sh`
