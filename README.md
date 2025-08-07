🧠 Legal Adivisory Bot
Empowering migrants, daily wage workers & minorities by explaining their rights in a language they understand — via AI.

The Multilingual Legal Rights Explainer Bot is a powerful, AI-driven web assistant that simplifies complex legal language into clear, understandable explanations tailored for underrepresented communities. Built with advanced LLM technology (Gemini 1.5 Flash), this tool delivers rights-based information in multiple Indian languages through text, audio, and visuals — ensuring accessibility for all.

Whether you are a migrant worker, a social worker, or someone advocating for digital legal empowerment, this bot can be your first step to accessible justice.


🎬 Demo Video

🎥 Watch the demo — Experience the bot in action!



🖼️ Bot Interface Preview
<img width="1920" height="877" alt="Screenshot 2025-08-07 114418" src="https://github.com/user-attachments/assets/103e9800-90b1-4776-8234-2a1f71babec4" />


✨ Key Features
🧠 AI-Powered Responses: Uses Gemini 1.5 Flash to understand and explain user queries
🌐 Multilingual Support: Responds in Bengali, Hindi, English, and more
🔊 Voice Output: Text-to-speech for users with limited literacy.

🎨 Modern UI: Clean, dashboard-style interface with responsive design
📊 Query Logging: All conversations saved for feedback & improvement
📥 Lightweight Frontend: Optimized for both desktop & mobile

🛠️ Tech Stack
| Layer         | Tools & Frameworks             |
| ------------- | ------------------------------ |
| 🎨 Frontend   | HTML5, CSS3, JavaScript        |
| 🔧 Backend    | Python, Flask                  |
| 🧠 AI API     | Gemini 1.5 Flash (Google AI)   |
| 📦 Deployment | GitHub Pages / Render / Heroku |


📁 Project Structure

| File/Folder            | Description                            |
| ---------------------- | -------------------------------------- |
| `app.py`               | Flask backend & Gemini API handler     |
| `templates/index.html` | Frontend HTML layout                   |
| `static/style.css`     | Custom CSS with transitions & styling  |
| `static/script.js`     | Handles Gemini API fetch & response UI |
| `.env`                 | Stores Gemini API Key securely         |
| `README.md`            | Project documentation (this file)      |

⚙️ Getting Started
# Step 1: Install Python dependencies
pip install flask python-dotenv

# Step 2: Set your Gemini API key
# In a file named .env:
GEMINI_API_KEY=your_actual_key_here

# Step 3: Start the Flask server
python app.py

🌐 Frontend Usage
1.Open your browser at http://localhost:5000
2.Enter your Name, Age, and Preferred Language
3.Ask your legal query in simple words
4.Get answers with:
5.Text response
6.Audio playback
7.Language of your choice

🌍 Supported Languages
1.🏳️Hindi
2.🏴 Bengali
3.🏳 English
...more coming soon!

📡 API Details
| Endpoint | Method | Description                                |
| -------- | ------ | ------------------------------------------ |
| `/ask`   | POST   | Sends query to Gemini, returns AI response |

🧾 Sample Request:

{
  "query": "Can police arrest me without a warrant?",
  "language": "Hindi"
}

🧾 Sample Response:

{
  "answer": "पुलिस कुछ मामलों में बिना वारंट के गिरफ्तारी कर सकती है।",
  "audio_url": "/static/audio/output.mp3"
}

👨‍💻 Contributors
Kunal Guha
📫 [kunalguh2003@gmail.com]

Subhadip Bag
📫 [subhadipbag906@gmail.com]

Souvik Halder
📫 [hsouvik605@gmail.com]




📝 License
Licensed under the MIT License — free to use, improve, and share.

⭐ Star, Fork, & Contribute
If this project helped spread awareness or simplified complex information:

⭐ Star the repo to show support

🍴 Fork it to improve or localize it

🐛 Submit issues or suggestions

"When rights are explained in your own language, justice becomes real." 🧑‍⚖️

