# ppa-helper
A helper program for adding ppa's in ubuntu.

A program writen in python to make adding ppa's easier on Ubuntu distros.
The program will try using your distro for the given ppa's and fallback to the latest version before your distro if not available.

Usage:

* Open terminal (Ctrl + Alt + T)
```bash
* sudo apt-get install git
* On Ubuntu 17.10-beta2 neither make nor python are not intalled so run sudo apt-get install make python
* git clone https://github.com/robertapengelly/ppa-helper.git
* cd ppa-helper
* make install
* example: ppa-helper ppa:notepadqq-team/notepadqq ppa:otto-kesselgulasch/gimp \
           gnome3-team/gnome3-staging gnome3-team/gnome3
```