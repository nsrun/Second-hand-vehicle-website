# AutoNova ⚡

**AutoNova** is a modern, high-performance, and feature-rich automotive marketplace platform. Originally built as a Django-based application, it has been fully migrated into a **purely static website** using HTML5, CSS3, and vanilla JavaScript.

This project serves as a comprehensive prototype for an Indian vehicle and spare parts marketplace, featuring advanced UI/UX components and client-side logic.

---

## 🚀 Features

### 🛒 Marketplace Ecosystem
- **Dual Listings**: Specialized support for both complete **Vehicles** (Cars, Bikes, Trucks) and **Spare Parts** (Engines, Brakes, Tires).
- **Advanced Browsing**: A robust [browse.html](browse.html) page with category-specific sidebars, multi-parameter filtering, and realistic sample data.
- **Unified Selling Flow**: A streamlined [sell.html](sell.html) page that allows users to toggle between vehicle and part listing forms.
- **Detailed Views**: [vehicle_detail.html](vehicle_detail.html) and [part_detail.html](part_detail.html) provide deep-dive information, technical specifications, and interactive seller cards.

### 🤖 AI-Powered Estimators
- **Vehicle Price Estimator**: Get instant market-value estimates for cars and bikes using custom client-side logic.
- **Spare Part Estimator**: Specialized valuation tool for genuine parts based on condition and category.
- **Client-Side Logic**: All estimation calculations are performed instantly in the browser via JavaScript.

### 🎨 Visual & Interactive Experience
- **Dynamic Hero Animation**: A complex HTML5 Canvas animation on the landing page featuring moving vehicles and road textures.
- **Bootstrap 5 UI**: Fully responsive design using the latest Bootstrap framework with custom-styled "AutoNova" components.
- **Componentized Design**: Consistent navigation bars and a multi-column global footer propagated across 18+ unique pages.

### 👤 User & Informational Pages
- **Interactive Dashboard**: A static dashboard for managing listings, messages, and viewing account statistics.
- **Account Management**: Complete flow including Login, Register, Forgot Password, and Profile Settings.
- **Legal & Help**: Comprehensive About, Contact, FAQ, Privacy Policy, and Terms of Service pages.

---

## 🛠️ Technologies Used

- **HTML5 & CSS3**: Semantic structure and advanced styling.
- **Bootstrap 5.3**: Responsive grid system and UI components.
- **JavaScript (ES6+)**: Custom animations, price estimator logic, and UI interactions.
- **Bootstrap Icons**: Consistent iconography across the platform.
- **Google Fonts**: Premium typography using 'Sora' and 'DM Sans'.

---

## 📂 Project Structure

```text
autonova/
├── css/               # Custom and library styles
│   └── autonova.css   # Core design system
├── js/                # Interactive scripts
│   └── autonova.js    # Core animations and logic
├── index.html         # Main landing page
├── browse.html        # Marketplace listings
├── sell.html          # Listing creation
├── estimator.html     # AI Price Estimator
├── dashboard.html     # User control panel
└── ... (14 other functional & legal pages)
```

---

## 🚦 How to Run

Since this is a static website, it does not require a backend server or database to run.

1. **Clone or Download** the repository to your local machine.
2. **Open index.html** in any modern web browser (Chrome, Firefox, Safari, Edge).
3. **Enjoy!** All features, including the estimators and filters, are functional via client-side logic.

---

## 🇮🇳 Developed for the Indian Market

AutoNova is designed with local context, including INR (₹) currency formatting, Indian vehicle categories, and realistic geographic locations across major Indian cities.

---
© 2026 AutoNova. All rights reserved.
