# Development Virtual Machines

This repo contains VirtualBox VM definitions for various programming environments that are created using Vagrantfiles.

## What's Commonly installed (all boxes)

* Debian 9.4
* Docker CE
* Gnome (core desktop)
* Visual Studio Code
* Google Chrome

## Pre-requisites

* [Oracle VirtualBox >= 5.2.12](https://www.virtualbox.org/wiki/Downloads)
* [Oracle VM VirtualBox Extension Pack](https://download.virtualbox.org/virtualbox/5.2.12/Oracle_VM_VirtualBox_Extension_Pack-5.2.12.vbox-extpack)
* [Hashicorp Vagrant](https://www.vagrantup.com/downloads.html)
* [Vagrant Disk-size Plugin](https://github.com/sprotheroe/vagrant-disksize)

## Building from Scratch

1. Clone the repo to a directory on your local machine: `git clone https://github.com/twizzledink/vboxes.git`

2. Open a command prompt or terminal and enter: `vagrant up`

3. Wait for your new virtual machine to be built.

4. login with: 'vagrant' for both the user name and password.

## After Setup

I recommend adding a new user for yourself after the fact and removing vagrant user.
