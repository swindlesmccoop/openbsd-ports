# Usage
[Set up the ports tree](https://www.openbsd.org/faq/ports/ports.html#PortsFetch)
```
git clone https://git.cbps.xyz/swindlesmccoop/openbsd-ports/
doas cp -r openbsd-ports/* /usr/ports/mystuff/
cd /usr/ports/mystuff/[package]
su
make
```