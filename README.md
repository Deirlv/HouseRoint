# 🏠 HouseRoint

![PHP Version](https://img.shields.io/badge/PHP-8.x-%23777BB3?style=for-the-badge&logo=php)
![Version](https://img.shields.io/badge/Version-1.0-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Laravel](https://img.shields.io/badge/Laravel-11-red?style=for-the-badge&logo=laravel)


Welcome to the "**House Right On Point**", a modern web application designed to simplify the process of listing, managing, and renting houses. This platform provides an intuitive interface to handle all housing needs.

---

## 🌟 Features

### For Homeowners:
- **Add/Edit/Delete Houses** – Easily manage your property listings with a user-friendly panel.
- **Image Uploads** – Add up to 5 high-quality images per house to showcase your property.
- **Availability Toggle** – Mark your house as *Available* or *Not Available* with a single click.

### For Renters:
- **Browse Listings** – View available houses with detailed descriptions, pricing, and images.
- **Filter & Pagination** – Effortlessly find the perfect home with filtering options and paginated results.
- **Detailed Views** – Explore each property with a carousel of images and essential details like location and contact information.

### For Admins:
- **Admin Dashboard** – Built with **Filament PHP** for seamless management. Moderate users' profiles and houses. Create roles and add them to users.
- **Statistics** - See statistics through visually clear charts (site visits, user registrations, etc.)
---

## 🛠️ Tech Stack

- **Backend:** Laravel
- **Frontend:** Blade Templates + Bootstrap 5
- **Database:** MySQL
- **File Storage:** Laravel Storage
- **Admin Panel:** Filament PHP
- **JavaScript:** Vanilla JS for dynamic interactions (e.g., image carousel)

---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

- **PHP 8.x**
- **Composer**
- **Node.js** *(optional, for frontend assets)*
- **MySQL Database**

### Installation

#### 1. Clone the Repository
```bash
git clone https://github.com/Deirlv/HouseRoint
cd src
```

#### 2. Install Dependencies
```bash
composer install
npm install
```

#### 3. Set Up Environment Variables
```bash
cp .env.example .env
php artisan key:generate
```
Update `.env` with your database credentials.

#### 4. Run Migrations
```bash
php artisan migrate
```

#### 5. Create the Symbolic Link to Storage
```bash
php artisan storage:link
```

#### 6. Start the Development Server
```bash
php artisan serve
```

#### 7. Access the Application
Open your browser and navigate to:
```
http://localhost:8000 (or other port you're using)
```

---

## 📂 Project Structure

```
├── app/                # Core application logic
├── resources/          # Views, assets
│   ├── views/          # Blade templates
│   └── js/             # JavaScript files
├── routes/             # Web and API routes
├── database/           # Migrations
├── public/             # Public assets (CSS, JS, images)
└── storage/            # Uploaded files and logs
```

---

## 📝 Legal Pages

The platform includes the following legal pages:

- **Privacy Policy** – Explains how user data is collected and used.
- **Terms of Service** – Outlines the rules for using the platform.

These pages ensure compliance with legal requirements.

---

## 📜 License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.

---

## 📧 Contact

Feel free to reach out:

- **Email:** timurzubalwork@gmail.com
- **GitHub:** [@Deirlv](https://github.com/Deirlv)

---

### 🎉 Special Thanks
Thanks to my teacher Oleksandr Nykytin [@ninydev](https://github.com/ninydev) for teaching me laravel. I was neutral about this framework at first, but it ended up being my favorite!
Also a big thank you to the open-source community and the creators of the tools and libraries used in this project!
