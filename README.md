# LTW GCR Developer Utilities and "How To"

Various utility code snippets and reference materials for LTW GCR developers.

# Useful References

Markdown cheatsheet - https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

# Dev Environment - Emulated

# Raspberry Pi

Setup a Raspberry Pi emulated testing environment:  http://www.makeuseof.com/tag/emulate-raspberry-pi-pc/

# Ubuntu Mate 

Setup a VMWare Ubuntu Mate on Mac testing environment:

Download https://ubuntu-mate.org/download/ Ubuntu MATE 16.04.3 LTS

Install into VMWare Fusion VM

Run

```
sudo apt-get update
sudo apt-get upgrade
```
Create snapshot of configured VM to use as baseline

Do testing from a restored main snapshot

# Target Environment

# Raspberry Pi

Setup a Raspberry Pi 3 using this software and associated instructions https://ubuntu-mate.org/raspberry-pi/

Run install script with parameters to specify **development** or **production** modes (development will install tools used to support debugging and testing, production is only the software required to run the services)
