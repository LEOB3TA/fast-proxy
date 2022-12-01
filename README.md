# fast-proxy
This is a little script to make ssh-proxy with the terminal of Macos


# Index

- [How to install](#how-to-install)
- [Usage](#usage)
- [Contribute](#contribute)
- [License](#license)

# How to install

## Dependencies

This script use the macos networksetup command

## Instructions

- Download the code from this repo
- Make the code executable with: 
```bash
chmod +x macproxy
```
- Execute it with:
```bash
./macproxy
```

# Usage

```bash
usage: macproxy [-h] [-n <network-services>] [-P <source-port>] [-p <ssh-port>] [-w] [-s] <user@ssh.proxy>
```

- -h : help
- -n : one of network services from "networksetup -listallnetworkservice"
- -P : port where you want your proxy in localhost (default: 9090)
- -p : port to connect to ssh server (default: 22)
- -w : turn on web proxy (http/https)
- -s : turn on socks proxy

# Contribute
 
 Open a issue or open a pull request
 
 ## TODO
 
 Add compatibility with other OS and browser; make this script runnable in background
 
 # License
 
 [CC0](https://creativecommons.org/share-your-work/public-domain/cc0/)


