# VZSpeed
OpenVZ container network usage measuring tool

## Setup

Either clone or wget the vzspeed file into /bin/ so that you can access it directly as a command. An alternative is to wget/clone it elsewhere and then add a entry into your .bashrc file. You'll need to chmod file as well, chmod +x should be enough.

## Usage

    vzspeed <VMID>

For example,

    [root@test ~]# vzspeed 100
    100| TX: 32087 kB/s RX: 3 kB/s
    100| TX: 8171 kB/s RX: 0 kB/s
    100| TX: 15508 kB/s RX: 2 kB/s

