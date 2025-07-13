# 🏋️ Fitness Tracker App

**Fitness Tracker** is a simple web application built with Flask (backend) and JavaScript/HTML/CSS (frontend) that helps users manage their fitness routine and track health data.

---

## 🚀 Features

- **User Authentication** (signup/login/logout)
- **Add/Edit/Delete Workout Plans** (CRUD operations)
- **Search & Filter** workouts by type, duration, etc.
- **Import/Export CSV** of workouts and contacts
- **Favorites & Labels** to manage workouts
- **Birthday reminders** for contacts
- Efficient lookup with **Trie and hash maps**
- **Responsive UI** built with HTML, CSS, JS

---

## 📁 Repository Structure

fitness/
├── backend/
│ ├── app.py # Flask server
│ ├── templates/ # HTML templates
│ └── static/ # JS, CSS, images
└── data/
└── contacts.txt # Filled with sample data


---

## 💾 Installation & Setup

1. Clone the repo:  
   ```bash
   git clone https://github.com/your-username/fitness
   cd fitness/backend

---
pip install flask flask-cors

python app.py

cd ../
python -m http.server 8000

---

 Usage

    Add a Workout Plan: Fill the form and press Add.

    Search: Type keywords (name, category, notes) and click Search.

    Edit/Delete: Use row buttons in the workout table.

    Favorites: Toggle via star icons.

    Import/Export CSV: Use the toolbar buttons.

    Recent Plans: Show the latest 5 entries.

    Filters: Use filter buttons for country, category.

    Birthday Reminder: Alerts for today's birthdays.


---



