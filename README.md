# 💍 Omnia & Abdelrahman - Wedding Invitation Website

Welcome to the official wedding invitation site for **Omnia & Abdelrahman** – a modern, romantic, and animated digital invite built with love 💖.

🌐 **Live Demo:**  
👉 [Click here to view it live](https://ahmedtahasubs.github.io/Abdelrahman-Omnia/)

---

## ✨ Features

- 💖 Floating animated hearts background
- 🎨 Elegant, responsive design using **Google Fonts** and **Font Awesome**
- 📩 "Send Your Wishes" form that sends messages to a **Telegram group**
- ✅ Stylish confirmation with celebration animation
- 📱 Mobile-friendly and fully responsive layout

---

## 🛠️ Technologies Used

- **HTML5**
- **CSS3** (with animations and gradients)
- **Vanilla JavaScript**
- **Telegram Bot API**
- **Google Fonts** & **Font Awesome**

---

## 📤 How the Telegram Form Works

1. User enters their name and message.
2. On form submit, JavaScript sends a message using the Telegram Bot API.
3. Telegram bot posts the message to a group (chat ID: `-1002539300272`).
4. A success animation appears on the website.

---

## 🔐 Telegram Setup (If You Want to Reuse)

To set up your own Telegram bot:
1. Create a bot using [@BotFather](https://t.me/BotFather)
2. Get your **bot token**
3. Add your bot to your group and promote it to **admin**
4. Get your **group chat ID** via `getUpdates` from the Telegram Bot API
5. Replace in your code:
```js
const telegramToken = 'YOUR_BOT_TOKEN';
const telegramChatId = 'YOUR_CHAT_ID';
