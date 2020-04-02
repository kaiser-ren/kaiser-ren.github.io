---
layout:     post
title:      "Install BlueZ on Windows 10 wsl"
subtitle:   "BlueZ 5.54"
date:       2020-04-01 12:00:00
author:     "Kai"
header-img: "img/post-bg-2020.jpg"
tags:
    - Bluetooth
    - BlueZ
---

* Install Ubuntu, WSL for Windows 10 

    I choose Ubuntu, This is installation link on [Microsoft website](https://docs.microsoft.com/en-us/windows/wsl/install-win10)

- system update and upgrade
```
sudo apt-get update
sudo apt-get upgrade
```

- install dependencies
```
sudo apt-get install -y git bc libusb-dev libdbus-1-dev libglib2.0-dev libudev-dev libical-dev libreadline-dev autoconf bison flex libssl-dev
```

- install BlueZ
```
sudo apt install bluez 
```

