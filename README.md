# 🧳 AI Trip Planner (TravelBuddy)

An **AI-powered travel planning system** built using **Django**, **Google Gemini API**, and **Bootstrap**, designed to help users create **personalized itineraries** based on their **destination, duration, mood, and travel group type**.

---

## 🚀 Project Overview

**AI Trip Planner (TravelBuddy)** uses the power of **Google Gemini API** to deliver smart, data-driven travel recommendations.  
Whether you're planning a solo adventure, a romantic getaway, or a family vacation — this system builds a tailor-made itinerary that fits your preferences perfectly.

---

## 🧠 Features

- 🤖 **AI-powered trip planning** using Google Gemini API  
- 📍 Custom itineraries based on location and duration  
- 🎭 Personalized recommendations based on **mood** and **group type**  
- 🗓️ Dynamic itinerary creation and visualization  
- 💾 SQLite database to store trip history and preferences  
- 🔐 User authentication for personalized experiences  
- 💻 Responsive UI built with **Bootstrap** and **jQuery**  
- 🌐 Fast backend powered by **Django**

---

## 🧩 Tech Stack

| Layer | Technology Used |
|-------|-----------------|
| **Frontend** | HTML, CSS, JavaScript, jQuery, Bootstrap |
| **Backend** | Python, Django |
| **Database** | SQLite |
| **API Integration** | Google Gemini API |

---

## ⚙️ How It Works

1. 🧭 The user enters **destination**, **duration**, and **mood**.  
2. 🤖 The backend uses **Google Gemini API** to generate AI-based suggestions for activities, attractions, and itineraries.  
3. 🗺️ The system creates a dynamic itinerary tailored to the user’s preferences.  
4. ✏️ The user can modify, save, or download their final trip plan.

---

## 🧑‍💻 Installation & Setup

Follow these steps to run the project locally:

### 1️⃣ Clone the repository
```bash
git clone https://github.com/PiyushCodess/TravelBuddy.git
cd TravelBuddy
2️⃣ Create and activate a virtual environment
python -m venv venv
venv\Scripts\activate  # For Windows
# source venv/bin/activate  # For Linux/Mac
3️⃣ Install dependencies
pip install -r requirements.txt
4️⃣ Create a .env file in the root directory
GROQ_API_KEY=your_groq_or_gemini_api_key_here
5️⃣ Run database migrations
python manage.py migrate
6️⃣ Run the Django development server
python manage.py runserver
Then open: 👉 http://127.0.0.1:8000/

☁️ Deployment (Render)
To deploy on Render:

Push your project to GitHub (make sure .env is added to .gitignore)

Create a new Web Service on Render.com

Set Environment Variables:

GROQ_API_KEY=your_actual_key
Add build & start commands:

Build Command: ./build.sh

Start Command: gunicorn AITripPlanner.wsgi:application


💡 Applications
Automated travel planning for individuals, couples, and families

Personalized trip suggestions based on preferences and moods

AI-assisted itinerary creation and time-efficient trip management

Dynamic recommendations for destinations and activities

🛠️ Future Enhancements
✈️ Flight & hotel booking integration

🗺️ Map visualization for routes

💬 Chat-based trip planning assistant

📱 Mobile app version with offline access

👨‍💻 Author
Piyush Patrikar
🎓 BTech CSE @ Indore Institute of Science and Technology
💼 Aspiring Django & AI Developer
🔗 LinkedIn | GitHub
