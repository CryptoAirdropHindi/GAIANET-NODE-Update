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
![image](https://github.com/user-attachments/assets/146e5704-3877-4a9d-9b6f-4016489aaa19)
![image](https://github.com/user-attachments/assets/8aae9da0-475c-4811-bf81-78eec420f457)
Now use this below command to get
```
gaianet info
```
![image](https://github.com/user-attachments/assets/fa25a13d-bc17-4d85-8639-7827e072a39f)
## 8. Join Gaia Domain
![image](https://github.com/user-attachments/assets/9aee4e0e-bb23-4b3f-b359-749f21cbe18a)
![image](https://github.com/user-attachments/assets/a0d37945-83f1-4384-a08c-ff00d24b66db)
![image](https://github.com/user-attachments/assets/f0e1c128-628d-44b0-b427-fe3a2fc4af01)
![image](https://github.com/user-attachments/assets/cf609a06-c354-43c2-a3b0-f82574543506)
![image](https://github.com/user-attachments/assets/b0aa74c9-15f3-4098-8390-4706ef32901c)

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
