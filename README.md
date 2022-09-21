cd $HOME &&
pkg upgrade -y &&
pkg update -y &&
pkg install git &&
git clone https://github.com/Ghimball/termux-config.git &&
cd termux-config &&
sh ./install.sh
