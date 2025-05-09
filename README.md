📞 AI-Powered Voice Call System (**AI CallMate**)
Revolutionizing Traditional Call Centers with AI-Driven Conversations

An intelligent, automated voice-calling platform built with Node.js, integrated with Twilio for programmable voice calls, and enhanced with AI for real-time, human-like conversations. This system allows you to initiate calls by inputting prompts and phone numbers. It then handles the entire conversation autonomously, records responses, and generates structured reports.

🚀 Key Features

✅ Automated Outbound Voice Calls – Make voice calls to any mobile number.

🤖 AI-Driven Voice Interaction – Human-like, context-aware conversations.

🧠 Natural Language Flow – The AI maintains a smooth dialogue from greeting to farewell.

🗣️ Text-to-Speech (TTS) & Speech-to-Text (STT) – Converts text input to speech and transcribes responses.

📊 Data Storage & Reporting – Responses saved to MongoDB; generates structured Q&A reports.

🌐 User-Friendly Frontend – React-based interface for inputting prompts and numbers.

🔐 TRAI & DND Compliance – Fully adheres to Indian telecom laws and user data protection.

🧱 Tech Stack

Backend: Node.js + Express

Database: MongoDB

Voice: Twilio

AI: Third-Party APIs

Frontend: HTML + CSS + JS

⚙️ Backend Setup
Create a .env file in /backend

env
TWILIO_SID=YOUR_SID_KEY TWILIO_AUTH=YOUR_AUTH_KEY TWILIO_PHONE=YOUR_PHONE_NUMBER MONGO_URI=YOUR_MONGODB_URL GEMINI_API_KEY=YOUR_GEMINI_API_KEY BASE_URL=YOUR_BASE_URL GROQ_API_KEY=YOUR_GROQ_API_KEY

Install dependencies:
cd backend npm install

Start server:
node index.js or nodemon index.js

📞 How It Works

Admin inputs a phone number and a question/prompt via the frontend.

The backend triggers a voice call using Twilio.

The system uses AI to engage in real-time conversation.

Speech is converted to text, interpreted, and responded to via TTS.

The full call transcript is stored and organized in MongoDB.

A detailed report is generated with question-answer pairs.

📊 Reporting Capabilities

Automatic transcript storage

Structured Q&A generation

(Upcoming) Export reports as PDF/Excel

(Upcoming) Real-time analytics and dashboard

⚖️ Legal & Compliance

TRAI and DND list integration to ensure compliance with Indian telecom norms.

Secure user consent management.

End-to-end encryption for sensitive data.

🧠 Future Roadmap

📄 Exportable PDF & Excel call summaries

📅 Call scheduling and history tracking

🌐 Multi-language voice support

📈 Real-time dashboard with metrics and analytics

🤝 Contributions
We welcome pull requests! For major changes, please open an issue to discuss what you'd like to improve or add.

📧 Contact
Developer: Vaibhav
📩 Email: sahuvaibhav064@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/vaibhav-chaudhary-615712272/

📜 License
MIT License © 2025 Vaibhav
