# Welcome To CS 296-25

## Intro

This course will teach you about functional programming in Clojure as well as the parallelisms involved in data structure implementation in the functional paradigm of programming vs the Object-Oriented one you have seen throughout CS 225.

## Environment Setup

### Using The Provided Image (Recommended)

To use the already pre-setup image we have given you, you will first need to do the following.

1. Install VirtualBox [VirtualBox Download Page](https://www.virtualbox.org/wiki/Downloads)
1. Install Vagrant [Vagrant Download Page](https://www.vagrantup.com/downloads.html)
1. Now, run the command `cd cs296-25git`
1. To turn on your vagrant box, run `vagrant up`
1. To access your vagrant machine, run `ssh vagrant@127.0.0.1 -p 2222` If you want to launch applications graphically, please run `ssh -X vagrant@127.0.0.1 -p 2222`. For Windows users, please use PuTTY. [How To Use PuTTY](http://www.geo.mtu.edu/geoschem/docs/putty_install.html) For Mac users who want graphical applications, please use the following. [Install XQuartz](https://www.xquartz.org/)
1. When prompted for a password, the password is `vagrant`
1. You will now have a prompt that has all the Clojure-releated tools you need and an editor called Spacemacs. The base distribution is Arch Linux and you can install anything you want. Your assignment files are located in `/vagrant` To access them, just run `cd /vagrant`

### Natively On Your Own Machine (Not So Recommended)

We recommend you install OpenJDK 8 (not Oracle JDK) and then install `lein`.

[Leiningen Homepage](https://leiningen.org/)

### Setting Up Lein And Clojure On EWS (Not Tested)

Theoretically, you just have to follow the `lein` installation instructions on EWS.

[Leiningen Homepage](https://leiningen.org/)
