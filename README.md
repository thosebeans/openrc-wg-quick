# openrc-wg-quick

## Description
openrc-wg-quick is a small tool to automatically create openrc services for wg-quick configurations.  
It replaces systemd's wg-quick units on openrc-based systems

## Usage
```sh
git clone https://github.com/thosebeans/openrc-wg-quick.git
cd openrc-wg-quick
./openrc-wg-quick wg0
#wg-quick@wg0
#/etc/init.d/wg-quick@wg0
```
