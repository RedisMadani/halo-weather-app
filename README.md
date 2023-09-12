# Halo - The Weather App
![preview](https://github.com/RedisMadani/halo-weather-app/assets/136177376/9254e0dc-1f3b-47f1-8dcc-bab31cb516eb)

Halo is a weather app written in python. You can quickly view the
weather in your city and checkout the forecast and historic temperature trends. 
Halo is smart enough to identify your location based on your ip.



## Prerequisites

1. Python 3
1. Pip

## Installation

### Snap

The easiest way to install halo is via snap. 


To install the latest stable version,

````console
user@ubuntu:~$ sudo snap install halo-weather
````

To install the latest build, 
````console
user@ubuntu:~$ sudo snap install --edge halo-weather
````

### Pypi

Make sure the following binaries are present:

````console
user@ubuntu:~$ sudo apt install python3-setuptools pkg-config libcairo2-dev libgirepository1.0-dev gir1.2-gtk-3.0 python3-dev
````

To install the package package using pip,

````console
user@ubuntu:~$ pip3 install halo-weather
````

## Usage
After installing it, you can directly launch it either by searching for Halo among your installed apps, or from terminal by running

````sh-session
$ halo-weather
````

### Running directly from Source

You can directly run this from source.
First, you will need to clone the source code and install the dependencies manually by running

````sh-session
$ git clone https://github.com/cijo7/Halo.git && cd Halo
$ pip3 install -r requirements.txt
````

Then run the python module by executing

````sh-session
$ python3 -m halo
````
