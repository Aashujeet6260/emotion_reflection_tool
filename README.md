# 💬 Emotion Reflection Tool

# As the File size of the Project Was more Then 100MB and Github was accept the repository of this so i have upload the file with Demo file on the drive link for this project -  

A simple web app where users can type in a short reflection (like “I feel nervous about my first job interview”), and the app returns a **fake emotion analysis** using a Python backend API.

---

## 📸 Preview

![Demo](https://your-image-or-gif-link-here.com) <!-- Optional GIF or Screenshot -->

---

## 🚀 Features

- 📝 Clean UI with reflection input
- 🔄 Loading state while waiting for results
- 🎭 Mock emotion + confidence output from API
- ⚡ FastAPI backend + Next.js frontend
- 📱 Mobile-first responsive design

---

## 📁 Project Structure

```
emotion-reflection-tool/
├── emotion-backend/     # Python FastAPI backend
└── emotion-frontend/    # Next.js + TypeScript frontend
```

---

## 🧰 Tech Stack

| Frontend | Backend  |
|----------|----------|
| Next.js  | FastAPI  |
| TypeScript | Python |
| React    | Uvicorn |
| Tailwind CSS (optional) | CORS Middleware |

---

## 🛠️ Installation & Setup

### ✅ Prerequisites

- [Node.js v18+](https://nodejs.org/en/download)
- [Python 3.8+](https://www.python.org/downloads)

---

### 🔧 Backend Setup (FastAPI)

1. Open terminal and navigate to backend:

```bash
cd emotion-backend
```

2. Create virtual environment and activate:

```bash
python -m venv venv
venv\Scripts\activate      # Windows
# OR
source venv/bin/activate   # macOS/Linux
```

3. Install required packages:

```bash
pip install -r requirements.txt
```

4. Start the FastAPI server:

```bash
uvicorn main:app --reload --port 8000
```

✅ API is now running at: [http://localhost:8000/analyze](http://localhost:8000/analyze)

---

### 🌐 Frontend Setup (Next.js)

1. Open a **new terminal** and navigate to frontend:

```bash
cd emotion-frontend
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

✅ App is now running at: [http://localhost:3000](http://localhost:3000)

---

## ✨ Usage

1. Go to [http://localhost:3000](http://localhost:3000)
2. Type a short reflection (e.g. _"I’m worried about my exam"_)
3. Click **Submit**
4. See a fake emotion and confidence level

---

## 📦 API Format

### Request

`POST /analyze`

```json
{
  "text": "I feel happy today"
}
```

### Response

```json
{
  "emotion": "Happy",
  "confidence": 0.87
}
```

---

## 📌 Notes

- This project uses **mock emotion analysis** (randomized).
- CORS is enabled on the backend for development only.

---

## 🧪 Future Enhancements (Optional Ideas)

- Add real NLP-based emotion detection using Hugging Face or NLTK
- Store user reflections in a database (e.g., MongoDB, SQLite)
- Add animations or charts for emotion trends

---

## 📄 License

MIT License – free to use and modify.

---

## 💡 Author

**Aashujeet Rai**  
Built for demo/learning purposes.
