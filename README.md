# KMS-one2one-call

## @Author: Timothy Lam

```
curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
sudo apt-get install -y nodejs
sudo npm install -g bower
```
```
cd kurento-tutorial-node/kurento-one2one-call
git checkout 6.10.0
npm install
npm start
```

```
rm -r node_modules
npm cache clean
```

```
npm start -- --ws_uri=ws://kms_host:kms_port/kurento
node server.js -- --ws_uri=ws://kms_host:kms_port/kurento
```

```
sudo npm install npm -g
```