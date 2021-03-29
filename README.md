# Systemd Timer Files

This git repository contains example files that were built for the systemd timers video made for the PenguinPropaganda streaming sites.

## firstTest

The firstTest folder contains the files for the first example.

## secondTest

The secondTest folder contains the files for the second example.

## Basic Systemd Commands:

- systemctl start <service or timer file> 
    - will turn on the service.
- systemctl stop <service or timer file> 
    - will turn off the service.
- systemctl enable <service or timer file> 
    - will set a symlink to run the service permanently.
- systemctl disable <service or timer file> 
    - will remove the symlink for the service.

- systemctl status <service or timer file> 
    - will give you detailed status information.
- systemctl list-timers 
    - will give you a list of all of the system timers running


## Some Resources:


An excellent overview of the differences between oneshot and simple services:

[https://trstringer.com/simple-vs-oneshot-systemd-service/](https://trstringer.com/simple-vs-oneshot-systemd-service/)

The archwiki on systemd timers:

[https://wiki.archlinux.org/index.php/Systemd/Timers](https://wiki.archlinux.org/index.php/Systemd/Timers)

The Debian manpage on systemd:

[https://manpages.debian.org/buster/systemd/systemd.service.5.en.html](https://manpages.debian.org/buster/systemd/systemd.service.5.en.html)
