# Astronomy Daily – NASA APOD Web App

A web application that displays daily astronomical content using NASA’s **Astronomy Picture of the Day (APOD) API**. The project was built with modern frontend tooling and focuses on API consumption, clean code, and responsive UI.

---

## Project Overview

Astronomy Daily fetches data from NASA’s APOD API and dynamically displays:

* Astronomy image or video of the day
* Title and publication date
* Scientific explanation provided by NASA

The content is updated daily and rendered automatically when the application loads.

---

## NASA APOD API

The Astronomy Picture of the Day (APOD) API is an open NASA service that provides curated daily astronomy content.

Official documentation:
[https://api.nasa.gov/](https://api.nasa.gov/)

API responses may include:

* Image or video URL
* Media type (image or video)
* Title
* Explanation
* Date

---

## Features

* Fetches and displays daily astronomy content
* Supports both images and embedded videos
* Fully responsive layout
* Clean and organized codebase
* Uses modern frontend tooling (Vite + ESLint)

---

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6+)
* Vite
* ESLint
* NASA APOD API

---

## Project Structure

```
project-root/
│
├── .gitignore
├── index.html
├── README.md
├── eslint.config.js
├── package.json
├── package-lock.json
├── vite.config.js
└── src/
    ├── main.js
    └── style.css
```

---

## How the Application Works

1. The application sends a request to the NASA APOD API when the page loads.
2. The API returns the daily astronomy data in JSON format.
3. JavaScript processes the response and dynamically updates the DOM with:

   * Title
   * Image or video
   * Explanation
   * Date

---

## API Key Configuration

To run the project locally, you need a NASA API key.

1. Visit [https://api.nasa.gov/](https://api.nasa.gov/)
2. Generate a free API key
3. Add the key to your JavaScript file:

```js
const API_KEY = "YOUR_API_KEY_HERE";
```

You can also use `DEMO_KEY`, but it has limited request capacity.

---

## Running the Project Locally

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repository-name.git
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

4. Open the application in your browser using the local URL provided by Vite.

---

## Scripts

Available npm scripts:

* `npm run dev` – starts the development server
* `npm run build` – builds the project for production
* `npm run preview` – previews the production build

---

## Future Improvements

* Select astronomy content by date
* Save favorite images
* Dark mode
* Internationalization (i18n)

---

## License

This project is intended for educational purposes and uses data provided by NASA Open APIs.

---

## Author

Developed by **Isabela Miranda]**

Future Software Engineer 
