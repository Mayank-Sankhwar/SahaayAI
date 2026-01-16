# SahaayAI
Helping people in places with low internet connectivity in getting answers to their queries through 24/7 AI call .

🎙️ SahaayAI: Multilingual Voice-to-Call Assistant

SahaayAI is an intelligent bridge between digital information and accessibility. It allows users to speak queries in their native language via a web interface and receive answers through a direct phone call and SMS, powered by real-time web scraping and machine learning.

🚀 Features

🎤 Multilingual Voice Input
A simple mic-enabled web interface that captures queries in various native languages.

🌐 Web-Scraping Intelligence
Automatically scrapes the web for real-time information, focused on Government Schemes and general user interests.

🧠 AI Voice Synthesis
Processes extracted data through an ML model to generate natural-sounding responses.

📞 Automated Call-Back
Triggers an AI bot to call the user's registered mobile number and deliver the response verbally.

📩 SMS Integration
Sends a text summary of the answer to the user for future reference.

🛠️ Tech Stack
Component	Technology
Frontend	React.js / HTML5 / Tailwind CSS
Backend	Node.js
Language Detection	Efficient Language Detector (ELD)
ML / Web Scraping	Tavily
Telephony	Twilio API (Voice & SMS)
LLM	Gemini (Query Processing)
⚙️ How It Works

Capture
User clicks the mic button on the Web UI and asks a question
Example: “What are the benefits of the PM-Kisan scheme?”

Translate & Process
The ML pipeline converts speech to text, detects the language, and extracts intent.

Search
The system performs a targeted web scrape to fetch accurate and up-to-date information.

Execute Call
The backend triggers a VoIP service to call the user's registered mobile number.

Voice & Text Delivery

The user hears the response in their native language over the phone

An SMS with written details is sent at the end of the call

📋 Prerequisites

Before running this project, ensure you have:

Node.js (Frontend & Backend)

API Keys for:

Twilio (Voice & SMS)

Gemini (LLM)

Tavily (Web Search)

🛠️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/yourusername/voicequery-ai.git
cd voicequery-ai

2️⃣ Install Backend Dependencies
npm install

3️⃣ Install Frontend Dependencies
cd client
npm install

4️⃣ Environment Variables

Create a .env file in the root directory:

TWILIO_ACCOUNT_SID=your_sid
TWILIO_AUTH_TOKEN=your_token
GEMINI_API_KEY=your_key
TAVILY_API_KEY=your_key

5️⃣ Run the Application

Start Backend

npm start


Start Frontend

cd client
npm start

🛡️ Use Cases

Digital Inclusion
Helping elderly or non-tech-savvy users access government information without typing.

Agriculture
Farmers querying crop insurance or weather-related schemes in regional languages.

Education
Students asking general knowledge questions on the go.

📌 Future Enhancements

Call recording & transcripts

Offline SMS fallback

Regional dialect tuning

Android & IVR support

🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first.

📄 License

This project is licensed under the MIT License.

❓ Need More?
