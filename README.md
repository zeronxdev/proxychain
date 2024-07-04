# Install
```
git clone https://github.com/zeronxdev/proxychain.git
cd proxychain
./configure --prefix=/usr --sysconfdir=/etc
make
sudo make install
sudo make install-config
sudo ln -s /usr/bin/proxychains4 /usr/bin/proxy
```
# Edit config
```
sudo nano /etc/proxychains.conf
```
