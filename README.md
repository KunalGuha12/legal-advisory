# ⚖️ LegalHelp.ai — Your Friendly Legal Rights Assistant

LegalHelp.ai is an AI-powered legal advisory chatbot built using Flask and Google Gemini 1.5 Flash, designed to help users understand their legal rights with clear, personalized, and friendly advice.
Whether it’s a wage issue, rental dispute, or harassment complaint, LegalHelp.ai simplifies the complex world of law using conversational AI.

---

# 🎬 Demo Video

🎥 [Watch the demo](https://drive.google.com/drive/folders/1YVnXJrwtw46YPxqCylbpSKEEelACHyzC?usp=drive_link) — Experience the bot in action!

---


# 🖼️ Bot Interface Preview
<img width="1920" height="868" alt="Screenshot 2025-08-07 165518" src="https://github.com/user-attachments/assets/e5d71de1-87b9-4cd4-8ed8-871b70086586" />



---

# ✨ Key Features

🧾 Collects user name, age, and gender for personalized answers

💬 Chatbox with real-time AI legal advisor

📚 Predefined legal issue suggestions (e.g. Labor Law, Harassment)

🧠 Session memory using cookies — remembers your context

✨ AI response formatting — supports bold, paragraphs, and ordered steps

🎨 Professional legal-themed UI (desktop-first)

---



# 🛠️ Tech Stack
| Layer         | Tools & Frameworks             |
| ------------- | ------------------------------ |
| 🎨 Frontend   | HTML5, CSS3, JavaScript        |
| 🔧 Backend    | Python, Flask                  |
| 🧠 AI API     | Gemini 1.5 Flash (Google AI)   |
| 📦 Deployment | GitHub Pages / Render / Heroku |

---




# 📁 Project Structure

     legalhelp-ai/
     │
     ├── static/
     │   ├── index.static.js        → Frontend JS logic
     │   ├── style.css              → UI styling
     │   └── screenshots/           → UI screenshots
     │
     ├── templates/
     │   └── index.html             → Main chat interface
     │
     ├── .env.sample                → Environment variable template
     ├── app.py                     → Flask backend with session handling
     ├── requirements.txt           → Python dependencies
     ├── README.md                  → This file
     └── .gitignore                 → Ignores .env, __pycache__, etc.

---
# 🧠 Powered By
-> Gemini 1.5 Flash -> Flask -> Google Generative AI SDK

---



# ⚙️ Getting Started
```bash
# Step 1: Install Python dependencies
pip install flask python-dotenv

# Step 2: Set your Gemini API key
### In a file named .env:
GEMINI_API_KEY=your_actual_key_here

### Step 3: Start the Flask server
python app.py
```

---



# 🌐 Frontend Usage

1.Open your browser at http://localhost:5000

2.Enter your Name, Age, and Preferred Language

3.Ask your legal query in simple words

4.Get answers with:
    
                   a. Text response

   
                    b. Audio playback

  
                    c. Language of your choice


---

# 🌍 Supported Languages

1.🏳️Hindi

2.🏴 Bengali

3.🏳 English

...more coming soon!


---


# 📡 API Details
| Endpoint | Method | Description                                |
| -------- | ------ | ------------------------------------------ |
| `/ask`   | POST   | Sends query to Gemini, returns AI response |

---

# 🧾 Sample Request:

{
  "query": "Can police arrest me without a warrant?",
  "language": "Hindi"
}

# 🧾 Sample Response:

{
  "answer": "पुलिस कुछ मामलों में बिना वारंट के गिरफ्तारी कर सकती है।",
}

---

# 👨‍💻 Contributors

Kunal Guha
📫 [kunalguh2003@gmail.com]

Subhadip Bag
📫 [subhadipbag906@gmail.com]

Souvik Halder
📫 [hsouvik605@gmail.com]

---


# 📝 License
Licensed under the MIT License — free to use, improve, and share.



⭐ Star, Fork, & Contribute
If this project helped spread awareness or simplified complex information:



⭐ Star the repo to show support

🍴 Fork it to improve or localize it

🐛 Submit issues or suggestions

"When rights are explained in your own language, justice becomes real." 🧑‍⚖️

