Docker container with appium and android emulator
======

#### Launch the image

``` bash
$ docker run -d -p 8888:4723 --name appium_emulator taraskrysiuk/appium_andr_emulator
```
Appium server will be enable on -> 127.0.0.1:8888 - on host machine

Emulator from host machine -> [container_ip]:5554
