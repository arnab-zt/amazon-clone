# 🛒 Amazon Clone

> A responsive Amazon-inspired e-commerce web interface with dynamic cart functionality, built using Vanilla JavaScript, HTML, and CSS.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

---

## 📌 Overview

This project is a front-end clone of Amazon's e-commerce platform, developed to deepen understanding of DOM manipulation, event handling, and responsive UI design. It replicates core shopping features including a product listing page, a functional cart, checkout flow, order history, and order tracking.

---

## ✨ Features

- 🏠 **Product Listing Page** — Grid layout displaying products with images, ratings, prices, and quantity selectors
- 🛒 **Dynamic Cart** — Real-time item count and total price updates using JavaScript DOM manipulation
- ✅ **Add to Cart Feedback** — Animated "Added" confirmation on each product card
- 📦 **Checkout Page** — Summarized order view before placing an order
- 📋 **Orders Page** — Browse past orders with item and price details
- 🔍 **Order Tracking Page** — Track delivery status for individual orders
- 📱 **Responsive Design** — Mobile-friendly layout with adaptive header using CSS media queries
- 🔎 **Search Bar** — Amazon-style search input in the header

---

## 🗂️ Project Structure

```
javascript-amazon-project-main/
├── index.html          # Product listing / main page
├── checkout.html       # Cart & checkout page
├── orders.html         # Order history page
├── tracking.html       # Order tracking page
├── data/
│   └── products.js     # Product data (name, price, rating, image)
├── backend/
│   └── products.json   # JSON data for products (backend simulation)
├── styles/
│   ├── shared/         # Shared styles (header, general)
│   └── pages/          # Page-specific styles
└── images/             # Product images, icons, logos, rating assets
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Page structure and semantic markup |
| **CSS3** | Styling, responsive layouts, animations |
| **JavaScript (Vanilla)** | DOM manipulation, cart logic, event handling |

---

## 🚀 Getting Started

No build tools or dependencies required — just open in a browser!

### Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/arnab-patra-dev/javascript-amazon-project-main.git
   ```

2. **Navigate into the folder**
   ```bash
   cd javascript-amazon-project-main
   ```

3. **Open `index.html`** in your browser

   - Double-click `index.html`, **OR**
   - Use the **Live Server** extension in VS Code for hot-reload

---

## 📸 Pages

| Page | File | Description |
|---|---|---|
| Home / Products | `index.html` | Browse all available products |
| Checkout | `checkout.html` | Review cart and place order |
| Orders | `orders.html` | View order history |
| Tracking | `tracking.html` | Track a specific order |

---

## 🔑 Key Concepts Practiced

- **DOM Manipulation** — Dynamically updating cart count, prices, and UI states
- **Event Handling** — Button clicks, quantity selectors, and form interactions
- **Responsive Web Design** — Flexbox, CSS Grid, and viewport-aware layouts
- **Data-driven UI** — Rendering product cards from a JavaScript data source
- **Multi-page Navigation** — Linking between pages with consistent shared header/footer styling

---

## 📈 What I Learned

Building this project helped me understand how large-scale e-commerce platforms work under the hood. Key takeaways:

- How to separate **data** from **presentation** in plain JavaScript
- The importance of **modular CSS architecture** (shared vs. page-specific styles)
- Managing **UI state** (like cart quantity) without a framework
- Writing clean, readable HTML for complex nested layouts

---

## 👤 Author

**Arnab Patra**  
B.Tech, CSE (AI & ML) — KIET Group of Institutions, Ghaziabad (2023–2027)

- 📧 [clasharnab@gmail.com](mailto:clasharnab@gmail.com)
- 💼 [LinkedIn](https://linkedin.com/in/arnab-patra-dev)
- 🐙 [GitHub](https://github.com/arnab-zt)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

> *Built with ❤️ as part of learning front-end web development fundamentals.*
