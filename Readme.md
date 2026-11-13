# SmartShop 🛍️

> **Your Ultimate Shopping Destination** — A modern, responsive e-commerce web application featuring dynamic catalog management, interactive shopping cart, promo coupon system, and a simulated digital wallet checkout.

🔗 **Live Demo:** [https://zephtix-lab.github.io/SmartShop/](https://zephtix-lab.github.io/SmartShop/)

---

## 📖 Project Description

**SmartShop** is an interactive, client-side e-commerce storefront application designed to provide users with a seamless and intuitive online shopping experience. Built using modern HTML5, vanilla JavaScript (ES6+), Tailwind CSS, and DaisyUI, the platform dynamically fetches merchandise from the FakeStore API, converts prices into Bangladeshi Taka (BDT ৳), and simulates end-to-end shopping workflows.

From browsing trending offers and searching catalog items to managing shopping cart quantities, applying promotional discount vouchers, and paying via a virtual wallet system, SmartShop delivers a polished and realistic shopping experience without requiring a backend server.

---

## ✨ Key Features

- **🌐 Live Product Catalog:** Dynamically retrieves real-world products via the [FakeStore API](https://fakestoreapi.com/) with automated price localization (USD to BDT conversion).
- **🔍 Instant Search & Sorting:** Real-time client-side search by product name and category, paired with sorting options (Price: Low to High, Price: High to Low, Name: A to Z).
- **🛒 Interactive Cart Drawer:** Side-drawer shopping cart allowing quantity adjustments (+/-), item removal, complete cart clearing, and persistent cart state saved via browser `localStorage`.
- **💳 Simulated Digital Wallet & Checkout:** Integrated virtual balance system with a top-up modal and automatic balance deduction during checkout with insufficient funds validation.
- **🎟️ Coupon & Discount System:** Support for discount coupons (e.g., `SMART10` for 10% off) with dynamic updates to subtotal, delivery charges, and final payable amount.
- **🎠 Interactive Sliders:** Automated carousel sliders for promotional deal banners and customer reviews with manual controls and pause-on-hover capability.
- **🔔 Toast Notification System:** Elegant non-blocking visual feedback for adding items to cart, wallet top-ups, errors, and order placement.
- **📱 Fully Responsive Design:** Clean, modern interface crafted with Tailwind CSS and DaisyUI, optimized across mobile, tablet, and desktop screens.
- **📬 Interactive Contact Form:** Built-in contact section with client-side field validation and feedback.

---

## 🛠️ Tech Stack

- **Markup & Logic:** HTML5, Modern JavaScript (ES6+ / Async-Await / Fetch API)
- **Styling & UI:** [Tailwind CSS](https://tailwindcss.com/) & [DaisyUI](https://daisyui.com/)
- **Icons:** [Font Awesome](https://fontawesome.com/)
- **Data Source:** [FakeStore API](https://fakestoreapi.com/) & Local JSON datasets (`bannerCardData.json`, `reviews.json`)
- **State Persistence:** Browser `localStorage` (cart items and wallet balance)

---

## 📂 Project Structure

```text
SmartShop/
├── Public/
│   ├── bannerCardData.json   # Promotional banner data
│   └── reviews.json          # Customer reviews & ratings data
├── app.js                    # Core application logic & DOM interactions
├── index.html                # Main layout and UI structure
├── style.css                 # Custom styles and slider animations
└── Readme.md                 # Project documentation
```

---

## 🚀 Getting Started

To run this project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/zephtix-lab/SmartShop.git
   ```

2. **Navigate into the project directory:**
   ```bash
   cd SmartShop
   ```

3. **Open the project:**
   - Double-click `index.html` to open it in your browser, or
   - Use a local development server like VS Code's **Live Server** extension for the best experience.

---

## 🌐 Live Deployment

Check out the live deployed project on GitHub Pages:  
👉 **[SmartShop Live Demo](https://zephtix-lab.github.io/SmartShop/)**

