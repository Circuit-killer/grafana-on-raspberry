# grafana-on-raspberry [![Release](https://img.shields.io/github/release/fg2it/grafana-on-raspberry.svg)](https://github.com/fg2it/grafana-on-raspberry/releases/latest)
[Grafana](http://grafana.org) *unofficial* packages for arm based raspberry pi (1, 2 and 3).

Grafana doesn't provide packages for arm, so the purpose of this repo is to provide notes
on how you can build Grafana yourself and packages I build according to these notes.

Deb packages and tarballs are available from the github
[release](https://github.com/fg2it/grafana-on-raspberry/releases) section (only pi 2 and pi 3) and
most recent ones are also available from a deb repo on bintray (including for pi 1). See the
[wiki](https://github.com/fg2it/grafana-on-raspberry/wiki) for details.

## `old-versions`
This directory contains notes for versions from 2.1.2 up to 3.1.1 for wheezy and jessie distro.

## `docker/`
The `docker/` folder contains `Dockerfile` and related files to build images
running grafana for armhf.


Grafana [license](https://github.com/grafana/grafana/blob/master/LICENSE.md).
