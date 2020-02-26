# easywall

[![GitHub Actions Build](https://img.shields.io/github/workflow/status/jpylypiw/easywall/python-testing)](https://github.com/jpylypiw/easywall/actions)
[![CodeCov Coverage](https://img.shields.io/codecov/c/gh/jpylypiw/easywall)](https://codecov.io/gh/jpylypiw/easywall)
[![GitHub license](https://img.shields.io/github/license/jpylypiw/easywall)](https://github.com/jpylypiw/easywall/blob/master/LICENSE)
[![GitHub repo size](https://img.shields.io/github/repo-size/jpylypiw/easywall.svg)](https://github.com/jpylypiw/easywall)
[![Project Version](https://img.shields.io/badge/release-alpha%20testing-red.svg)](https://github.com/jpylypiw/easywall)
[![Discord Support](https://img.shields.io/discord/333980251921186818)](https://discord.gg/CUj2sFb)
[![Beerpay](https://img.shields.io/beerpay/jpylypiw/easywall)](https://beerpay.io/jpylypiw/easywall)

Today **Firewalls** are more important than years before. Hackers and Bots are trying to invade your server. So what to do against it?
Set up a firewall! But which one? **IPTables** is the strongest firewall in **Linux** environments. So we wanted to make IPTables usable by everyone. We created a simple **Web Interface** for IPTables so everyone can install and use it on his / her server.

## Demo

> We are currently setting up a self resetting demo server.\*

## Features

- **Blacklist for completely blocking an IPV4 / IPV6 Address**
- **Whitelist to allow complete traffic from a specific IP**
- **Opening TCP and UDP Ports**
- **Opening TCP and UDP Port Ranges**
- **Automatic Reset of Firewall Settings on connection loss or bad firewall settings**

## Install

We provide extensive instructions on our [installation](https://github.com/jpylypiw/easywall/blob/master/INSTALL.md) page.  
You can find a script for automatic downloading and installation.

## Documentation

Check the **[easywall wiki](https://github.com/jpylypiw/easywall/wiki)**.

## License

easywall is GNU General Public License v3.0.

It re-distributes other open-source tools and libraries. Please check its [License](https://github.com/jpylypiw/easywall/blob/master/LICENSE).

## Screenshots

![Screenshot 1: Home Page on Mobile](https://i.imgur.com/vEneFWK.png)
![Screenshot 2: Main Menu on Mobile](https://i.imgur.com/zxCcPQW.png)
![Screenshot 3: Ports Page Upper Part](https://i.imgur.com/qYjxXNZ.png)
![Screenshot 4: Ports Page Lower Part](https://i.imgur.com/zdN0oRu.png)
![Screenshot 5: Apply Page with Automatic Timeout Reset](https://i.imgur.com/BaWMkZD.png)

## DEV Environment

To create a development environment you have to execute the following command after cloning the repository:

```bash
python3 setup.py develop
```
