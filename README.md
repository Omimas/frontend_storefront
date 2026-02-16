# Omimas Frontend Storefront

A modern, fast, and responsive e-commerce interface built with **Vanilla JavaScript**. This project focuses on modular frontend architecture, dynamic content rendering, and efficient client-side search algorithms without relying on heavy frameworks.

## 🚀 Key Features

* **Modular Architecture:** Uses a custom `loadHTML` utility to asynchronously inject reusable components like Headers and Footers, improving maintainability.
* **Dynamic Category Routing:** Implements a state-based content switcher that renders products based on categories (Electronics, Fashion, Books, etc.) from a centralized data object.
* **Smart Search Engine:** A robust client-side search functionality that aggregates data across all categories and provides real-time filtering.
* **Dynamic Image Slider:** An automated promotional banner system to showcase discounts and featured products.
* **Fully Responsive UI:** A custom CSS grid and flexbox-based layout optimized for both desktop and mobile users, featuring a sticky navigation header.

## 🛠️ Technical Stack

* **Frontend:** HTML5, CSS3 (Modern Flexbox/Grid)
* **Scripting:** Vanilla JavaScript (ES6+)
* **Asynchronous Logic:** Fetch API for partial loading and dynamic data handling.
* **Styling:** Custom CSS with media queries for cross-device compatibility.

## 📂 Project Structure

```text
├── partials/           # Reusable HTML components (Header, Footer)
├── images/             # Product and UI assets (Banners, Logos)
├── styles.css          # Global styling and responsive design
├── scripts.js          # Core logic (Routing, Search, Slider)
└── index.html          # Main entry point
