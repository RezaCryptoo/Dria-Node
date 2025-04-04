# Dria Node Setup Guide 🚀

![Node Status](https://github.com/RezaCryptoo/dria/blob/main/01.JPG?raw=true)


## System Requirements

- **RAM:** 8 GB  

- **CPU:** 8-Core  

- **Storage:** 100 GB  

---
---


## 1️⃣ Update System

```bash
sudo apt update && sudo apt upgrade -y
```

## 2️⃣ Install Required Tools

```bash
sudo apt install apt-transport-https ca-certificates curl software-properties-common -y
```

## 3️⃣ Install Screen

```bash
sudo apt install screen -y
```

## 4️⃣ Install Ollama 

```bash
curl -fsSL https://ollama.com/download/linux | bash
```

```bash
ollama --version
```

## 5️⃣ Download and Install Dria Launcher 

```bash
curl -fsSL https://dria.co/launcher | bash
```

## 6️⃣ Select AI Models 
After installation, configure the models by running:

```bash
dkn-compute-launcher settings
```

Then:
- Click on **Models**.
- Select **Edit model selection**.
- Avoid selecting all models as they take up significant space. Choose only the models you need.

### Suggested Models (For Ollama):
```yaml
qwq:latest
hellord/mxbai-embed-large-v1:f16
qwen2.5-coder:7b-instruct-fp16
mixtral:8x7b
deepseek-r1:7b
phi3.5:3.8b-mini-instruct-fp16
phi3.5:3.8b
llama3.2:3b
llama3.2:1b-text-q4_K_M
llama3.2:1b
llama3.1:latest
driaforall/tiny-agent-a:3b
driaforall/tiny-agent-a:1.5b
driaforall/tiny-agent-a:0.5b
deepseek-r1:1.5b
deepseek-coder:6.7b
```
After selecting the models you need, click **Save**.

## 7️⃣ Enter Referral Code 🏷️
(Optional) If you'd like, you can use my referral code:

```bash
dkn-compute-launcher referrals
```
Referral Code:
```
RteNp6RMZeWWsH2v349V
```

## 8️⃣ Start Dria Node ⚙️
To start the Dria node, use:

```bash
dkn-compute-launcher start
```

When prompted for the **Enter wallet secret key**, input your private key:
- If you already have a wallet, use that key.
- If you don't, create a wallet in **MetaMask** and enter the private key **without the 0x prefix**.

After entering the information and ensuring the models have been downloaded and tested, stop the node with **Ctrl + C**.

## 9️⃣ Run Node Inside Screen 💻
After testing the models, stop the node and run it inside a **Screen** session to keep it running:

```bash
screen -S dria
dkn-compute-launcher start
```

### 🔄 Ensure the Node is Online

✅ Your node should be online and displayed like the example shown in the image!

![Node Status](https://raw.githubusercontent.com/RezaCryptoo/dria/main/02.JPG)

## 🔚 Exit Screen
To exit the screen session:

```bash
Ctrl + A + D
```

## 🔟 Check Node Status and Points 📊
To check the status and points of your node:

### 🧠 Node Status:
[Dria Node Status](https://dria.co/edge-ai/my-node)

### 🔍 Check Points (Search Ethereum Wallet Address):
[Dria Edge AI](https://dria.co/edge-ai)



---

📢 **Follow for Updates:**
- Twitter: [https://x.com/Reza_Cryptoo](https://x.com/Reza_Cryptoo)
- Telegram: [https://t.me/Rezaa_Cryptoo](https://t.me/Rezaa_Cryptoo)

