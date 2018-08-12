Debian APT repository
This repository hosts packages for Debian.

To use the repository:

1. Add my GPG key:
```
# apt-key adv --keyserver hkps://hkps.pool.sks-keyservers.net --recv-keys 0x3F7A2FA142E434FE06622560B05266B2EB68F001
```

2. Add this line to `/etc/apt/sources.list`:
```
deb https://amurzeau.github.io/apt-repository unstable main
```

3. Update apt and install
```sh
# apt-get update
# apt-get install XXX
```

