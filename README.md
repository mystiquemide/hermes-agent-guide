# Hermes-agent-guide

<img width="1280" height="1280" alt="image" src="https://github.com/user-attachments/assets/cf6bd284-e80f-4638-b388-3fcffbb20a05" />


# This guide will help anyone set up a Hermes agent on Nous research.
Hermes Agent is an autonomous agent that lives on your server, remembers what it learns, and gets more capable the longer it runs.

# Requirements
Linux / macOS / WSL
# Steps
## Step 1
## WSL Setup
Head to WSL on Windows, open the terminal
```
wsl
```
## Step 2
## Installing Dependencies
Clone the repo to install dependencies
```
curl -fsSL https://raw.githubusercontent.com/NousResearch/hermes-agent/main/scripts/install.sh | bash
```
<img width="1387" height="1020" alt="image" src="https://github.com/user-attachments/assets/c923cec9-b7fb-4bbc-8b0c-2f2f2aa5e22d" />

<img width="1387" height="1020" alt="WindowsTerminal_GCQxMRjOPx" src="https://github.com/user-attachments/assets/ae54a5e3-25cf-48a0-8a6a-e8841466eaee" />


## Step 3
## Setting up your Hermes agent
- Select ENTER to proceed
- Select Provider: this will enable you to connect to your chat model
- Select Open router and click on Open router
- Go to [Openrouterai](https://openrouter.ai) to get an API key
- Sign up with GitHub on [Openrouterai](https://openrouter.ai)
- Click on API keys
- Click on Create API key
- Enter a name
- Copy your API key

  <img width="1387" height="1020" alt="WindowsTerminal_F2glvDfnEn" src="https://github.com/user-attachments/assets/60e969df-3909-4935-b89a-976e5fbe32c8" />

<img width="1547" height="418" alt="image" src="https://github.com/user-attachments/assets/02488868-de6b-4c72-985d-abe5550c60e4" />

## Step 4 
## Model Setting
- Select model
- Choose nvidia/nemotron-3-super-120b-a12b:free
- Click on Enter

  <img width="1387" height="1020" alt="WindowsTerminal_f5lLj22KbQ" src="https://github.com/user-attachments/assets/dbd5fc76-3421-4e72-bdbb-805836ad31c6" />

  ## Step 5
  ## TTS settings
  - Select TTS provider
  - Keep Current
  - Select Terminal backend
  - Choose Local
 
    <img width="1387" height="1020" alt="WindowsTerminal_xdDuEvL6i3" src="https://github.com/user-attachments/assets/f39d5038-54fe-4ff8-b013-b2bbdb980725" />


    <img width="1069" height="352" alt="WindowsTerminal_7lRLB12And" src="https://github.com/user-attachments/assets/d543bb2e-a9e5-4c1a-8e35-6675e55efadc" />

## Step 6
## Agent Settings
- Click on Enter on Max Iterations ( 60 )
- Press ENTER to use the default tool
- Press ENTER for context compression

  <img width="1351" height="542" alt="WindowsTerminal_bu66bjEUbw" src="https://github.com/user-attachments/assets/3c93718a-4112-4b23-b93d-3b48cdbcc147" />


  <img width="1291" height="317" alt="WindowsTerminal_jz0ZLmtLCo" src="https://github.com/user-attachments/assets/da22eb34-14f8-4f2e-bba9-2dc7f8edb0a3" />

  <img width="1296" height="294" alt="WindowsTerminal_evyD5jj4TG" src="https://github.com/user-attachments/assets/7038f22b-4f63-4851-b4ac-621d13a23561" />

## Step 7
## Session Reset
- Select Inactivity plus Daily Reset
- Press ENTER for inactivity timeout
- Press ENTER for the daily reset hour

<img width="1387" height="1020" alt="WindowsTerminal_TJtFrp7mIj" src="https://github.com/user-attachments/assets/f6c983c9-6a53-4c5c-b6af-fb18435358f1" />

<img width="1367" height="496" alt="WindowsTerminal_bwMtd0wjOi" src="https://github.com/user-attachments/assets/64e5ea04-83c4-463f-990c-4a70b95b2186" />

<img width="1360" height="239" alt="WindowsTerminal_iBo5DZYEoK" src="https://github.com/user-attachments/assets/46b0a9c3-51f5-4741-8faf-aea552d10996" />

## Step 8
## Messaging Platforms
- Select Y to use the Telegram bot and press enter
- Create a bot via @BotFather on Telegram
- Click on Start
- Enter a name for your bot. I used HERMES CHAT BOT
- Now let's choose a username for your bot. It must end in `bot`
- Done, your bot will be created
- Let's link our bot using the bot token
- Copy the bot token and paste it into your terminal and press ENTER. Do not worry, it will not display the token
- Restrict who can use your token
- Go to @userinfobot on Telegram
- It will reply with your numeric ID (e.g., 123456789)
- Copy it and paste it into your terminal
- Click on Y to use ID for home channel and press ENTER
- Click on N to set up the Discord Bot
- Click on N to set up Stack Bot
- Click on N to set up Matrix Bot
- Click on N to set up MatterMost Bot
- Click on N to set up WhatsApp
- click on N to set up GitHub, GitLab, etc
- Done

NT: Why I said N for the rest of the socials is cause they are less important, telegram is the most important of them all

<img width="1303" height="280" alt="WindowsTerminal_htEbdi4Ubd" src="https://github.com/user-attachments/assets/9469b750-e06a-48d2-92f2-7901ded44093" />

<img width="1327" height="295" alt="jpR40h8H6W" src="https://github.com/user-attachments/assets/b630a4b4-024f-49af-9587-bd87b642e372" />

<img width="948" height="526" alt="Telegram_TLc6Bx7jFz" src="https://github.com/user-attachments/assets/bae56f88-0dd5-43be-a3b2-2ad51b53617f" />

<img width="1348" height="379" alt="brave_WwxlTVzfgj" src="https://github.com/user-attachments/assets/efc4c914-6144-41fc-a1e9-a3ab1e11933f" />

<img width="1065" height="222" alt="WindowsTerminal_zjFyLq3Un4" src="https://github.com/user-attachments/assets/b5399dbf-5e79-4e88-ad0d-722344214384" />

<img width="1159" height="330" alt="WindowsTerminal_H3IDdg3oAc" src="https://github.com/user-attachments/assets/a79aab48-8ffe-4d8b-9a02-aa5191b7b83b" />

<img width="1132" height="212" alt="WindowsTerminal_2B36qsLpcD" src="https://github.com/user-attachments/assets/91046ca1-0545-46be-af25-2ec4651e87da" />

## Discord Bot Setup

- Go to https://discord.com/developers/applications → New Application → give it a name
- Click Bot on the left → Reset Token → copy your bot token
- Scroll to Privileged Gateway Intents → toggle ON Message Content Intent → Save Changes
- Go to Installation → Guild Install → pick scopes `bot` and `applications.commands` → copy the invite link
- Open the link, invite the bot to your server
- In Discord: Settings → Advanced → Developer Mode ON → right-click your name → Copy User ID
- Run `hermes gateway setup` → select Discord → paste your token and user ID when asked
- Done. Tag the bot in any channel to start chatting.

- <img width="2072" height="1039" alt="image" src="https://github.com/user-attachments/assets/25edf52c-4078-47b3-be34-5ad12b4b21d2" />

<img width="2072" height="1039" alt="image" src="https://github.com/user-attachments/assets/5a0d7b68-4ae1-433f-a3fa-e499221e0c57" />



## Step 9
## Install the gateway as a systemd service? (runs in background, starts on boot)
- Click on Y and press ENTER to use the default
- Click on Y to start the service

<img width="1368" height="633" alt="WindowsTerminal_82SyVBIYbA" src="https://github.com/user-attachments/assets/dce23c7c-9472-4e06-ab82-0e9a2fcd4693" />

## Step 10
## SYSTEM MD SERVICES FOR HERMES
- You will see TOOLS for CLI, screenshot it and keep it for future references
- Press `ESC` to cancel
- Choose a provider, select ENTER to use the default
- Select FAL AI for image generation, head to [FALAI](https://fal.ai/dashboard/keys)
- Click on sign up with github
- Click on for myself and create with AI tools, and click on continue
- Click on Add Key
- Enter the relevant details
- Create key
- Copy your key and save it
- Paste it into your terminal and press ENTER
- Choose a voice provider, select the default to use your device's TTS
- Select Search Provider, select [FIRECRAWL](https://firecrawl.dev)
- Sign up on [FIRECRAWL](https://firecrawl.dev) with GitHub, use a VPN if the site does not respond
- Complete the onboarding tasks
- Choose the free plan
- Click on API keys
- Click on Create
- Enter the details
- Copy the key and paste it into your terminal and press ENTER
- Done
## SYSTEM MD SERVICES IS FULLY CONFIGURED

<img width="1387" height="1020" alt="WindowsTerminal_poHLMMivWu" src="https://github.com/user-attachments/assets/597720ab-59b1-4da5-8b41-1f6e35610c30" />

<img width="1387" height="1020" alt="WindowsTerminal_gJ4WWQ0fPb" src="https://github.com/user-attachments/assets/7a213419-b47d-4011-a861-6bab13fe1c57" />

<img width="2074" height="1099" alt="image" src="https://github.com/user-attachments/assets/c15f94ff-3661-4850-98d6-87d187bf9cc1" />

<img width="2074" height="1099" alt="image" src="https://github.com/user-attachments/assets/32bf4216-9223-434e-af2d-331f7d75df93" />

<img width="801" height="744" alt="chrome_rnGJJL82eN" src="https://github.com/user-attachments/assets/cb733ce2-a245-411f-97eb-bbed527a0ab3" />

<img width="2074" height="1099" alt="chrome_fSrHJivbfz" src="https://github.com/user-attachments/assets/26a88fbe-b25c-468c-b7c1-538310a5e583" />

<img width="1377" height="333" alt="WindowsTerminal_AH0DcW4P8r" src="https://github.com/user-attachments/assets/1981484c-33ed-4513-b030-27dd0a419182" />

<img width="1387" height="1020" alt="WindowsTerminal_AndpMXHgxB" src="https://github.com/user-attachments/assets/84543381-1819-4ed3-aeb9-b46594a5968d" />

<img width="1387" height="1020" alt="WindowsTerminal_bljtInvQfV" src="https://github.com/user-attachments/assets/e6852ad0-42e9-42c1-ab62-3f937164a1c7" />

<img width="2074" height="1099" alt="chrome_w5dbPa4ZsV" src="https://github.com/user-attachments/assets/302a49cf-a856-470e-b0bc-5b079ab50212" />

<img width="2074" height="1099" alt="chrome_B4ktW0D1sx" src="https://github.com/user-attachments/assets/6c9d824e-3748-4bf3-80ab-3c323f98ddcd" />

<img width="1388" height="604" alt="chrome_Ci6yccgZEJ" src="https://github.com/user-attachments/assets/bef7349c-6a78-4bba-b20c-17f7c363f2f7" />




## Step 11
## Interacting with HERMES
- You will see `Would you like to install the gateway as a background service? `
- Click on Y
- HERMES INSTALLATION IS COMPLETE AND IS LIVE ON TELEGRAM
- Reload your shell to use the `hermes` command:
  
<img width="1387" height="1020" alt="image" src="https://github.com/user-attachments/assets/68dff61d-8383-4c31-8363-6277533ac2b5" />

<img width="1387" height="1020" alt="WindowsTerminal_tE4ie7Fk8L" src="https://github.com/user-attachments/assets/22b969b5-ebbe-44f5-aef6-f19930a5316d" />

<img width="1328" height="1151" alt="iBnAciNFPk" src="https://github.com/user-attachments/assets/49ebb639-98bc-4587-8896-a164c162ee5d" />

## Step 12
## Interacting with HEMRES PART 2
- Use Hermes to start chatting with your agent
- Enter any input to start your message
- Done, your Hermes agent is successfully installed, and you can start chatting and it also works on your desktop background

<img width="1382" height="607" alt="WindowsTerminal_uWasLNXZ9g" src="https://github.com/user-attachments/assets/b9baad72-5600-4dc8-abf1-aebde85d19d3" />

<img width="1387" height="1020" alt="WindowsTerminal_xQCSbokcHP" src="https://github.com/user-attachments/assets/e5edc2b1-b28d-477b-a450-3105777ab1ba" />

## Optional: Run Hermes on a VPS (24/7)

Want Hermes online 24/7 even when your PC is off? Put it on a cheap VPS.

This guide uses [Tencent Cloud Lighthouse](https://console.tencentcloud.com/lighthouse), it's affordable and beginner-friendly.

- Go to https://console.tencentcloud.com/lighthouse → click **Sign Up Free** to create an account
- After logging in, click **Buy** and select **Lighthouse**
- Pick a region close to you and choose **Ubuntu** as the OS
- Choose a plan, the Linux Starter (2 vCPU, 2 GB RAM) works perfectly and is very cheap
- Complete payment and wait for the instance to deploy
- Once ready, click **Log In** on your instance to open the web terminal, or SSH in
- Run the install:
  ```
  curl -fsSL https://raw.githubusercontent.com/NousResearch/hermes-agent/main/scripts/install.sh | bash
  ```
- Go through the setup wizard, same as on your local machine
- Run `hermes gateway setup` to connect Telegram or Discord
- Start it in the background:
  ```
  hermes gateway --daemon
  ```
- Done. Your agent is live 24/7, chat with it anytime from your phone.

## If you have any questions, dm [MYSTIQUEMIDE](https://x.com/MystiqueMide)

# MADE WITH ❤️❤️ BY [MYSTIQUEMIDE](https://x.com/MystiqueMide)
