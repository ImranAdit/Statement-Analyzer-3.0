# 📊 Statement Analyzer Tool

A web-based tool to analyze payment processing statements and compare current processing costs with Adit Pay pricing.

---

## 🚀 Features

* 📂 Upload bank / merchant statements (PDF)
* 🤖 AI-powered data extraction (planned)
* 📊 Transaction-level cost breakdown
* 💰 Current vs Adit Pay cost comparison
* 📈 Savings & recommendation engine
* ✏️ Editable inputs for accuracy

---

## 🧠 How It Works

1. Upload a statement or enter data manually
2. System extracts key values:

   * Monthly volume
   * Processing fees
   * Transaction mix
3. Applies pricing logic
4. Displays:

   * Current cost
   * Adit Pay cost
   * Savings

---

## 🏗️ Tech Stack

* **Frontend:** HTML, JavaScript (React-ready)
* **Backend:** Node.js (Express)
* **Parsing:** PDF processing
* **Deployment:** Docker
* **Hosting:** Render / Railway

---

## 📂 Project Structure

```
statement-analyzer/
│
├── backend/        # API + calculation engine
├── frontend/       # UI
├── Dockerfile      # Deployment config
└── README.md
```

---

## ⚙️ Setup (Local)

### 1. Clone Repo

```
git clone https://github.com/your-username/statement-analyzer.git
cd statement-analyzer
```

### 2. Install Backend

```
cd backend
npm install
node server.js
```

### 3. Open Frontend

Open `frontend/index.html` in browser

---

## 🚀 Deployment

This project is Dockerized and can be deployed on:

* Render
* Railway

---

## 📌 Future Improvements

* 🤖 AI-based statement parsing using OpenAI
* 📄 PDF report generation
* 📊 Dashboard UI
* 🔐 User authentication
* 🗄️ Database integration

---

## 💡 Use Case

Built for sales teams to quickly analyze merchant statements and demonstrate potential savings with Adit Pay.

---

## 👤 Author

Built by Adit Pay Team
