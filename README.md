# AgriLens 🌾
**Bridging the Gap Between Farmers and Fair Prices.**

AgriLens is a comprehensive, direct-to-buyer marketplace and soil intelligence platform designed to eliminate middlemen in agriculture. It empowers farmers to list their harvests at fair prices and provides data-driven insights through an AI-powered Soil Intelligence module.

---
👥 Team
Gurlal Singh (Lead Developer)

Piyush Dhingra

Gautam Bishwas

Nitin Thakur

## 🚀 Features

* **Direct Marketplace:** A transparent platform where farmers list crops and buyers connect directly, removing brokers.
* **Soil Intelligence Engine:** Analyze regional soil health (NPK, pH levels) to receive AI-backed crop recommendations.
* **Secure Authentication:** OTP-based registration and login system for user verification.
* **Real-time Admin Dashboard:** A robust control panel for admins to manage user data, soil analytics, and listing approvals.
* **WhatsApp Integration:** Direct communication channels between farmers and buyers to negotiate deals.

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Modern/Responsive), FontAwesome.
* **Backend:** PHP (Native/Server-Side Rendering).
* **Database:** MySQL (Relational Database).
* **Authentication:** Session-based (with bcrypt support planned).

## 📂 Project Structure

```text
/
├── assets/            # CSS, JS, and Image files
├── db/                # SQL schema files (database.sql)
├── includes/          # PHP reusable components (config, db_connect)
├── uploads/           # User-uploaded crop images
├── admin.html         # Admin control panel
├── index.html         # Landing page
├── login.html         # Login page
├── marketplace.html   # Crop listing view
├── register.html      # User registration
├── soil.html          # Soil intelligence module
└── README.md
