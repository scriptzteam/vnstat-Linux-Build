# vnstat-Linux-Build

```
apt update
apt upgrade
apt install build-essential libsqlite3-dev libgd-dev git
git clone https://github.com/vergoh/vnstat.git
cd vnstat
./configure --prefix=/usr --sysconfdir=/etc && make && make install
vnstatd -d
```
