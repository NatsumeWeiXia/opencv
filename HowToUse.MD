# HOW TO USE

## libs
```
sudo apt-get autoremove libopencv-dev python-opencv
sudo apt-get install cmake build-essential
sudo apt-get install libgtk2.0-dev libgtkglext1-dev
sudo apt-get install libqt4-dev libpangox-1.0-dev libxmu-dev libxmu-headers
sudo apt-get install zlib1g-dev libjpeg-dev libpng12-dev libtiff4-dev libjasper-dev libgphoto2-2-dev
sudo apt-get install libdc1394-22 libdc1394-22-dev libavcodec-dev libavformat-dev libavresample-dev libgstreamer1.0-dev libgstreamer-plugins-base1.0-dev libgstreamer-plugins-good1.0-dev libswscale-dev libtheora-dev libvorbis-dev libxvidcore-dev libx264-dev libopencore-amrnb-dev libopencore-amrwb-dev libv4l-dev v4l-utils libxine2-dev libmp3lame-dev libfaac-dev yasm
linear algebra: sudo apt-get install libeigen3-dev
sudo apt-get install libtbb-dev ocl-icd-opencl-dev opencl-headers

apt-get installbuild-essential 
apt-get install cmake git libgtk2.0-dev pkg-config libavcodec-dev libavformat-dev libswscale-dev 
apt-get install python-dev python-numpy libtbb2 libtbb-dev libjpeg-dev libpng-dev libtiff-dev libjasper-dev libdc1394-22-dev 
apt-get install libavcodec-dev libavformat-dev libswscale-dev libv4l-dev liblapacke-dev 
apt-get install libxvidcore-dev libx264-dev 
apt-get install libatlas-base-dev gfortran 
apt-get install ffmpeg
```
## get
```
git clone
```
## so
```
mkdir builds
cd builds
cmake -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=/usr/local/opencv ..
make
make install
```
## jar
```
cmake -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=/usr/local/opencv -D BUILD_TESTS=OFF ..
make -j8
make install
```
## videoio.h notfound
```
mkdir /usr/include/ffmpeg
cd /usr/include/ffmpeg
ln -sf /usr/include/x86_64-linux-gnu/libavcodec/*.h ./
ln -sf /usr/include/x86_64-linux-gnu/libavformat/*.h ./
ln -sf /usr/include/x86_64-linux-gnu/libswscale/*.h ./

sudo apt-get install python-software-properties
sudo add-apt-repository ppa:ubuntu-toolchain-r/test
sudo apt-get update
sudo apt-get install gcc-4.9
sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-4.9 50
```
**notwork on my machine**

## ERRORS

link error when new VideoCapture();

**didn't solve**
