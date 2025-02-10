# 🤖 Gemini Pro - ChatBot

A conversational AI chatbot powered by **Gemini Pro API**. This chatbot can engage in interactive conversations, answer queries, and assist users with real-time responses. Built using **Python** and **Streamlit** for seamless deployment.

---


## 📦 Features

- ✅ Real-time chatbot responses using Gemini Pro API  
- ✅ Sleek, user-friendly UI with Streamlit  
- ✅ Secure API key management  
- ✅ Lightweight and fast  

---

## ⚙️ Tech Stack

- **Frontend:** Streamlit  
- **Backend:** Python  
- **API:** Gemini Pro API  

---

## 🖥️ Installation Guide (For Local Setup)

### 1 Clone the Repository

```bash
git clone https://github.com/your-username/gemini-pro-chatbot.git
cd gemini-pro-chatbot
```

### 2 Install the Dependencies

```
pip install -r requirements.txt
```

## 🔐 API Key Configuration
### Method 1: Using .streamlit/secrets.toml (For Deployment on Streamlit Cloud)
  In your project folder, create a file:
```
.streamlit/secrets.toml
```
  Add your API key like this:
```
[api_keys]
GOOGLE_API_KEY = "YOUR_GOOGLE_API_KEY_HERE"
```
  Save the file.

### Method 2: Using .env (For Local Development)
Create a .env file in the project root folder.
Add the following line:
```
GOOGLE_API_KEY=YOUR_GOOGLE_API_KEY_HERE
```
Make sure you have python-dotenv installed (already in requirements.txt).

## 🚀 Run the App Locally
```
streamlit run main.py
```

## 📂 Project Structure
```
gemini-pro-chatbot/
├── app.py
├── requirements.txt
├── .streamlit/
│   └── secrets.toml
└── README.md
```


