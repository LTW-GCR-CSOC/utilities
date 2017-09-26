![Global Cybersecurity Resource](https://github.com/LTW-GCR-CSOC/csoc-installation-scripts/blob/master/githubGCRheader.png?raw=true "Global Cybersecurity Resource")   
# LTW GCR Developer Utilities and "How To"

Various utility code snippets and reference materials for LTW GCR developers.

# Useful References

  * [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
  * [Sample service scripts for debian](https://github.com/wyhasany/sample-service-script)
    * [Example service script for dionaea](https://blog.honeynet.org.my/2010/02/14/dionaea-auto-start-script-on-ubuntu/)
  * [Open source project template for github](https://github.com/cfpb/open-source-project-template)
  * [Malware hunting project](https://github.com/phage-nz/malware-hunting)
  * [Securing systlogd](http://www.rsyslog.com/doc/v8-stable/tutorials/tls_cert_summary.html)
  * [Install Ubuntu Mate on EC2](https://alexanderzeitler.com/articles/deploying-ubuntu-mate-desktop-as-developer-environment-on-aws-ec2/)

# Dev Environment - Emulated

## Raspberry Pi

Setup a Raspberry Pi emulated testing environment:  http://www.makeuseof.com/tag/emulate-raspberry-pi-pc/

## Ubuntu Mate 

Setup a VMWare Ubuntu Mate on Mac testing environment:

Download https://ubuntu-mate.org/download/ Ubuntu MATE 16.04.3 LTS

Install into VMWare Fusion VM

Install VMWare Tools 
```
sudo apt-get install open-vm-tools
```

Update OS

```
sudo apt-get update
sudo apt-get upgrade
```
Create of snapshot of configured VM using the VMWare Fusion "Take Snapshot" function to use as a baseline for testing - always test on a copy of that master snapshot

Do testing from a restored master snapshot

# Target Environment

## Raspberry Pi

Setup a Raspberry Pi 3 using this software and associated instructions https://ubuntu-mate.org/raspberry-pi/

Run install script with parameters to specify **development** or **production** modes (development will install tools used to support debugging and testing, production is only the software required to run the services)
