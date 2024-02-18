pkg update && pkg upgrade

pkg install git

pkg install python
rm -rf TUHIN-GREEN

git clone --depth=1 https://github.com/zeyxos/TUHIN-GREEN.git

cd TUHIN-GREEN

python3 GREEN.py
