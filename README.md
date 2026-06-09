<div align="center">

<img src="./src/assets/image/navbar_logo.png" alt="ZoG Logo" width="80" />

# Z·G Dashboard

### Social Media Order Management Platform

<p>A clean, modern, and fully responsive dashboard for managing social media orders — built with the latest React & Tailwind CSS v4.</p>

<br/>

[![React](https://img.shields.io/badge/React-19.x-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://react.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Vite](https://img.shields.io/badge/Vite-6.x-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![React Router](https://img.shields.io/badge/React_Router-v7-CA4245?style=for-the-badge&logo=reactrouter&logoColor=white)](https://reactrouter.com/)

<br/>

![GitHub repo size](https://img.shields.io/github/repo-size/Nayeem0011/zog-app?style=flat-square&color=6C5CE7)
![GitHub last commit](https://img.shields.io/github/last-commit/Nayeem0011/zog-app?style=flat-square&color=FF6B35)
![GitHub stars](https://img.shields.io/github/stars/Nayeem0011/zog-app?style=flat-square&color=FFD700)

</div>

---

## 🌟 Overview

**Z·G Dashboard** is a social media order management platform where users can track and manage service orders such as **Likes**, **Follows**, **Messages**, and more — across multiple social media platforms.

The app is designed **mobile-first** with a seamless transition to a full-featured **desktop layout**, offering a native app-like experience on all screen sizes.

---

## ✨ Features

| Feature | Description |
|---|---|
| 📊 **Order Dashboard** | View orders grouped by Today / Yesterday with real-time status |
| 🗂️ **Tab Filtering** | Quickly filter orders using Order 1, Order 2, Order 3 tabs |
| ☰ **Side Navigation** | Smooth animated slide drawer with FAQ, News, Account links |
| 🔗 **Add Link Page** | Dedicated full-screen page to add Instagram links and order details |
| 📱 **Responsive Design** | Fully optimized for both Mobile and Desktop with separate layouts |
| 🔍 **Smart Search** | Always visible on Desktop; accessible via drawer on Mobile |
| ✅ **Status Tracking** | Clear **Working** and **Canceled** order status indicators |
| 🚀 **Fast Performance** | Built with Vite for lightning-fast development and builds |

---

## 🗂️ Project Structure

```
zog-app/
│
├── 📁 public/
│
├── 📁 src/
│   ├── 📁 assets/
│   │   └── 📁 font/
│   │   └── 📁 image/
│   │       ├── navbar_logo.png
│   │       └── navbar_profile.png
│   │
│   ├── 📁 components/
│   │   ├── Navbar.jsx              ← Responsive top navigation bar
│   │   ├── AddLinkPage.jsx         ← Standalone Add Link page (mobile route)
│   │   ├── Sidebar.jsx             ← Desktop left panel — Pay card + menu
│   │   ├── Header.jsx              ← Icon tab bar — Like, Follow, Level, etc.
│   │   ├── OrderDashboard.jsx      ← Order filter tabs + list view
│   │   └── OrderList.jsx           ← Desktop right panel — Add Link
│   │
│   ├── App.jsx                     ← Router + main layout
│   ├── main.jsx
│   └── index.css
│
├── index.html
├── vite.config.js
├── package.json
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- **Node.js** v18 or higher
- **npm** v9 or higher

### Installation

```bash
# Step 1 — Clone the repository
git clone https://github.com/Nayeem0011/zog.git

# Step 2 — Move into the project directory
cd zog

# Step 3 — Install all dependencies
npm install

# Step 4 — Start the development server
npm run dev
```

> Open **http://localhost:5173** in your browser.

---

## 🛠️ Tech Stack

| Technology | Version | Purpose |
|---|---|---|
| [React.js](https://react.dev/) | `19.x` | Component-based UI library |
| [Tailwind CSS](https://tailwindcss.com/) | `v4` | Utility-first CSS framework |
| [Vite](https://vitejs.dev/) | `6.x` | Next-generation build tool |
| [React Router DOM](https://reactrouter.com/) | `v7` | Client-side page routing |
| [Lucide React](https://lucide.dev/) | `latest` | Beautiful SVG icon library |


---

## 🗺️ Routes

| Path | Page | Description |
|---|---|---|
| `/` | `Dashboard` | Main dashboard — all components visible |
| `/add-link` | `AddLinkPage` | Standalone Add Link form — no Navbar or Sidebar |

---

## 🎨 Color Palette

<div>

| Swatch | Name | Hex | Usage |
|:---:|---|---|---|
| 🟠 | Orange | `#FF6B35` | Pay button gradient, Logo background |
| 🟣 | Purple | `#6C5CE7` | Active tabs, Next button, FAB button |
| ⚫ | Dark | `#1A1A2E` | Primary text, menu items |
| ⚪ | Light Gray | `#F8F8F8` | Page background |
| 🔵 | Blue | `#4A90D9` | Progress bar indicator |
| 🔴 | Red | `#FF4B4B` | Canceled order status |
| 🩶 | Muted Gray | `#9AA2AB` | Inactive text, placeholder, icons |
| 🍑 | Peach | `#FFC3A9` | Avatar ring background |

</div>

---

## 📦 Available Scripts

```bash
npm run dev        # Start local development server
npm run build      # Build for production
npm run preview    # Preview the production build locally
npm run lint       # Run ESLint for code quality
```

---

## 👤 Author

<div align="center">

<br/>

**Nayeem Islam**

[![GitHub](https://img.shields.io/badge/GitHub-Nayeem0011-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Nayeem0011)
[![Gmail](https://img.shields.io/badge/Gmail-sknayeemislam384@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sknayeemislam384@gmail.com)

<br/>

</div>

---

<div align="center">

⭐ **If you like this project, please give it a star!** ⭐

<br/>

Made with ❤️ by [Nayeem Islam](https://github.com/Nayeem0011)

</div>
