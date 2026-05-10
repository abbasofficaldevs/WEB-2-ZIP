<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:ff512f,100:7b2ff7&height=220&section=header&text=WEB-2-ZIP&fontSize=58&fontColor=ffffff&fontAlignY=38&desc=Download%20Any%20Website%20Source%20Code%20as%20ZIP&descAlignY=60&descSize=18&animation=fadeIn" />

<br>

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=24&pause=1000&color=FF512F&center=true&vCenter=true&width=900&lines=WEB-2-ZIP+%F0%9F%9A%80;Download+Any+Website+Source+Code+Instantly+%F0%9F%93%A6;FastAPI+%7C+AioHTTP+%7C+AsyncIO+Powered+%F0%9F%94%A5;Download+HTML+CSS+JS+Images+Fonts+Automatically+%E2%9A%A1;Vercel+Ready+%7C+Termux+Ready+%F0%9F%93%B1" alt="Typing SVG" />

<br><br>

![Python](https://img.shields.io/badge/Python-3.x-ff512f?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![AsyncIO](https://img.shields.io/badge/AsyncIO-Ultra_Fast-7b2ff7?style=for-the-badge)
![AioHTTP](https://img.shields.io/badge/AioHTTP-Downloader-ff0000?style=for-the-badge)
![ZIP](https://img.shields.io/badge/ZIP-Generator-ff512f?style=for-the-badge)
![Vercel](https://img.shields.io/badge/Vercel-Ready-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-00ff99?style=for-the-badge)

<br>

> **🌐 Powerful FastAPI based Website Source Downloader that downloads HTML, CSS, JS, Images & Assets into a ZIP archive instantly.**

</div>

---

<div align="center">

# 🌟 About WEB-2-ZIP

</div>

**WEB-2-ZIP** is a high-performance website source downloader API built using **FastAPI**, **AioHTTP**, and **AsyncIO**.

It downloads website source code including:

- HTML
- CSS
- JavaScript
- Images
- Fonts
- Media Files
- JSON/XML Assets

and automatically compresses everything into a downloadable ZIP archive.

Perfect for:

- 🌐 Website Backups
- 📦 Source Code Archiving
- 📚 Learning Frontend Structure
- 🧪 Testing Websites Offline
- ⚡ Fast Website Cloning

---

<div align="center">

# ✨ Features

</div>

```diff
+ 🚀 Ultra Fast Async Downloads
+ 📦 Automatic ZIP Creation
+ 🌐 Downloads HTML/CSS/JS/Images
+ 🔥 FastAPI Backend
+ ⚡ AsyncIO + AioHTTP Powered
+ ☁️ Vercel Compatible
+ 📱 Termux Compatible
+ 🔗 tmpfiles.org Upload Support
+ 🧹 Auto Cleanup System
+ 💻 Beginner Friendly API
```

---

<div align="center">

# 📂 Project Structure

</div>

```bash
WEB-2-ZIP/
│
├── api.py
├── requirements.txt
├── vercel.json
└── README.md
```

---

<div align="center">

# ⚙️ Installation

</div>

## Clone Repository

```bash
git clone https://github.com/abbasofficaldevs/WEB-2-ZIP.git

cd WEB-2-ZIP
```

---

## Install Requirements

```bash
pip install -r requirements.txt
```

---

## requirements.txt

```txt
fastapi
uvicorn
aiohttp
aiofiles
beautifulsoup4
lxml
uvloop
```

---

<div align="center">

# 🚀 Run API

</div>

```bash
python api.py
```

Server Starts On:

```bash
http://127.0.0.1:3648
```

---

<div align="center">

# 📡 API Usage

</div>

## Download Website Source

```http
GET /zip?url=https://example.com
```

---

## Example Request

```bash
curl "http://127.0.0.1:3648/zip?url=https://example.com"
```

---

## Success Response

```json
{
  "success": true,
  "download_url": "https://tmpfiles.org/dl/xxxxx/site.zip",
  "domain": "example.com",
  "file_size_mb": 2.45,
  "file_count": 52,
  "time_taken_seconds": 4.82
}
```

---

## Error Response

```json
{
  "success": false,
  "error": "Invalid content type"
}
```

---

<div align="center">

# 📦 What Gets Downloaded?

</div>

```diff
+ HTML Files
+ CSS Files
+ JavaScript Files
+ Images
+ Fonts
+ JSON/XML Assets
+ Media Files
+ Favicons
+ Source Maps
```

---

<div align="center">

# ☁️ Deploy On Vercel

</div>

## vercel.json

```json
{
  "version": 2,
  "builds": [
    {
      "src": "api.py",
      "use": "@vercel/python"
    }
  ],
  "routes": [
    {
      "src": "/(.*)",
      "dest": "api.py"
    }
  ]
}
```

---

## Deploy Command

```bash
npm i -g vercel

vercel
```

---

<div align="center">

# 📱 Termux Installation

</div>

```bash
pkg update -y

pkg install python -y

pip install -r requirements.txt
```

---

<div align="center">

# 🔥 API Endpoints

</div>

| Endpoint | Method | Description |
|----------|---------|-------------|
| `/` | GET | API Information |
| `/zip` | GET | Download & ZIP Website |
| `/download/{id}` | GET | Download Generated ZIP |

---

<div align="center">

# ❤️ Developer

Made with FastAPI & AsyncIO

### 👨‍💻 API Dev: @ab_devs
### 📢 Updates: @abkidz

</div>
````1
