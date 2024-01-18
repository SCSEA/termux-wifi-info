#Installation

apt update && apt upgrade -y

pkg install termux-api -y

apt install python2

apt install git

git clone https://github.com/SCSEA/termux-wifi-info.git

cd termux-wifi-info

chmod +x *

python2 wifi-info.py
