<div align="center">
  <img src="https://files.catbox.moe/as1b4c.png" alt="KING-M" width="300"/>
</div>

<p align="center">
  <a href="#"><img title="KING-M" src="https://img.shields.io/badge/KING--M-your%20whatsapp%20manager?colorA=%230017ff&colorB=%23ff0099&style=for-the-badge"></a>
</p>

---

## 🚀 Deployment Set Up

Follow these steps to get started.

### 1. **Fork the Repository**
<p>
  <a href="https://github.com/sesco001/KING-MD/fork" target="_blank">
    <img src="https://img.shields.io/badge/Fork--Repository-black?style=for-the-badge&logo=github" alt="Fork KING-MD on GitHub">
  </a>
</p>

### 2. **Get Session ID**
<p>
  <a href="https://peace-hub-mcbo.onrender.com/pair" target="_blank">
    <img src="https://img.shields.io/badge/Get%20Pair--Code-animeblue?style=for-the-badge&logo=whatsapp" alt="Pair Code">
  </a>
</p>

### 3. **Choose Server**

| **Heroku (Automatic)** | **Panel / VPS (Manual)** |
|:----------------------:|:------------------------:|
| <a href="https://veriiiiii.vercel.app/" target="_blank"><img src="https://img.shields.io/badge/Deploy--to--Heroku-indigo?style=for-the-badge&logo=heroku" alt="Deploy to Heroku"></a> | <a href="#panel-setup"><img src="https://img.shields.io/badge/Deploy--on--Panel-blue?style=for-the-badge&logo=linux" alt="Deploy on Panel"></a> |

---

## <a name="panel-setup"></a>💻 Panel Deployment Guide

Use this guide if you are deploying on **Pterodactyl, Plesk, Render, or a VPS**.

### **Step 1: Upload Files**
* Download this repository or clone it into your panel.
* Ensure **Node.js 18+** is installed on your server.

### **Step 2: Create Configuration File**
1.  Go to your file manager.
2.  Create a new file named `.env`.
3.  **Copy the text below**, paste it into the file, and fill in your details:

```bash
# ==========================================
#        KING-MD CONFIGURATION
# ==========================================

# 1. SESSION ID (Required)
# Paste your long session code here (after pairing).
SESSION="YOUR_SESSION_ID_HERE"

# 2. BOT OWNER
# Put your phone number (No '+' or spaces).
# Example: 254712345678
DEV="254712345678"

# 3. COUNTRY CODE
# Your country code (e.g., 254 for Kenya).
CODE="254"

# 4. BOT NAME
# Give your bot a custom name.
APP_NAME="KING-M"

# 5. HEROKU API (Optional)
# Leave blank if you are not using Heroku features.
HEROKU_API=""
