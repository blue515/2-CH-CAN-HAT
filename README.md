# 2-CH-CAN-HAT
**安裝必要函式庫**
* 安裝BCM2835
> $wget http://www.airspayce.com/mikem/bcm2835/bcm2835-1.60.tar.gz
> $tar zxvf bcm2835-1.60.tar.gz
> $cd bcm2835-1.60/
> $sudo ./configure
> $sudo make
> $sudo make check
> $sudo make install
* 安裝wiringPi(64-bit Rpi)
> #用指令複製資源包到樹莓派
> $wget https://www.waveshare.net/w/upload/8/8c/WiringPi-master.zip
> #安裝解壓縮環境(可選)
> $sudo apt-get install unzip
> #進入資料夾位置，進行解壓縮
> $unzip WiringPi-master.zip
> #進入資料夾目錄(WiringPi-master中)
> $cd WiringPi-master/
> #執行sudo ./build
> $sudo ./build
> #若上一指令失敗則執行，再執行上一指令(可選)
> $chmod +x ./build
* 安裝Python(python3)
> $sudo apt-get update
> $sudo apt-get install python3-pip
> $sudo apt-get install python3-pil
> $sudo apt-get install python3-numpy
> $sudo pip3 install RPi.GPIO
> $sudo pip3 install spidev
> $sudo pip3 install python-can
