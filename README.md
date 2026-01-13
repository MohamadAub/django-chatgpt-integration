# 🤖 Django ChatGPT Integration

**Django ChatGPT Integration** is a modern web application that combines the power of **Django**, a high-level Python web framework, with **OpenAI’s ChatGPT**, a state-of-the-art AI language model.  
This project enables users to interact with an AI-powered chatbot through a clean and responsive chat interface.

---


![alt text](<Django chatgpt-1.png>)


---

## 🚀 Features

- 💬 **Interactive Chat Interface** — Real-time communication with ChatGPT.
- 🔗 **Seamless API Integration** — Direct integration with OpenAI’s API.
- 👤 **User Authentication** — Register and log in for personalized sessions.
- 🧠 **Conversation History** — Save and display past interactions.
- ⚡ **AJAX-Powered Responses** — Real-time message updates without page reloads.
- 🧰 **Error Handling** — Graceful management of API and connection errors.

---

## 🛠️ Installation

Follow the steps below to set up the project on your local machine.

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/MohamadAub/django-chatgpt-integration.git
cd django-chatgpt-integration
```

### 2️⃣ Create & Activate a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate   # For Windows
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Add Your OpenAI API Key
In your project’s `.env` file, add the following line:
```
OPENAI_API_KEY=your-api-key
```

### 5️⃣ Apply Migrations
```bash
python manage.py migrate
```

### 6️⃣ Run the Development Server
```bash
python manage.py runserver
```

Then open your browser and go to **http://127.0.0.1:8000**.

---

## 💡 Usage

1. Register or log in to your account.  
2. Start chatting with ChatGPT via the web interface.  
3. View your chat history and previous conversations.  
4. Enjoy AI-powered intelligent responses in real-time!

---

## 🧩 Tech Stack

- **Backend:** Django (Python)  
- **Frontend:** HTML, CSS, JavaScript, AJAX  
- **AI Model:** OpenAI ChatGPT API  
- **Database:** SQLite (default) / PostgreSQL (optional)  
- **Environment Management:** Python-dotenv  

---

## 🤝 Contributing

Contributions are welcome!  
If you’d like to improve this project, please fork the repo and submit a pull request.  
Found a bug? Open an issue describing it.

---

## 🧾 License

This project is licensed under the **MIT License** — feel free to use and modify it.

---

## 🙌 Acknowledgements

- [Django](https://www.djangoproject.com/) — The web framework used.  
- [ChatGPT](https://openai.com/) — AI model for generating chatbot responses.  
- [OpenAI API](https://platform.openai.com/docs/api-reference) — For seamless integration.

---

### 🌟 Author
**Mohamad EL-AYOUBI**  
Software & Cloud Engineer | DevOps | AI Integration Specialist  
🔗 [GitHub Profile](https://github.com/MohamadAub)
