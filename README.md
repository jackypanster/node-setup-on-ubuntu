+ Download the node.js dist

```bash
wget https://nodejs.org/dist/v7.3.0/node-v7.3.0-linux-x64.tar.gz
```

+ Install the node.js binary

```bash
cd /usr/local
sudo tar --strip-components 1 -xzf /home/ubuntu/node-v7.3.0-linux-x64.tar.gz
```

+ Verify

```bash
node -v
npm -v
```

+ Configure registry

```bash
sudo npm install --registry http://registry.cnpmjs.org
```
