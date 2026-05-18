# 🚀 How to Build Your Own AI Assistant for FREE

### Complete Step-by-Step Guide: Alibaba Cloud + OpenClaw + Telegram

> ⏱️ **Time Required:** 15-20 minutes  
> 💰 **Cost:** FREE (70 million tokens for new users!)  
> 🎯 **Skill Level:** Beginner-friendly

---

## 📋 Table of Contents

1. [Prerequisites](#-prerequisites)
2. [Step 1: Get Your Free Alibaba Cloud API Key](#-step-1-get-your-free-alibaba-cloud-api-key)
3. [Step 2: Create Your Telegram Bot](#-step-2-create-your-telegram-bot)
4. [Step 3: Deploy OpenClaw on Alibaba Cloud](#-step-3-deploy-openclaw-on-alibaba-cloud)
5. [Step 4: Configure & Link Everything](#-step-4-configure-openclaw-and-link-your-accounts)
6. [Step 5: Open the Network Port](#-step-5-open-the-network-port)
7. [Step 6: Start Chatting!](#-step-6-start-chatting)
8. [Troubleshooting](#-troubleshooting)
9. [FAQ](#-faq)

---

## 📝 Prerequisites

Before you begin, make sure you have:

| Requirement | Details |
|---|---|
| ✅ **Alibaba Cloud Account** | New users get **70 million FREE tokens**! [Sign up here](https://www.alibabacloud.com/) |
| ✅ **Telegram Account** | Any account (personal or business) |
| ✅ **Computer** | Windows, Mac, or Linux with a modern web browser |
| ✅ **Internet Connection** | Stable connection for setup |
| ✅ **15-20 Minutes** | Time to complete all steps |

---

## 🔑 Step 1: Get Your Free Alibaba Cloud API Key

### 🎯 What You'll Get:
- **API Key** (starts with `sk-`)
- **70 million FREE tokens** for new users
- Access to Qwen models (Qwen3.6-Plus, Qwen-Max, etc.)

### 📌 Instructions:

#### 1.1 Activate Model Studio

1. Go to [Alibaba Cloud Console](https://home-intl.console.aliyun.com/)
2. Log in to your account (or create one)
3. Search for **"Model Studio"** in the search bar
4. Click on **Model Studio** from the results
5. Click **"Activate Now"** if it's your first time
6. Follow the on-screen instructions to complete activation

![Step 1.1](https://via.placeholder.com/800x400?text=Model+Studio+Activation+Screenshot)

#### 1.2 Navigate to API Keys

1. In the **left-side navigation pane**, find and click **"API Key"**
2. You'll see the API Key management page

![Step 1.2](https://via.placeholder.com/800x400?text=API+Key+Navigation+Screenshot)

#### 1.3 Create a New Key

1. Click the **"Create API Key"** button (usually top-right)
2. A dialog box will appear:
   - **Workspace:** Select the **default workspace**
   - **Description:** Add a note like `"OpenClaw AI Assistant"` (optional but helpful)
3. Click **"OK"**

![Step 1.3](https://via.placeholder.com/800x400?text=Create+API+Key+Dialog+Screenshot)

#### 1.4 Save Your Key Immediately ⚠️

1. The **full API key** will be displayed in a dialog box
2. **COPY IT NOW!** You won't be able to see it again after closing
3. Save it in a secure place:
   - Password manager (recommended)
   - Encrypted notes
   - Secure text file

> 🔐 **Security Tip:** Never share your API key publicly or commit it to GitHub!

**Your key will look like:** `sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx`

![Step 1.4](https://via.placeholder.com/800x400?text=API+Key+Display+Screenshot)

---

## 🤖 Step 2: Create Your Telegram Bot

### 🎯 What You'll Get:
- **Bot Username** (e.g., `@my_alibaba_ai_bot`)
- **Bot Token** (long string of letters and numbers)

### 📌 Instructions:

#### 2.1 Find BotFather

1. Open **Telegram** on your phone or desktop
2. In the search bar, type: `@BotFather`
3. Look for the **blue verified checkmark** ✓
4. Open the chat with BotFather

![Step 2.1](https://via.placeholder.com/800x400?text=BotFather+Search+Screenshot)

#### 2.2 Start the Conversation

1. Click the **"START"** button at the bottom of the chat
2. BotFather will greet you with a welcome message

![Step 2.2](https://via.placeholder.com/800x400?text=BotFather+Start+Screenshot)

#### 2.3 Create a New Bot

1. Send the command: `/newbot`
2. BotFather will ask for a **name** (can be anything):
   - Example: `"My Alibaba AI Assistant"`
3. BotFather will ask for a **username** (must end in `bot`):
   - Example: `my_alibaba_ai_bot`
   - ⚠️ Must be unique! If taken, try variations

![Step 2.3](https://via.placeholder.com/800x400?text=New+Bot+Creation+Screenshot)

#### 2.4 Save Your Bot Token ⚠️

1. BotFather will send a success message with your **bot token**
2. It looks like: `110201543:AAHdqTcvCH1vGWJxfSeofSAs0K5PALDsaw`
3. **Save this token securely** (same as API key!)

> 🔐 **Security Tip:** This token gives full control of your bot. Keep it private!

![Step 2.4](https://via.placeholder.com/800x400?text=Bot+Token+Screenshot)

---

## ☁️ Step 3: Deploy OpenClaw on Alibaba Cloud

### 🎯 What You'll Get:
- **Cloud Server** running 24/7
- **OpenClaw** pre-installed
- **Automatic updates**

### 📌 Instructions:

#### 3.1 Go to Simple Application Server Console

1. Visit [Simple Application Server Console](https://swas.console.aliyun.com/)
2. Log in if prompted

![Step 3.1](https://via.placeholder.com/800x400?text=SAS+Console+Screenshot)

#### 3.2 Create a New Server

1. Click **"Create Server"** or **"Buy Now"**
2. Under **"Image"** section:
   - Select **"Application Image"**
   - Choose **"OpenClaw"** (may be listed as "Clawdbot" or "OpenClaw AI")

![Step 3.2](https://via.placeholder.com/800x400?text=Select+OpenClaw+Image+Screenshot)

#### 3.3 Choose Your Configuration

| Setting | Recommendation | Why |
|---|---|---|
| **Instance Type** | At least **2 GiB RAM** | Ensures stable operation |
| **Region** | **US (Virginia)** or **Singapore** | Better for global audience |
| **Subscription** | **12 months** (default) | Can be changed later |
| **Storage** | Default (40GB+) | Enough for models and data |

> 💡 **Pro Tip:** New users often get **free tier** or heavily discounted first server!

![Step 3.3](https://via.placeholder.com/800x400?text=Server+Configuration+Screenshot)

#### 3.4 Complete the Purchase

1. Review your configuration
2. Click **"Buy Now"** or **"Create"**
3. Follow payment instructions (may be $0 for free tier)
4. Wait **2-5 minutes** for server to provision
5. Server status should show **"Running"**

![Step 3.4](https://via.placeholder.com/800x400?text=Server+Running+Screenshot)

---

## ⚙️ Step 4: Configure OpenClaw and Link Your Accounts

### 🎯 What You'll Do:
- Connect **Alibaba API** (brainpower)
- Connect **Telegram Bot** (body/interface)
- Configure **OpenClaw** (brain)

### 📌 Instructions:

#### 4.1 Open Server Dashboard

1. Go back to [Simple Application Server Console](https://swas.console.aliyun.com/)
2. Find your new server in the list
3. Click the **Instance ID** to open details

![Step 4.1](https://via.placeholder.com/800x400?text=Server+Dashboard+Screenshot)

#### 4.2 Enter Configuration Wizard

1. Click the **"Application Details"** tab
2. Find **"Steps to Use OpenClaw"** section
3. Click **"Execute Command"** under **"Configure OpenClaw"**
4. A **black terminal window** will open in your browser

![Step 4.2](https://via.placeholder.com/800x400?text=Terminal+Window+Screenshot)

#### 4.3 Configure the Model

1. The setup script will start automatically
2. When prompted for **Model Provider**, select:
   - **Alibaba Cloud** / **Bailian** / **Dashscope**
3. When prompted for **API Key**:
   - Paste the key from **Step 1**
   - Press **Enter**

![Step 4.3](https://via.placeholder.com/800x400?text=API+Key+Input+Screenshot)

#### 4.4 Add Telegram Channel

1. Script will ask: **"Configure channels?"**
2. Type: `telegram` (or the corresponding number)
3. Press **Enter**
4. When prompted for **Bot Token**:
   - Paste the token from **Step 2**
   - Press **Enter**
5. Confirm your settings when asked

![Step 4.4](https://via.placeholder.com/800x400?text=Telegram+Config+Screenshot)

#### 4.5 Complete Setup

1. Script will validate your credentials
2. You'll see **"Setup Complete!"** or similar message
3. Note down your **server IP** or **domain**
4. Terminal can be closed

---

## 🔓 Step 5: Open the Network Port

### 🎯 Why This Matters:
For Telegram to communicate with your AI assistant, a specific network port on your server must be open. This is like opening a door for incoming messages!

### 📌 Instructions:

#### 5.1 Execute the Open Port Command

1. Go back to the **Simple Application Server Console**
2. Find your server and click the **Instance ID**
3. Click the **"Application Details"** tab
4. Find **"Steps to Use OpenClaw"** section
5. Click **"Execute Command"** under the **"Open Port"** step
6. This will automatically configure your server's firewall
7. Wait for **"Port opened successfully!"** confirmation

![Step 5.1](https://via.placeholder.com/800x400?text=Open+Port+Command+Screenshot)

> 🔐 **Security Note:** Only the required port is opened. Your server remains secure!

#### 5.2 Verify Port is Open

1. The command will show which port was opened (usually `18789` for OpenClaw)
2. You should see a **success message**
3. If you see an error, try running the command again
4. Contact support if issues persist

---

## ✅ Step 6: Start Chatting!

### 🎉 Congratulations! Your setup is now complete!

### 📌 Instructions:

#### 6.1 Find Your Bot on Telegram

1. Open the **Telegram app** (phone or desktop)
2. Search for your bot using the **username** you created
   - Example: `@my_alibaba_ai_bot`
3. Open the chat
4. Click the **"START"** button at the bottom

![Step 6.1](https://via.placeholder.com/800x400?text=Bot+Chat+Screenshot)

#### 6.2 Send Your First Message

1. Type a simple message: `Hello!` or `Hi there!`
2. Wait a few seconds
3. **Your AI assistant should respond!** 🎉
4. It's powered by **Alibaba Cloud's free tokens!**

#### 6.3 Test Different Features

Try these test messages:
- `/help` - See available commands
- `/status` - Check bot status  
- `"What's the weather like?"` - Ask a question
- `"Help me write an email"` - Request assistance
- `"Tell me a joke"` - Have some fun!
- `"What can you do?"` - Learn capabilities

![Step 6.2](https://via.placeholder.com/800x400?text=Test+Message+Screenshot)

#### 6.4 What If It Doesn't Work?

If your bot doesn't respond:
1. ✅ Check server status is **"Running"**
2. ✅ Verify you completed **Step 5** (Open Port)
3. ✅ Confirm bot token is correct
4. ✅ Try `/start` command again
5. ✅ Check **Troubleshooting** section below

---

## 🎊 You Did It!

Your AI assistant is now **live and running 24/7**! 🚀

### What You've Built:
- ✅ Cloud-hosted AI assistant
- ✅ Powered by Alibaba Cloud (70M free tokens!)
- ✅ Accessible via Telegram
- ✅ Running on OpenClaw framework
- ✅ Ready to customize and expand!

### Next Steps:
- 🎨 **Customize** your bot's personality
- 🔗 **Add integrations** (email, calendar, etc.)
- 📊 **Monitor usage** in Alibaba Cloud console
- 🌐 **Share** with friends and community
- 💡 **Build advanced features** with OpenClaw

---

## 🔧 Troubleshooting

### ❌ Problem: API Key Not Working

**Solutions:**
- ✅ Check key starts with `sk-`
- ✅ Ensure no extra spaces when copying
- ✅ Verify Model Studio is activated
- ✅ Check for typos

### ❌ Problem: Bot Doesn't Respond

**Solutions:**
- ✅ Verify bot token is correct
- ✅ Check server is "Running"
- ✅ Ensure bot is not blocked
- ✅ Try `/start` command again

### ❌ Problem: Server Won't Start

**Solutions:**
- ✅ Check payment is complete
- ✅ Verify region availability
- ✅ Contact Alibaba Cloud support
- ✅ Try different region

### ❌ Problem: Configuration Script Fails

**Solutions:**
- ✅ Refresh the terminal window
- ✅ Check internet connection
- ✅ Verify credentials again
- ✅ Restart server and try again

---

## ❓ FAQ

### Q: Is this really free?
**A:** Yes! New Alibaba Cloud users get **70 million free tokens**. That's enough for thousands of conversations!

### Q: What happens when I use all free tokens?
**A:** You can purchase more tokens at very low rates, or create a new account.

### Q: Can I customize my bot?
**A:** Yes! OpenClaw supports custom prompts, personalities, and integrations.

### Q: Is my data secure?
**A:** Yes! Your API keys and tokens are stored securely on your server. Never share them publicly.

### Q: Can I use this on multiple devices?
**A:** Yes! Telegram works on phone, desktop, and web. Your bot is cloud-based.

### Q: What models can I use?
**A:** Qwen3.6-Plus, Qwen-Max, Qwen-Flash, and more! All accessible via Alibaba Cloud.

### Q: How do I update my bot?
**A:** OpenClaw has auto-update features. Check the server dashboard for updates.

---

## 🎉 Congratulations!

You now have your own **AI Assistant** running 24/7 on the cloud! 🚀

### What's Next?

- 🎨 **Customize** your bot's personality
- 🔗 **Add more integrations** (email, calendar, etc.)
- 📊 **Monitor usage** in Alibaba Cloud console
- 🌐 **Share** your bot with friends
- 💡 **Build advanced features** with OpenClaw

---

## 📚 Additional Resources

- [OpenClaw Documentation](https://docs.openclaw.ai)
- [Alibaba Cloud Model Studio](https://www.alibabacloud.com/product/model-studio)
- [Telegram Bot API](https://core.telegram.org/bots/api)
- [Qwen Model Documentation](https://help.aliyun.com/zh/model-studio/)

---

## 🤝 Need Help?

- 📧 **Email:** support@web4city.xyz
- 💬 **Telegram:** @web4city
- 🐙 **GitHub Issues:** [Create an issue](https://github.com/web4city/web4city-launch/issues)

---

## ⭐ Support This Project

If this guide helped you, please:

1. ⭐ **Star** this repository
2. 🍴 **Fork** it to customize
3. 📢 **Share** with friends
4. 💬 **Join** our community

---

**Built with 💙 by Web4City** | [https://web4city.xyz](https://web4city.xyz)

*Last Updated: May 18, 2026*
