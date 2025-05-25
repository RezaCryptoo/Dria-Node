# Dria Node Setup Guide 🚀
![image](https://github.com/user-attachments/assets/d55fb6a9-2fbf-4c46-84f5-191d922468b5)




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
curl -fsSL https://ollama.com/install.sh | sh
```

```bash
ollama --version
```

## 5️⃣ Download and Install Dria Launcher 

```bash
curl -fsSL https://dria.co/launcher | bash && source ~/.bashrc
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

### Suggested Models :
```yaml
ollama:
[x] llama3.2:1b-instruct-q4_K_M
[x] gemma3:4b

openai:
[x] gpt-4o
[x] gpt-4o-mini

gemini:
[x] gemini-2.5-pro-exp-03-25
[x] gemini-2.0-flash

openrouter:
[x] anthropic/claude-3.5-sonnet
[x] anthropic/claude-3-7-sonnet


```
After selecting the model, choose the “API Keys” option.

You will need 3 API keys.
Get them for free from the following links and enter them:

-OPENAI_API_KEY → https://platform.openai.com/api-keys

-GEMINI_API_KEY → https://aistudio.google.com/app/apikey 

-OPENROUTER_API_KEY → https://openrouter.ai/settings/keys

After entering the keys, click “Save & Exit”

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
```

```bash
dkn-compute-launcher start
```

### 🔄 Ensure the Node is Online

✅ Your node should be online and displayed like the example shown in the image!

![image](https://github.com/user-attachments/assets/66bd0253-bc0f-4a48-b2b5-a8d6010ff259)


## 🔚 Exit Screen
To exit the screen session:


## Ctrl + A + D


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

