# 10-things-to-do-AFTER-Installing-DEBIAN
After this was requested several times I list 10 things to do after installing Debian 9. It covers how to install Debian 9, configure it and properly install Debian Xfce. Although I focus here on Debian 9 Xfce stable, many things to do after installation also work with other Debian / Linux variants.

## 1. Setup SUDO and install Synaptic
These two programs will ease the process of installing programs and performing the administrative task

### Install SUDO
If you set a root account during the Debian 9 installation, you may also want to set uo ```sudo```, to be able to perform administrative tasks as a regular user.

To install ```sudo```, log into your Debian system as root and issue the command:
```apt install sudo```
Now, ```sudo```is installed on your system.
Next, you neet to configure your user to be permitted to use it. To achieve that, add your user to the sudo group
```adduser **yourusername** sudo
