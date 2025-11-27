# Luxuria - Premium Furniture E-commerce

![Project Banner](https://images.unsplash.com/photo-1555041469-a586c61ea9bc?q=80&w=2070&auto=format&fit=crop)

**Luxuria** is a modern, luxurious e-commerce interface designed for high-end furniture brands. Built with **Next.js** and **React**, this project focuses on delivering a premium user experience (UX) with smooth animations, minimalist design, and responsive layout.

> **Note:** This is a **Frontend-focused demo**. The database connections have been mocked/bypassed to allow easy setup and UI development without requiring a MongoDB instance.

## ✨ Key Features

* **🎨 Premium UI/UX:** Minimalist design with Serif typography (*Playfair Display*) and whitespace optimization.
* **📱 Fully Responsive:** Optimized for mobile, tablet, and desktop viewing.
* **🛍️ Cart Management:** Real-time shopping cart functionality using **Redux**.
* **🔐 Modern Auth UI:** Redesigned Login & Register pages with split-screen layout and glassmorphism effects.
* **⚡ Smooth Animations:** Interactive elements powered by **Framer Motion** and CSS animations.
* **🔎 Product Filtering:** Category filtering with sliding tab effects.
* **📦 No Database Required:** Uses mock data and simulated API calls for instant deployment and testing.

## 🛠️ Tech Stack

* **Framework:** [Next.js](https://nextjs.org/)
* **Styling:** Bootstrap 5, Custom CSS, Tailwind CSS (Utility classes)
* **State Management:** Redux (react-redux)
* **Icons:** FontAwesome, React Icons, Custom SVGs
* **Animations:** Framer Motion, CSS Keyframes
* **Data:** Local JSON Mock Data

## 🚀 Getting Started

Follow these steps to run the project locally on your machine.
### 1. Install dependencies
npm install
# or
yarn install

### 2. Run the development server
npm start


📂 Project Structure
src/
├── app/              # Next.js App Router pages
├── components/       # Reusable UI components (Navbar, Footer, Products...)
├── redux/            # State management (Cart actions/reducers)
├── data/             # Mock JSON data for products
├── styles/           # Global styles
└── libs/             # Utility functions

