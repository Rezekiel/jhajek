# Tolling Assignment Advanced

## Objectives and Outcomes

* Understand how to add custom virtual machines to the Vagrant platform
* Understand the advantages of using Vagrant and Packer
* Configure specific software needed to use Big Data tooling platform, Spark, Hadoop, and Mariadb in virtual machines

## Packer and Vagrant Build Steps

* From the commandline, ```cd``` into the build directory of the packer-vagrant-build-scripts repo you cloned.
  * ```packer-vagrant-build-scripts\packer\build```
* Find the build artifacts, there should be one *.box file, similar to ```ubuntu-vanilla-18043-server-virtualbox-1580565828.box```
  * Your number will be different as it is a timestamp
* Add this box to Vagrant
  * Initialize and connect to this virtual machine.

## Inside Vagrant Box Steps

* change host name, add initials and system for local
* install mariadb server
* install java 8 openjdk
  * make sure it is default jdk
* Install Spark 2.4
* Install Hadoop 2.9.3
* configure .bashrc file to add path
  * demonstrate with version commands
* Configure Vagrant Paths, memory, and cpus

## Deliverable

* Proceed to finish the last part of chapter 2 lecture
  * Walking through the command line Spark exercises
  