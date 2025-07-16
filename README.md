📘 URL Shortener App
A user-friendly React-based URL Shortener application that allows users to shorten long URLs, customize shortcodes, set expiry durations, and track click statistics — all with a clean Material UI design.

🚀 Features
🔗 Shorten up to 5 URLs at a time

✏️ Optional custom shortcode for each URL

⏳ Set custom expiry time (in minutes) or default to 30 minutes

📊 Track analytics for each shortened URL:

Total number of clicks

Timestamp of each click

Referrer/source of click

Coarse-grained geographical location

🔁 Redirection from shortened URL to original long URL

✅ Client-side form validation

🎨 Fully styled using Material UI

🧠 Mock logging middleware integration

🧰 Tech Stack
React.js

React Router

Material UI (MUI)

Axios (for API/mocking)

Git & GitHub (version control)

📂 Project Structure
pgsql
Copy
Edit
url-shortener/
├── src/
│   ├── components/
│   ├── pages/
│   │   ├── ShortenerPage.js
│   │   └── StatisticsPage.js
│   ├── services/
│   │   └── urlService.js
│   ├── App.js
│   └── index.js
├── public/
├── package.json
├── README.md
└── .gitignore
🧪 How to Run Locally
Clone the Repository

bash
Copy
Edit
git clone https://github.com/Keerthi-Vasan-Adhithan/212222240048.git
cd 212222240048/url-shortener
Install Dependencies

bash
Copy
Edit
npm install
Start the App

bash
Copy
Edit
npm start
Visit http://localhost:3000 in your browser.

🧠 Requirements Fulfilled
✅ Shorten links with optional shortcode and expiry

✅ Display original and shortened URLs with creation/expiry dates

✅ Click tracking with timestamp, referrer, and location

✅ Client-side validation for inputs

✅ Material UI used throughout

✅ Mock Logging Middleware (as required)

✅ No login/auth required

✅ All shortcodes are unique

✅ Clean UI and routing with React Router
