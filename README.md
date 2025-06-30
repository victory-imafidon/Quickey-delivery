# 🚚 Quickey Delivery

Quickey Delivery is a smart logistics and on-demand delivery platform designed to connect users with trusted riders for fast, affordable, and secure deliveries. It enables users to request, track, and manage pickups from within a simple web-based interface — optimized for mobile and scale.

> 🔧 Built by [Imafidon Victory](https://github.com/victory-imafidon) | PHP, JavaScript, Bootstrap, Firebase | Location-aware + Admin-controlled platform

---

## ✨ Key Features

- 📍 **Real-Time Pickup Requests** – Users can place delivery requests with address & contact info
- 🧭 **Live Tracking & Status Updates** – Admin updates delivery stages (Pending, Picked, Delivered)
- 🗺️ **Google Maps Integration** – View delivery route and pickup address on map
- 👤 **User Dashboard** – Track delivery history and request status
- 🧑‍💼 **Admin Panel** – Rider assignment, order status control, delivery fee management
- 🔔 **Notification System** – Email/SMS/FCM alerts (optional)
- 📱 **Mobile-Optimized (TWA/PWA)** – Acts like an app on Android devices

---

## 🛠 Built With

- **Backend:** PHP (Laravel or native PHP)
- **Frontend:** HTML5, Bootstrap 5, JavaScript
- **Database:** MySQL
- **Geolocation/Maps:** Google Maps JavaScript API
- **Authentication:** Email-based or session-based login
- **Deployment:** Firebase Hosting (TWA), VPS-ready for web

---

## 📈 Use Case

Quickey Delivery was designed to solve a real need: quick intra-city logistics for everyday customers and small businesses. With a clear interface, mobile support, and rider-controlled logic, it streamlines the delivery process from request to doorstep.



## 🔧 Setup for Development

```bash
git clone https://github.com/yourusername/quickey-delivery.git
cd quickey-delivery
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
