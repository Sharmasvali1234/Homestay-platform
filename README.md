# 🏡 StayEase - Homestay Booking Platform

StayEase is a full-stack MERN web application that allows hosts to list their homestays and customers to explore and book them based on location, amenities, and preferences. It's designed to make short-term rentals easy, efficient, and accessible for both hosts and travelers.

---

## 🚀 Features

### 🔹 For Hosts:
- Sign up / Login as a host
- Add new listings (homestays, plots, villas, etc.)
- Upload multiple photos for each listing
- Specify details like city, province, country, category, and price
- View, edit, and delete your own listings
- Accept or reject booking requests from customers
- Communicate with customers upon booking confirmation

### 🔹 For Customers:
- Sign up / Login as a customer
- Browse and filter homestays by location and category
- View listing details with images, location map, and description
- Send booking requests to hosts
- Track booking status (Pending, Confirmed, Rejected)
- Leave reviews and feedback on listings

---

## 🛠️ Tech Stack

- **Frontend:** React.js, SCSS, React Router
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (with Mongoose)
- **State Management:** Redux
- **Authentication:** JWT-based auth
- **Cloudinary** (for image upload)
- **Map Integration:** Leaflet.js (OpenStreetMap)

---

## 📸 Screenshots

> _Add some screenshots here to showcase your UI (optional)_

---

## 📁 Folder Structure

/client --> React frontend
/server --> Express backend with API routes
/redux --> Redux setup for user, trip, listings
/components --> Reusable UI components (Navbar, Card, etc.)




---

## ⚙️ Getting Started

### ✅ Prerequisites
- Node.js and npm
- MongoDB
- Cloudinary Account (for image uploads)
- Git

### 🚩 Setup Instructions

```bash
# 1. Clone the repository
git clone https://github.com/Sharmasvali1234/Homestay-platform.git

# 2. Navigate into project folder
cd Homestay-platform

# 3. Install dependencies
cd client
npm install
cd ../server
npm install

# 4. Create environment files (.env)
# Example for server/.env:
PORT=3001
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_key
CLOUDINARY_API_SECRET=your_secret

# 5. Run the app
# Terminal 1: Start backend
cd server
npm start

# Terminal 2: Start frontend
cd client
npm start
