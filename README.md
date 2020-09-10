Mad Max - The Road Warrior
========================

Setup a wireguard server using pihole for DNS on Ubuntu 20.04

Prerequisites
------------

* Ubuntu 20.04 Server installed
* Firewall allow port 22
* Add ssh public key to `${home_directory}/.ssh/authorized_keys`

Installation
------------

  bash <(curl -s https://raw.githubusercontent.com/damonmorgan/mad-max/master/road-warrior)

Add another wireguard client
------------

  bash <(curl -s https://raw.githubusercontent.com/damonmorgan/mad-max/master/wireguard)

What is installed and configured
-----------------

* docker and docker-compose (running pihole, traefik and heimdall)
* wireguard server
* sshd
