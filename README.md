# rpi3-compose-portainer

Run [Portainer](http://portainer.io/) on a Raspberry Pi 3 using docker-compose.

### Prerequisites

* [Raspberry Pi 3](https://www.raspberrypi.org/products/raspberry-pi-3-model-b/)
* A MicroSD-Card with an up-to-date [Raspbian](https://www.raspberrypi.org/downloads/raspbian/) distribution
* [Docker Engine](https://docs.docker.com/)
* [docker-compose](https://docs.docker.com/compose/)

### Step-by-step instructions

```
git clone https://github.com/gmacario/rpi3-compose-portainer
cd rpi3-compose-portainer
docker-compose up -d
```

then browse http://_rpi3-ip-address_:9080/

Copyright 2017, [Gianpaolo Macario](https://gmacario.github.io/)
