# Safarino - Trip Planner Web Application

Welcome to **Safarino**, a powerful and intelligent **Trip Planner web application** built with **Django**. This platform is designed to help travelers create detailed, smart travel itineraries tailored to their preferences. Safarino is more than just a trip planner; it's a community where users can plan trips, book accommodations, leave reviews, and much more.

---


## 📆 Key Features

### ✈️ Smart Trip Planning

* Users are guided through a series of questions regarding their **travel preferences**, such as trip type, interests, travel time, and budget.
* Based on the responses, the platform generates a **custom travel itinerary**.

### 🌍 Interactive Daily Itinerary

* Each day of the trip is presented with suggested locations to visit.
* Includes an **interactive map** showing those places.
* A **day-switch menu** allows users to navigate through daily plans.

### 🏨 Hotel Booking

* Recommended hotels suitable to the traveler's profile and budget.
* Easy access to **hotel booking options**.

### 🍽️ Food & Restaurant Suggestions

* Suggests **restaurants, fast food**, and **cafes** for **breakfast, lunch, and dinner**.

### 💬 Reviews and Ratings

* Users can write reviews and rate:

  * Cities
  * Places
  * Hotels
  * Restaurants

### 📄 Blog Section

* A built-in **blog system** to share:

  * Travel guides
  * City highlights
  * News and updates

### 🚌 Transport Booking

* Offers access to **online ticketing**:

  * Train
  * Bus
  * Airplane
  * Other public transport

### 👤 User Authentication

* **Sign up / Login** system with form-based and **Google login integration**.

---

## ✨ Upcoming Features

### 🤝 Find Travel Companions

* Travelers looking for a **companion** can provide their preferences and details.
* The system will **match users** based on their travel compatibility.

### 🏡 Host Spaces for Rent

* Users can list their **available rooms or properties** for others to book instead of hotels.
* Great for **local stays and budget travelers**.

---

## 📖 Tech Stack

* **Backend:** Django (Python)
* **Frontend:** HTML5, CSS3, JS, Bootstrap/Tailwind (planned)
* **Database:** SQLite (development), PostgreSQL/MySQL (planned)
* **APIs:** Google Maps API (for maps), third-party transport & booking APIs

---

## 🔧 Installation Guide

```bash
# Clone the repository
git clone https://github.com/Petrosbid/Safarino_website.git
cd Safarino_website

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start the development server
python manage.py runserver
```

---

## 📁 Project Structure (Simplified)

```
Safarino_website/
├── core/                 # Main app with models/views/templates
├── templates/            # HTML templates
├── static/               # Static files (CSS, JS, images)
├── media/                # Uploaded media
├── users/                # User authentication & profiles
├── trips/                # Trip creation logic
├── reviews/              # Ratings and comments
├── blog/                 # Blog articles
├── booking/              # Ticket and hotel booking logic
├── manage.py
```

---

## 📊 Contribution

We welcome contributions from developers, designers, and travel lovers. Feel free to fork the project, submit issues, or make pull requests.

---

## 📅 License

This project is licensed under the **MIT License**.

---

## 🚀 Author

Developed with passion by [Petrosbid](https://github.com/Petrosbid)

For suggestions, collaborations, or questions, feel free to open an issue or contact me directly.

---

## 🌐 Meta Description

Safarino is a powerful Django-based travel planner web app where users can plan custom itineraries, find travel companions, book hotels, and discover top-rated places with reviews.

