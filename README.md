
# 🧠 Medical Chat Bot Using RAG

A powerful AI-driven medical chatbot built with **Retrieval-Augmented Generation (RAG)**, featuring a responsive dashboard, secure login/registration system, PostgreSQL database integration, and an advanced image analyzer.

---

## 🚀 Features

### 💬 Chatbot (RAG-Based)
- Answers medical questions using a Retrieval-Augmented LLM.
- Context-aware conversations with intelligent follow-up handling.

### 📊 Dashboard
- Intuitive user interface with:
  - Query history
  - Analysis results
  - Admin statistics

### 🔐 Authentication
- Secure login and registration pages.
- Passwords encrypted using industry standards.

### 🗃️ PostgreSQL Database
- Stores user data, chat logs, and analysis results.
- Efficient, scalable schema.

### 🖼️ Image Analyzer
- Accepts medical image uploads (X-ray, MRI, etc.).
- Provides AI-powered feedback and analysis reports.

---

## 🧰 Tech Stack

| Area            | Technology                          |
|-----------------|--------------------------------------|
| Backend         | Python, Flask / FastAPI             |
| Frontend        | HTML, CSS, JavaScript               |
| AI/NLP          | OpenAI API / Transformers           |
| Database        | PostgreSQL                          |
| Auth            | bcrypt / Flask-Login                |
| Image Analysis  | TensorFlow / PyTorch                |
| Deployment      | Streamlit / Docker / Render / Heroku|

---

## 📁 Project Structure

```
Medical-Chat-Bot-Using-RAG/
├── app.py                  # Main server script
├── chatbot/                # RAG-based chatbot logic
├── dashboard/              # User interface & dashboards
├── auth/                   # Login and registration modules
├── db/                     # PostgreSQL DB connection and schema
├── analyzer/               # Image processing modules
├── static/                 # Static files (CSS, JS)
├── templates/              # HTML templates
├── requirements.txt
└── README.md
```

---

## 🛠️ Getting Started

```bash
# Clone the repository
git clone https://github.com/Pawan1724/Medical-Chat-Bot-Using-RAG.git
cd Medical-Chat-Bot-Using-RAG

# (Optional) Create and activate virtual environment
python -m venv venv
venv\Scripts\activate  # On Windows

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py
```

---

## 🗃️ PostgreSQL Configuration

1. Install PostgreSQL.
2. Create a database `MedicalBotDB`.
3. Update the connection in `db/config.py`:

```python
DATABASE_URL = "postgresql://<username>:<password>@localhost:5432/MedicalBotDB"
```

---

## 📸 Screenshots (Optional)

_Add screenshots of your chatbot, dashboard, and image analyzer interfaces._

---

## 🤝 Contributing

Feel free to fork the repository, submit pull requests, or suggest improvements!

---

## 👨‍💻 Author

**Pawan Kumar Salikanti**  
_AI & ML Enthusiast_  
[GitHub](https://github.com/Pawan1724)

---

## 📄 License

Licensed under the [MIT License](LICENSE).
