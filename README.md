# 🌌 Astronomy Daily – NASA APOD Web App

A web application that displays **daily astronomical events and images** using NASA’s **Astronomy Picture of the Day (APOD) API**. The project focuses on simplicity, clean UI, and API consumption, making it ideal for learning and showcasing frontend and API integration skills.

---

## 🚀 Overview

Astronomy Daily fetches data directly from NASA’s APOD API and presents:

* The **astronomical image or video of the day**
* A **detailed scientific explanation** provided by NASA
* The **title and date** of the event

The application updates daily and allows users to explore astronomy content in an intuitive and visually appealing way.

---

## 🛰️ NASA APOD API

The **Astronomy Picture of the Day (APOD)** API is a public NASA service that provides daily astronomy content curated by professional astronomers.

API Documentation:
[https://api.nasa.gov/](https://api.nasa.gov/)

Each response may include:

* Image or video (YouTube/Vimeo)
* Title
* Explanation
* Date
* Media type

---

## ✨ Features

* 📅 Displays the astronomy content of the current day
* 🖼️ Supports both images and videos
* 📖 Shows full scientific explanation from NASA
* 🌍 Responsive layout for desktop and mobile
* ⚡ Fast API requests and dynamic rendering

---

## 🛠️ Technologies Used

* **HTML5** – Application structure
* **CSS3** – Styling and responsive design
* **JavaScript (Vanilla)** – API consumption and DOM manipulation
* **NASA APOD API** – External data source

---

## 📂 Project Structure

```
project-root/
│
├── index.html      # Main HTML file
├── style.css       # Application styles
├── script.js       # API logic and DOM updates
└── README.md       # Project documentation
```

---

## ⚙️ How It Works

1. The app sends a **fetch request** to the NASA APOD API.
2. The API returns the daily astronomy data in JSON format.
3. JavaScript dynamically updates the page with:

   * Title
   * Image or embedded video
   * Description
   * Date

---

## 🔑 API Key Setup

To run the project locally:

1. Access [https://api.nasa.gov/](https://api.nasa.gov/)
2. Generate a free API key
3. Replace the API key in `script.js`:

```js
const API_KEY = "YOUR_API_KEY_HERE";
```

⚠️ You can also use `DEMO_KEY`, but it has limited requests per hour.

---

## ▶️ How to Run Locally

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repository-name.git
```

2. Open `index.html` in your browser

No server or build tools are required.

---

## 📸 Screenshots

*Add screenshots or GIFs here to demonstrate the UI.*

---

## 🎯 Future Improvements

* 📆 Select astronomy content by date
* ⭐ Save favorite images
* 🌙 Dark mode
* 🌐 Internationalization (i18n)

---

## 📄 License

This project is for educational purposes and uses data provided by **NASA Open APIs**.

---

## 👩‍💻 Author

Developed by **[Your Name]**
Software Engineer | Web Developer

---

✨ Explore the universe, one day at a time.
Web app that shows daily astronomical events using NASA’s APOD API.
