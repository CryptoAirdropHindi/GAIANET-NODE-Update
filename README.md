<h2 align=center>GAIANET-NODE-Update by CryptoAirdropHindi</h2>

## 1. First you have to stop the Node

Use this command
```
rm -rf gaianet && docker stop gaianet && docker rm gaianet
```

- Let's install the node update:
- Default model
## 2. Use the following command to download the latest version of the Gaia node:
```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```
- Download a Very Large LLM file

## 3. Run the command printed on the terminal to set up the environment path, it is started with source.
```
source/root/bashrc
```
## 4. Use this command to run the GaiaNet node on a different port.
```
gaianet config --port 8047
```
## 5. Start Node
```
gaianet init
```
```
screen -S Gaia
```
```
gaianet start
```
## 6. Now use this below command to get `node-info`
```
gaianet info
```
- Copy `Node ID` and `Device ID` and then write `exit` to detach from this container
- Visit [Gaianet Site](https://www.gaianet.ai/setting/nodes) and then connect your wallet

- Now click on `connect new node`, here enter your `Node ID` and `Device ID` and then click on `Join` button
- After that, customize this URL using your `Node ID`, visit the modified URL, and start chatting with it to increase `throughput`
```
 https://YOUR_NODE_ID.us.gaianet.network
```
- **The more you chat, the higher the `throughput`, and the more Gaianet points you will earn.**
## Back Up `nodeid.json` (Imp)
- Use the below command and then save its somewhere (vvip)
```
cat gaianet/nodeid.json 
```

---
"Great, all set! If you have any questions, don’t hesitate to ask in our Telegram channel."
Or if you'd like something more friendly and engaging:
- Telegram - https://t.me/Crypto_airdropHM
- Youtube - https://www.youtube.com/@CryptoAirdropHindi6
