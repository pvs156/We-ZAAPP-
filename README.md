🚀 We Zaap

 

We Zaap is a game-changing AI-powered platform designed to empower students by revolutionizing interview preparation. Through real-time, immersive mock interviews, We Zaap harnesses cutting-edge AI to provide personalized practice sessions, detailed feedback, and actionable insights, ensuring users excel in real-world interview situations.


🌟 Features

🎯 Personalized Interviews: Customize your sessions by specifying job roles, difficulty levels, and durations.

📚 Dynamic Question Generation: Leverages Retrieval-Augmented Generation (RAG) to generate relevant, company-specific questions.

🎙️ Seamless Voice Interaction: Real-time speech transcription with OpenAI's Whisper API and natural-sounding audio prompts via gTTS.

📈 Comprehensive Feedback Dashboard: Immediate, detailed reports highlighting strengths and improvement areas in technical and soft skills.

🔒 Secure User Management: Robust authentication system powered by SQLAlchemy and Werkzeug.


🛠️ Tech Stack

Backend: Flask, Python

Database: SQLAlchemy (SQLite/PostgreSQL)

AI & ML:

Retrieval-Augmented Generation (RAG)

OpenAI Whisper API (Speech-to-text)

GPT-4 (Question generation & evaluation)

Fine-tuned evaluation model

Web Scraping: BeautifulSoup, Requests

Text-to-Speech: Google Text-to-Speech (gTTS)

Frontend: HTML, CSS, JavaScript

Environment Management: python-dotenv

Security: Werkzeug (Password hashing)


📦 Installation

Quickly set up We Zaap locally with these easy steps:

🔧 Prerequisites

Python 3.8+

pip (Python package manager)

Git

OpenAI API Key


🚀 Setup

Clone the Repository:

git clone https://github.com/your-username/we-zaap.git
cd we-zaap

Create a Virtual Environment:

python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

Install Dependencies:

pip install -r requirements.txt

Configure Environment Variables:

Create a .env file in the root directory and add:

OPENAI_API_KEY=your-api-key
DATABASE_URL=sqlite:///we_zaap.db

Run the Application:

Python App.py


🎨 Project Structure

![image](https://github.com/user-attachments/assets/b4e919fc-91a0-460a-b99d-d87b0c58bd48)


🤝 Contributing

Contributions are welcome! Feel free to submit a pull request or create an issue if you have suggestions or improvements.


📜 License

Distributed under the MIT License. See LICENSE for more information.


📬 Contact

Venkata Sai Prashanth: prashanthpvs862@gmail.com

🌟 Happy interviewing with We Zaap! 🌟

