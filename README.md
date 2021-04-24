# cyberdeck
sick deck, chummer

# instructions for setting up a sick cyberdeck in 242 steps

## required installs
apt get git vim

## install and configure display

cd ~
sudo apt-get install -y git python3-pip
sudo pip3 install --upgrade adafruit-python-shell click==7.0
git clone https://github.com/adafruit/Raspberry-Pi-Installer-Scripts.git
cd Raspberry-Pi-Installer-Scripts

### for console mode
sudo python3 adafruit-pitft.py --display=35r --rotation=90 --install-type=console
### for gui mode
sudo python3 adafruit-pitft.py --display=35r --rotation=90 --install-type=fbcp