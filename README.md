# bitcointesting
Test Bitcoin with API Tutorial.

## Table of contents
* [Prepare your bitcoin node](#prepare-bitcoin-node)
* [Regression test node](#regression-test-node)
* [Install python and pip](#Install-python-and-pip)
* [Write your first test](#setup)

## Prepare bitcoin node
Get a [Raspberry Pi](https://www.raspberrypi.org). I used following list: 
* Raspberry Pi 4 8Gb RAM.
* Official Raspberry Pi Keyboard.
* SecurePi case for Raspberry Pi 4.
* Pi 4 Power Supply USB-C 5V - 3A.
* Micro HDMI to HDMI adapter.
* Sandisk microSDXC Extreme PRO 64GB 275MB/S UHS-II.
* Some monitor with HDMI connection.

![My Raspberry Pi unpacked](/images/myraspberrypi.png)

Install Ubuntu server on Raspberry Pi (without the optional desktop!). 
When this is done you have a Raspberry pi that is connected in your network. 
Use following [How to install Ubuntu on your Raspberry Pi](https://ubuntu.com/tutorials/how-to-install-ubuntu-on-your-raspberry-pi#1-overview) to do this. 
This tutorial is based on Ubuntu version 20.04.
 
To install bitcoin node on your Raspberry Pi use : [How to install bitcoin-core on Ubuntu](https://snapcraft.io/install/bitcoin-core/ubuntu). 

## Regression Test Node
In order to use an isolated test environment, we will start the bitcoin node as a **regtest** node. Therefore you need to start the bitcoin node as follows on the command prompt:
* bitcoin-core.daemon -regtest -daemon

To interact with your node you can use the RPC cli at the command prompt like so:
* bitcoin-core.cli -regtest getblockchaininfo

## Install Python and pip


## Write your first test
