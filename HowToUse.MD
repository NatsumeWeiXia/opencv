#HOW TO USE

sudo -i
mkdir /usr/include/ffmpeg
cd /usr/include/ffmpeg
ln -sf /usr/include/x86_64-linux-gnu/libavcodec/*.h ./
ln -sf /usr/include/x86_64-linux-gnu/libavformat/*.h ./
ln -sf /usr/include/x86_64-linux-gnu/libswscale/*.h ./
exit (sudo 終了)

sudo apt-get install python-software-properties
sudo add-apt-repository ppa:ubuntu-toolchain-r/test
sudo apt-get update
sudo apt-get install gcc-4.9
sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-4.9 50
