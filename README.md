# PPA for BlueChi

## Installation

```bash
# Add BlueChi PPA
$ curl -s --compressed "https://raw.githubusercontent.com/engelmi/bluechi-ppa/main/deb/KEY.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/bluechi.gpg >/dev/null
$ curl -s --compressed -o /etc/apt/sources.list.d/bluechi.list "https://raw.githubusercontent.com/engelmi/bluechi-ppa/main/deb/bluechi.list"
$ sudo apt update

# Install BlueChi packages
$ sudo apt install bluechi-controller bluechi-agent bluechictl
```
