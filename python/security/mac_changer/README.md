# MAC changer script

## Installation

The script uses ifconfig to change MAC adress therefore you should use root permissions.

`python setup.py install`

## Usage

Try --help param

### Setting random(-r)  MAC for wlan0(-i)

`$: macc -i wlan0 -r` 

### Setting specific(-m) MAC for eth0:

`$: mac -i eth0 -m 80:44:3f:6e:85:8g`
