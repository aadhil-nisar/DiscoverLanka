# DiscoverLanka – Fullstack Travel Planning Platform

## Project Overview

DiscoverLanka is a fullstack travel planning web application designed to help users explore Sri Lanka and generate smart, personalized travel itineraries.

This system combines a modern frontend with a backend, database, and AI-powered planner to create a complete travel platform.

This project is developed as a **university student project** and is currently in the development phase.

---

## Key Features

### Destination Exploration

* Explore Sri Lanka by categories:

  * Beaches
  * Hill Country
  * Heritage Sites
  * Wildlife
  * Waterfalls
* Interactive destination cards and sections

---

### AI Smart Trip Planner

Users can enter:

* Starting location
* Destination
* Trip duration
* Budget
* Travel style
* Transport type
* Interests and preferences

System generates:

* Route flow (e.g., Colombo → Kandy → Nuwara Eliya)
* Stops along the way
* Local food and experiences
* Budget breakdown
* Transport guidance
* Day-by-day itinerary
* Smart travel tips

---

### Manual Itinerary Planner

* Create custom travel plans manually
* Add stops, destinations, and notes
* Structured itinerary output
* Printable travel plan (voucher-style design)

---

### 👤 User Authentication

* User registration and login system
* Email verification (optional)
* Profile management

---

### Reviews System

* View traveler reviews
* Submit new reviews
* Filter reviews by rating

---

### Contact & Support

* Contact form
* Help Center (FAQ)
* Blog and About pages
* Privacy Policy and Terms

---

## Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript (Vanilla JS)
* Font Awesome
* Google Fonts

---

### Backend

* PHP (Core PHP)
* REST-style API endpoints
* JSON-based responses

---

### Database

* MySQL
* Main tables:

  * users
  * reviews
  * itineraries (planned/future)

---

### AI Integration

* Google Gemini API
* Used to generate smart travel itineraries

---

## Project Structure

DiscoverLanka/

├── ai-server/
│ ├── .env
│ ├── package.json
│ ├── server.js
│ └── server.js.bak
│
├── assets/
│ └── images/
│ └── destinations/
│
├── backend/
│ ├── api/
│ │ ├── ai-plan-trip.php
│ │ ├── auth.php
│ │ ├── contact.php
│ │ ├── itineraries.php
│ │ ├── newsletter.php
│ │ ├── profile.php
│ │ └── reviews.php
│ │
│ ├── config/
│ │ ├── ai.php
│ │ ├── db.php
│ │ └── email.php
│ │
│ ├── middleware/
│ │ └── helpers.php
│ │
│ └── database.sql
│
├── css/
│ ├── auth.css
│ ├── category.css
│ ├── plan-trip.css
│ ├── profile.css
│ ├── signin.css
│ └── style.css
│
├── js/
│ ├── auth.js
│ ├── category.js
│ ├── plan-trip.js
│ └── script.js
│
├── about.html
├── blog.html
├── category.html
├── contact.html
├── help.html
├── index.html
├── itinerary-planner.html
├── places.html
├── plan-trip.html
├── privacy.html
├── profile.html
├── reviews.html
├── signin.html
├── terms.html
│
├── .gitattributes
└── README.md

---

## Future Improvements

* Payment and booking system
* Google Maps integration
* Save and share itineraries
* Admin dashboard
* Image uploads for reviews
* Mobile app version

---

## Author

**Aadhil Nisar**  
Fullstack project for **DiscoverLanka**  
University student project based on Sri Lanka travel discovery and trip planning.

---

## Note

This project is currently in development and is created for educational and demonstration purposes.

---

## 🌐 Live Frontend

www.discoverlanka.live

