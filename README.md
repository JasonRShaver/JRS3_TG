# JRS3_TG


* Raspberry Pi 3 B
http://downloads.raspberrypi.org/raspbian/images/raspbian-2017-07-05/
https://etcher.io/

# Enable RDP

```
sudo apt-get install tightvncserver
sudo apt-get install xrdp
```

# Find your IP address

```
sudo ifconfig
```

# Audio Setup

```
sudo apt-get install alsa-utils
sudo apt-get install mpg321 --fix-missing
sudo apt-get install lame

git clone  https://git.assembla.com/portaudio.git
cd portaudio
./configure
make
make install

```

# FFTW

```
sudo apt-get install fftw3
sudo apt-get install libfftw3-dev

git clone https://github.com/gpu-fftw/gpu_fftw.git
cd gpu_fftw
make

```

# TG

```
sudo apt-get install autoconf
sudo apt-get install libtool
sudo apt-get install libgtk-3-dev --fix-missing
sudo apt-get install libgtk2.0-dev

git clone https://github.com/vacaboja/tg.git
cd tg
./autogen.sh
./configure
make
```
https://github.com/bsteinsbo/rpi_touch_driver
