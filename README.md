🌐 Project Overview

This project is an Optical Character Recognition (OCR) system that extracts text from images and converts it into machine-readable text.

Users can upload images containing printed or handwritten text, and the application processes the image using AI-powered OCR to detect and display the extracted text.

The goal of this project is to demonstrate how image processing and AI-based text recognition technologies can automate data extraction from images, scanned documents, and photos.

The system also supports:

🌙 Dark Mode / Light Mode UI
🌏 English & Japanese language support

🖼️ Screenshots
Light Mode
<img width="900" alt="Light Mode UI" src="screenshots/light-mode.png">
Dark Mode
<img width="900" alt="Dark Mode UI" src="screenshots/dark-mode.png">
OCR Result
<img width="900" alt="OCR Result" src="screenshots/ocr-result.png">

(Add your screenshots inside a screenshots folder)

🇯🇵 日本語説明 (Japanese Description)

このプロジェクトは、画像からテキストを抽出するOCR（光学文字認識）システムです。

ユーザーはテキストを含む画像をアップロードすると、アプリケーションがAIを使用して画像を処理し、機械が読み取れるテキストデータに変換します。

このシステムは、画像処理技術とAIによる文字認識を活用して、スキャンされた文書や画像からのデータ抽出を自動化することを目的としています。

主な特徴：

ダークモード / ライトモード対応

英語 / 日本語の多言語対応

AIによる高精度OCR処理

シンプルで使いやすいインターフェース

--------------------------------------------------------------------------------------------------------------

✨ Features

✔ Upload images containing text
✔ AI-powered OCR text extraction
✔ Support for printed and handwritten text
✔ Canvas-based image editing using Fabric.js
✔ Dark Mode / Light Mode UI
✔ English / Japanese language switching
✔ Cloud storage for uploaded files
✔ Secure authentication with Supabase

--------------------------------------------------------------------------------------------------------------

🧠 Tech Stack
Frontend

React / Next.js – UI framework
Tailwind CSS – Styling
Fabric.js – Canvas editor

Backend

Next.js API Routes (or Node.js / Express)
Supabase
Database
Authentication
Storage

AI Processing
Gemini AI Flash 2.5 – OCR processing

Deployment

Vercel – Hosting
Supabase – Backend services

Localization
i18next – English / Japanese translation

--------------------------------------------------------------------------------------------------------------

⚙️ Installation
1️⃣ Clone the Repository
git clone https://github.com/yourusername/ocr-ai-project.git

cd ocr-ai-project
2️⃣ Install Dependencies
npm install

or

yarn install
3️⃣ Configure Environment Variables

Create a .env.local file.

NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_key
GEMINI_API_KEY=your_gemini_api_key
4️⃣ Run the Development Server
npm run dev

Open in browser:

http://localhost:3000
🚀 Deployment

The project is deployed using:

Vercel – Frontend hosting

Supabase – Backend services

Deploy with:

vercel deploy
🧪 Demo

Live Demo:
(https://ocrproject3.vercel.app/)

Example Workflow:

1️⃣ Upload image
2️⃣ Edit or crop using canvas editor
3️⃣ Click Extract Text
4️⃣ AI processes image using Gemini
5️⃣ OCR result appears instantly

--------------------------------------------------------------------------------------------------------------

📁 Project Structure
/ocr-project
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

--------------------------------------------------------------------------------------------------------------

🔮 Future Improvements

Multi-language OCR support

PDF document OCR

Handwriting accuracy improvements

Export results as PDF / TXT

Batch image processing
--------------------------------------------------------------------------------------------------------------
👩‍💻 Author

Nilakshi Fernando

Software Engineering Graduate
Passionate about AI, Web Development, and Automation
