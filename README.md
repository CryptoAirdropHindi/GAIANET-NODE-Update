<h2 align=center>GAIANET-NODE-Update</h2>

1. First you have to stop the Node

Use this command
```
docker stop gaianet && docker rm gaianet
```

- Let's install the node update:
- Default model
2. Use the following command to download the latest version of the Gaia node:
```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```
- Download a Very Large LLM file

3. Run the command printed on the terminal to set up the environment path, it is started with source.
```
source/root/bashrc
```
4. Use this command to run the GaiaNet node on a different port.
```
gaianet config --port 8047
```
5. used for fine-tuning or configuring the LLaMA-3.2-3b model.
```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/refs/heads/main/llama-3.2-3b-instruct/config.json
```
6. Start Node
```
gaianet start
```
7. Now use this below command to get `node-info`
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
