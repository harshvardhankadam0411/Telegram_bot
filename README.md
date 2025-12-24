# Telegram_bot
# 🤖 Telegram Job Alert Bot

A Python-based Telegram bot that automatically fetches the latest **Remote Jobs, AI/ML Jobs, Data Science Jobs, and Government Jobs** using RSS feeds and delivers them directly to users on Telegram.

---

## 🚀 Features

- 📢 Fetches latest job openings from multiple trusted RSS feeds  
- 🌍 Covers:
  - Remote Developer Jobs
  - AI / Machine Learning Jobs
  - Data Science / Data Analyst Jobs
  - Government Jobs (India)
- ⚡ Real-time job updates via Telegram commands
- 🔐 Secure token handling using environment variables
- ☁️ Deployable on cloud platforms (Railway / Render / Replit)

---

## 🛠 Tech Stack

- **Python 3**
- **python-telegram-bot (v20+)**
- **feedparser**
- **Telegram Bot API**

---

## 📂 Project Structure
telegram-job-bot/
│
├── bot.py # Main bot file
├── requirements.txt # Dependencies
├── README.md # Project documentation


---

## 📦 Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/telegram-job-bot.git
cd telegram-job-bot

## Environment Variable Setup
Set your Telegram bot token as an environment variable:
set BOT_TOKEN=your_telegram_bot_token
export BOT_TOKEN=your_telegram_bot_token

## Run the Bot
python bot.py

## Once running, open Telegram and type:
/start
/jobs



