# Tattoo


### installation
```
curl -sL https://deb.nodesource.com/setup_13.x | sudo -E bash -
sudo apt install nodejs -y
sudo apt install npm -y
sudo npm install -g npm
hash -d npm
```

```
git clone https://github.com/facebook/watchman.git
cd watchman/
git checkout v4.9.0
sudo apt install -y libssl-dev autoconf automake libtool build-essential python-dev pkg-config
./autogen.sh
./configure
make
sudo make install
```

```
sudo npm install -g react-native-cli
sudo npm install -g react-viro-cli
```


### initialization
```
sudo react-viro init tattoo --verbose
sudo npm install --unsafe-perm -g ngrok
sudo chown -R davy tattoo
```


### testing
http://localhost:4040/status