# systemd-glorytun

systemd service files for glorytun client

Copy glorytun.env to /opt/glorytun and copy gt.key in same directory.

## glorytun installation

```
sudo apt install libsodium-dev autoconf automake pkg-config
```

```
git clone https://github.com/angt/glorytun --recursive --branch stable;
cd glorytun
./autogen.sh;
./configure;
make;
sudo make install
```
