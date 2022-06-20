<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Mumble Server for YunoHost

[![Integration level](https://dash.yunohost.org/integration/mumbleserver.svg)](https://dash.yunohost.org/appci/app/mumbleserver) ![Working status](https://ci-apps.yunohost.org/ci/badges/mumbleserver.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/mumbleserver.maintain.svg)  
[![Install Mumble Server with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mumbleserver)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Mumble Server quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Mumble is a free, open source, low latency, high quality voice chat application. Mumble was the first VoIP application to establish true low latency voice communication over a decade ago. But low latency and gaming are not the only use cases it shines in.


**Shipped version:** 1.3.0~ynh3

## Screenshots

![Screenshot of Mumble Server](./doc/screenshots/Mumble.png)

## Disclaimers / important information

## Setup

This package installs the Debian package and configures it with given settings. Password and other usefull information will be sent by email after installation.

- [Add the admin](http://wiki.mumble.info/wiki/Murmurguide#Connecting_to_Murmur_Server)

## Config
If you need to change password of the server/superuser
1- edit `/var/www/mumbleserver/mumble-server.ini`
2- remove (or change) the password for serverpassword=
3- restart mumbleserver

## Documentation and resources

* Official app website: <https://mumble.info>
* Official admin documentation: <https://wiki.mumble.info/wiki/Main_Page>
* Upstream app code repository: <https://github.com/mumble-voip/mumble>
* YunoHost documentation for this app: <https://yunohost.org/app_mumbleserver>
* Report a bug: <https://github.com/YunoHost-Apps/mumbleserver_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/mumbleserver_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/mumbleserver_ynh/tree/testing --debug
or
sudo yunohost app upgrade mumbleserver -u https://github.com/YunoHost-Apps/mumbleserver_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
