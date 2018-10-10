# PCA9685

sudo raspi-config //Herramienta de configuracion

sudo i2cdetect -y 1

# Demo de control del Modulo de Python

sudo apt-get install git build-essential python-dev
cd ~
git clone https://github.com/adafruit/Adafruit_Python_PCA9685.git
cd Adafruit_Python_PCA9685
sudo python setup.py install
# if you have python3 installed:
sudo python3 setup.py install
