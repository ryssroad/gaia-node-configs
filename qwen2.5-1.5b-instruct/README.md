# A Qwen-2.5-1.5b-Instruct node 

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init with the Qwen2.5-1.5b-Instruct model

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/qwen2.5-1.5b-instruct/config.json
```

**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.



