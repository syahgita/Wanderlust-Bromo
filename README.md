# 🌄 Wanderlust Bromo

> Explore the Beauty of Bromo with Ease

Wanderlust Bromo adalah website wisata yang dirancang untuk membantu wisatawan menemukan informasi lengkap mengenai Gunung Bromo serta melakukan pemesanan paket wisata secara online dengan mudah dan cepat.

---

## 📖 About The Project

Gunung Bromo merupakan salah satu destinasi wisata paling populer di Indonesia. Namun, banyak wisatawan masih kesulitan mencari informasi paket wisata yang terpercaya dan melakukan reservasi secara praktis.

Wanderlust Bromo hadir sebagai solusi digital yang menyediakan:

- Informasi destinasi wisata Bromo
- Paket wisata lengkap
- Galeri foto destinasi
- Sistem booking online
- Testimoni pelanggan
- Kontak tour guide

---

## ✨ Features

### 👤 User Features
- View informasi destinasi Bromo
- Browse paket wisata
- Booking paket wisata
- Lihat galeri foto
- Kirim pesan melalui halaman kontak
- Melihat testimoni pelanggan

### 🔐 Admin Features
- Login Admin
- Kelola paket wisata (CRUD)
- Kelola booking pelanggan
- Kelola galeri foto
- Kelola testimoni

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript
- React.js
- Bootstrap / Tailwind CSS

### Backend
- Node.js
- Express.js

### Database
- MySQL

### Tools
- Git
- GitHub
- VS Code

---

## 📂 Project Structure

```plaintext
wanderlust-bromo/
│
├── public/
│   ├── images/
│   └── icons/
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── styles/
│   ├── data/
│   ├── App.jsx
│   └── main.jsx
│
├── backend/
│   ├── config/
│   ├── models/
│   ├── controllers/
│   ├── routes/
│   └── server.js
│
├── docs/
│   ├── wireframe.png
│   ├── erd.png
│   └── usecase-diagram.png
│
├── README.md
└── package.json
```

---

## 🗺️ Website Pages

### Home
Menampilkan:
- Hero Section
- Informasi Singkat Bromo
- Paket Populer
- Testimoni
- Footer

### About
Berisi:
- Sejarah Gunung Bromo
- Informasi Wisata
- Lokasi dan Akses

### Packages
Menampilkan:
- Sunrise Tour
- Midnight Tour
- Jeep Adventure
- Camping Package

### Gallery
Menampilkan foto-foto destinasi wisata Bromo.

### Booking
Form pemesanan paket wisata.

### Contact
Informasi kontak dan media sosial.

---

## 🗄️ Database Design

### Users

| Field | Type |
|---------|---------|
| id | INT |
| name | VARCHAR(100) |
| email | VARCHAR(100) |
| password | VARCHAR(255) |

### Packages

| Field | Type |
|---------|---------|
| id | INT |
| package_name | VARCHAR(100) |
| description | TEXT |
| price | DECIMAL |

### Bookings

| Field | Type |
|---------|---------|
| id | INT |
| user_id | INT |
| package_id | INT |
| booking_date | DATE |
| participants | INT |
| total_price | DECIMAL |

### Testimonials

| Field | Type |
|---------|---------|
| id | INT |
| customer_name | VARCHAR(100) |
| review | TEXT |
| rating | INT |

---

## 🚀 Installation

### 1. Clone Repository

```bash
git clone https://github.com/username/wanderlust-bromo.git
```

### 2. Masuk ke Folder Project

```bash
cd wanderlust-bromo
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Jalankan Frontend

```bash
npm run dev
```

### 5. Jalankan Backend

```bash
cd backend

npm install

npm start
```

---

## 📸 Future Improvements

- Online Payment Gateway
- Google Maps Integration
- User Authentication
- Booking History
- Admin Dashboard
- PDF Invoice Generation
- Multi-language Support
- Dark Mode

---

## 🎯 Objectives

Membantu wisatawan dalam:

- Mendapatkan informasi wisata Bromo
- Memilih paket wisata sesuai kebutuhan
- Melakukan booking secara online
- Menghemat waktu pencarian informasi

---

## 👨‍💻 Development Team

Wanderlust Bromo Team

| Name | Role |
|--------|--------|
| Member 1 | Frontend Developer |
| Member 2 | Backend Developer |
| Member 3 | Database Designer |
| Member 4 | UI/UX Designer |

---

## 📄 License

This project is licensed under the MIT License.

---

## 🌅 "Travel Far Enough, You Meet Yourself"

Thank you for visiting Wanderlust Bromo!
