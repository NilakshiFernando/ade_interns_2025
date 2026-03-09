# 📄 AI OCR Text Recognition System

![Next.js](https://img.shields.io/badge/Next.js-000?logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?logo=tailwind-css&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white)
![Gemini AI](https://img.shields.io/badge/Gemini-AI-blue)
![Vercel](https://img.shields.io/badge/Vercel-000?logo=vercel)

AI-powered **Optical Character Recognition (OCR)** web application that extracts text from images using **Gemini AI**, built with **Next.js, Supabase, and Tailwind CSS**.

---

# 🌐 Project Overview

This project is an **Optical Character Recognition (OCR) system** that extracts text from images and converts it into **machine-readable text**.

Users can upload images containing **printed or handwritten text**, and the system processes the image using **AI-powered OCR** to detect and display the extracted text.

The system demonstrates how **AI + Image Processing** can automate **data extraction from images, scanned documents, and photos**.

### 🌟 Key Highlights

- 🌙 Dark Mode / Light Mode UI
- 🌏 English & Japanese language support
- 🧠 AI-powered OCR with Gemini Flash 2.5
- ☁ Cloud storage with Supabase
- 🎨 Canvas editor for image editing

---

# 🎥 Demo

### OCR Processing Demo

![Demo GIF](screenshots/demo.gif)

*(Add a screen recording GIF of your project here)*

---

# 🖼️ Screenshots

## ☀ Light Mode

<img width="900" src="screenshots/light-mode.png">

## 🌙 Dark Mode

<img width="900" src="screenshots/dark-mode.png">

## 🔍 OCR Result

<img width="900" src="screenshots/ocr-result.png">

---

# 🧠 System Architecture

```
User Upload Image
        │
        ▼
Next.js Frontend (React UI)
        │
        ▼
Canvas Editing (Fabric.js)
        │
        ▼
Next.js API Route
        │
        ▼
Gemini AI Flash 2.5
        │
        ▼
Extracted Text Response
        │
        ▼
Display Result in UI
```

---

# 🇯🇵 日本語説明 (Japanese Description)

このプロジェクトは、**画像からテキストを抽出するOCR（光学文字認識）システム**です。

ユーザーがテキストを含む画像をアップロードすると、AIを使用して画像を処理し、**機械が読み取れるテキストデータ**に変換します。

このシステムは、**画像処理技術とAIによる文字認識**を活用して、スキャンされた文書や写真からのデータ抽出を自動化することを目的としています。

### 主な機能

- ダークモード / ライトモード対応  
- 英語 / 日本語の多言語対応  
- AIによるOCR処理  
- シンプルで使いやすいUI  

---

# ✨ Features

- Upload images containing text
- AI-powered OCR text extraction
- Support for printed and handwritten text
- Canvas-based editing with Fabric.js
- Dark / Light theme
- English / Japanese translation
- Secure authentication
- Cloud storage

---

# 🧰 Tech Stack

## Frontend

- **React / Next.js**
- **Tailwind CSS**
- **Fabric.js**

## Backend

- **Next.js API Routes**
- **Supabase**
  - Database
  - Authentication
  - Storage

## AI Processing

- **Gemini AI Flash 2.5**

## Localization

- **i18next** (English / Japanese)

## Deployment

- **Vercel**
- **Supabase**

---

# ⚙️ Installation

## 1 Clone Repository

```bash
git clone https://github.com/yourusername/ocr-ai-project.git
cd ocr-ai-project
```

---

## 2 Install Dependencies

```bash
npm install
```

or

```bash
yarn install
```

---

## 3 Setup Environment Variables

Create `.env.local`

```
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_key
GEMINI_API_KEY=your_gemini_api_key
```

---

## 4 Run Development Server

```bash
npm run dev
```

Open:

```
http://localhost:3000
```

---

# 🚀 Deployment

The application is deployed using:

- **Vercel** – frontend hosting
- **Supabase** – backend services

Deploy using:

```bash
vercel deploy
```

---

# 📁 Project Structure

```
ocr-project
│
├── components
├── pages
├── api
├── public
├── screenshots
├── styles
├── utils
│
├── i18n
├── supabase
│
└── README.md
```

---

# 🔮 Future Improvements

- Multi-language OCR
- PDF document scanning
- Better handwriting recognition
- Export as PDF / TXT
- Batch image processing

---

# 👩‍💻 Author

**Nilakshi Fernando**

Software Engineering Graduate  
Interested in **AI, Web Development, and Automation**

---

# ⭐ Support

If you like this project:

⭐ Star the repository  
🍴 Fork the project  
🚀 Share with others
