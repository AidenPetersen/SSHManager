# SSHManager
A simple ssh login managing tool. It keeps track of the SSH addresses and descriptions. It does NOT keep track of passwords.

# Installation
You can easily install this program by running 
```bash
$ chmod +x install.sh
# ./install.sh
```
or you could simply run
```bash
# mv sshmgr /usr/local/bin
```
instead.

# Instructions
There are 4 commands
* `sshmgr add` allows you to add an address and a description.
* `sshmgr` or `sshmgr connect` lists avaliable addresses to connect to, then lets you select one to ssh into.
* `sshmgr remove` removes an address that you already added.
* `sshmgr list` lists all of the addresses that you've added.
