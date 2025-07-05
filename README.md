# Blessed Gebre-Michael Catholic School Website 🌍

This is a fully responsive, full-featured website built for **Blessed Gebre-Michael Catholic Secondary School**, designed to showcase the school’s offerings and allow online student registration with secure database integration.

---

## 📌 Features

- 🏫 **Modern Homepage** – Introduction, school stats, programs, and clubs.
- 📖 **Textbooks Page** – Resource access for students.
- 🧼 **COVID Response Plan** – Health and safety measures taken by the school.
- 🧍‍♂️ **About Page** – Information about the school's mission and values.
- 📝 **Online Registration** – Students can submit registration forms that get saved in a MongoDB database.
- ✅ **Thank You Page** – Confirmation screen after successful registration.
- 📱 **Fully Responsive** – Works on all screen sizes.

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript (Vanilla)
- **Backend**: Node.js + Express
- **Database**: MongoDB (via Mongoose)
- **Deployment Ready**: Can be deployed to Render, Vercel, or Netlify with a MongoDB Atlas DB

---

## 🚀 Getting Started (Local Setup)

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/school-website.git
   cd school-website
   Install Dependencies
   ```

bash
Copy code
npm install
Set Up Environment Variables

Create a .env file in the root directory with the following:

ini
Copy code
MONGODB_URI=your_mongodb_connection_string
PORT=3000
You can use MongoDB Atlas for a free online database.

Start the Server

bash
Copy code
node server.js
Visit http://localhost:3000 in your browser.

🌐 Deployment
To deploy online:

Frontend: Host the public/ folder on Netlify or Vercel.

Backend: Host server.js on Render or another Node.js platform.

Database: Use MongoDB Atlas (free cloud-hosted MongoDB).

Make sure the registration.html form sends data to the deployed backend's /register endpoint.

🙌 Acknowledgments
Built with guidance from school staff at BGMCS.

UI inspired by modern educational websites.

✨ Author
Aida Jemberu

📄 License
This project is for educational purposes and can be adapted with permission.
