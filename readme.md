# FitCore – AI-Powered Fitness App 🏋️🤖🥗

FitCore is a cross-platform AI-powered fitness app that helps users achieve their fitness goals through personalized workout videos and intelligent meal planning. It supports data integration from health tracking devices like Google Fit and Apple HealthKit.

## 🔗 Live Links

- **🌐 Live App:** [https://your-live-app-link.com](https://your-live-app-link.com)
- **🛠️ Admin Panel:** [https://your-admin-link.com](https://your-admin-link.com)
- **📘 API Documentation:** [https://your-api-docs-link.com](https://your-api-docs-link.com)

---

## 🧠 Core Features

- AI-generated **personalized meal plans** using health data
- Stream/download **goal-based workout videos**
- **Health sync** via Google Fit & Apple HealthKit
- **Manual input fallback** for health tracking
- **Subscriptions** and **one-time content purchases**
- **Notifications** for updates, progress, and new content

---

## 🗃️ Database Schema

This project uses **PostgreSQL** with the schema visualized below:

![Database ERD](./7e7ce494-9a2b-414c-bf4c-a2b006b70821.png)

📍 View the interactive DB diagram here:  
🔗 [https://dbdiagram.io/d/681376501ca52373f5198603](https://dbdiagram.io/d/681376501ca52373f5198603)

---

## ⚙️ Backend Stack

- **Framework:** Django + Django REST Framework
- **Database:** PostgreSQL
- **Authentication:** JWT & OAuth2
- **Media Storage:** AWS S3 / Cloudinary
- **AI Integration:** OpenAI GPT-based meal planning (or custom ML)

---

## 📦 Installation & Setup

```bash
# Clone the repo
git clone https://github.com/your-username/fitcore.git
cd fitcore

# Create virtual environment
python -m venv env
source env/bin/activate  # or env\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Run server
python manage.py runserver
