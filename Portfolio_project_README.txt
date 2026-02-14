Portfolio Frontend

This is the frontend of the Personal Portfolio Full-Stack Project.
It is built using HTML, CSS, and JavaScript with a mobile-first responsive design approach.

The frontend communicates with a backend REST API to dynamically fetch and display project data and to submit contact form information.

🚀 Features

Responsive mobile-first layout

Multi-page navigation (Home, About, Projects, Contact)

Dynamic project cards using Fetch API

Contact form connected to backend API

Dark / Light theme toggle

Sticky navbar with scroll effect

Clean and modular folder structure

🛠️ Technologies Used

HTML5 (Semantic Structure)

CSS3 (Flexbox & Grid)

JavaScript (ES6+)

Fetch API

📂 Folder Structure
client/
│
├── index.html        # Home page
├── about.html        # Profile & education details
├── projects.html     # Dynamic project listing
├── contact.html      # Contact form page
│
├── css/
│   ├── style.css         # Main styling
│   └── responsive.css    # Media queries (Mobile-first)
│
├── js/
│   ├── main.js       # UI interactions & theme toggle
│   └── api.js        # Fetch API calls
│
└── assets/
    ├── images/
    ├── icons/
    └── resume.pdf

🔗 Backend API Integration

The frontend interacts with the backend using:

GET /api/v1/projects → Fetch project data

POST /api/v1/contact → Submit contact form

Example API call:

fetch("http://localhost:5000/api/v1/projects")

▶️ How to Run

Make sure backend server is running (if using dynamic data)

Open index.html in your browser

Navigate through pages

🎯 Purpose

This frontend demonstrates:

Modular UI architecture

Responsive design principles

Dynamic content rendering

API integration using JavaScript

👨‍💻 Author

Hemanth J R
Engineering Student | Full Stack Developer