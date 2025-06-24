# 🏠 Find Your Roommates

A responsive and modern web application to help people find suitable roommates. Users can post their available rooms with pricing, and also explore room posts created by others. Whether you're searching for a place or sharing yours — this is the place! 💼🛏️

---

## 🔗 Live Links

🌐 **Client (Frontend)**: [https://your-client-live-link.com](https://find.roommates.surge.sh)  
🛠️ **Server (Backend)**: [https://your-server-live-link.com](https://roommate-server-side-nu.vercel.app)

_(Replace with your actual deployment links)_

---

## ✨ Features

- 📝 Users can post available rooms with details and pricing
- 💸 Price visibility for every room
- 🔍 Browse room posts easily and quickly
- 🔐 Firebase authentication for secure login/register
- 📱 Fully responsive design with smooth animations
- 🧠 Clean UX with alerts, tooltips, and modern UI components

---

## 🛠️ Tech Stack

### 🎨 Frontend

| Library | Purpose |
|--------|---------|
| `react`, `react-dom` | Core UI framework |
| `react-router` | Routing |
| `tailwindcss`, `daisyui` | Styling & components |
| `react-awesome-reveal` | Scroll animations |
| `react-simple-typewriter` | Typewriter effects |
| `lucide-react`, `react-icons` | Icons |
| `react-toastify`, `sweetalert2` | Toasts & Alerts |
| `react-tooltip` | Tooltips |
| `firebase` | Authentication |
| `react-responsive-carousel` | Carousel display |

---

### ⚙️ Backend

| Library | Purpose |
|--------|---------|
| `express` | Node.js server |
| `cors` | Cross-Origin access |
| `dotenv` | Environment variable management |
| `mongodb` | NoSQL database |

---

## 🗂️ Folder Structure

find-your-roommates/
│
├── client/ # React frontend
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── hooks/
│ │ ├── App.jsx
│ │ └── main.jsx
│ └── tailwind.config.js
│
├── server/ # Express backend
│ ├── routes/
│ ├── controllers/
│ ├── models/
│ └── index.js
