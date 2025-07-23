# 🏨 Continental Hospitality Management Suite

A **full-stack hospitality management system** supporting hotel room bookings, event scheduling, restaurant reservations, employee management, and maintenance tracking.

Built with a modular **Flask backend**, a **Flutter mobile app**, and a **React + Tailwind CSS web frontend** for modern, responsive experiences.

---

## 📁 Project Structure

```plaintext
.
👉 backend/                                # Flask backend
📌   └── app.py
👉 App/paris/                              # Flutter mobile app
📌   └── lib/
📌       └── main.dart
👉 Frontend/Hospitality-management-system/ # React frontend
📌   ├── src/
📌   │   ├── App.jsx
📌   │   └── main.jsx
📌   └── ...
📌 README.md
```

---

## 🚀 Features

* 🏯 Hotel room booking system
* 📅 Event scheduler
* 🍽️ Restaurant reservation & order system
* 🧹 Maintenance issue tracking
* 👨‍💼 Staff/employee directory
* 📧 Email confirmations (via Flask-Mail)
* 📱 Flutter-based mobile interface
* 🖥️ React + Tailwind CSS web interface
* 💡 Modular Flask backend with MySQL support

---

## 🧐 Tech Stack

| Layer        | Technology                                  |
| ------------ | ------------------------------------------- |
| **Backend**  | Python (Flask), MySQL, Flask-Mail, REST API |
| **Mobile**   | Flutter (Dart)                              |
| **Frontend** | React, Vite, Tailwind CSS, Framer Motion    |
| **Auth**     | (Optional) JWT-based API authentication     |
| **Routing**  | React Router DOM                            |

---

## 🔧 Getting Started

### 🐍 Backend (Flask)

```bash
cd backend
python -m venv venv
source venv/bin/activate  # Or use venv\Scripts\activate on Windows
pip install -r requirements.txt
# Configure .env for DB and SMTP credentials
python app.py
```

---

### 📱 Mobile App (Flutter)

```bash
cd App/paris
flutter pub get
flutter run
```

---

### 💻 Web App (React + Tailwind)

```bash
cd Frontend/Hospitality-management-system
npm install         # or yarn install
npm run dev         # or yarn dev
```

Runs at: [http://localhost:5173](http://localhost:5173)

To build for production:

```bash
npm run build       # or yarn build
```

---

## 💠 Backend API Overview

RESTful endpoints are organized modularly:

| Endpoint       | Functionality                      |
| -------------- | ---------------------------------- |
| `/booking`     | Room booking and management        |
| `/event`       | Event scheduling and details       |
| `/restaurant`  | Restaurant reservations and orders |
| `/employee`    | Staff CRUD operations              |
| `/maintenance` | Track maintenance requests         |

➡️ Example: `POST /booking` — Book a hotel room

---

## 📬 Email Integration

* Uses **Flask-Mail** for sending booking confirmations.
* Make sure to set SMTP values in `.env`.

---

## 🔒 Authentication (Optional)

* JWT-based token authentication can be integrated to secure the API endpoints.

---

## 🌐 Live Demo (Frontend Only)

👉 [Hosted Frontend Demo (Vercel)](https://hospitality-management-system-3z1z-4ceipl064-actinkers-projects.vercel.app)

⚠️ *Note: This deployment showcases only the React frontend. Backend must be hosted separately using services like ngrok or cloud platforms.*

---

## ✨ Frontend Highlights

* ⚡ Built with React + Vite for fast performance
* 🎨 Tailwind CSS-styled responsive design
* 🌙 Framer Motion animations & transitions
* 🔄 Swiper.js integration for sliders
* 🔗 REST API integration for dynamic data

---

## 📦 Frontend Project Structure

```plaintext
src/
📌 components/      # Reusable UI components
📌 contents/        # Static data or mock content
📌 pages/           # Page-level components
📌 routes/          # Routing configuration
📌 styles/          # Custom CSS/Tailwind classes
📌 utils/           # Helper functions
📌 App.jsx
📌 config.js        # API base URL config
📌 index.css
📌 main.jsx
```

---

## ⚖️ Configuration

* API base URL is set in `src/config.js`.
* Make sure this matches your backend server address (e.g., ngrok URL).

---

## 🎮 Demo Video

📹 [Watch on Google Drive](https://drive.google.com/file/d/1KQLeWcc61L0FReqLQfV-EMo8kZkSjmG3/view?usp=sharing)

---

## ❤️ Made with Love by Team Continental

> A modern full-stack application to streamline hotel and restaurant operations — from the palm of your hand to the admin's desk.
