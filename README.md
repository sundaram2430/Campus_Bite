# 🍽 CampusBite – Campus Food Ordering App

A **food ordering prototype** built for campus canteens, allowing students to browse menus, add items to cart, and pay — all without standing in a queue.

---

## 🚀 Live Demo

Open `index.html` in any browser — no server or dependencies needed.

---

## 🏪 Canteens Supported

| Canteen | Speciality | Hours |
|---------|-----------|-------|
| **Darshni** | South Indian Breakfast, Snacks, Beverages, Sweets | 7am – 9pm |
| **Oota** | Full Meals, Thali, Rice, Curries, Non-Veg | 7:30am – 9:30pm |

---

## ✨ Features

- 🏪 **Two canteens** – Darshni & Oota with separate menus
- 🗂 **Category filters** – Quickly browse by food type
- 🛒 **Cart system** – Add, remove, adjust quantities
- 💳 **Payment options** – UPI / Card / Pay at Counter
- 🎟 **Order token** – Unique token generated after payment
- 🟢🔴 **Veg / Non-Veg indicators** on every item
- 💬 **Toast notifications** when items are added
- 📱 **Responsive design** – Works on mobile & desktop

---

## 🧾 Menu Overview

### Darshni Canteen
- Breakfast: Idli, Masala Dosa, Poha, Upma, Vada, Puri Bhaji
- Snacks: Samosa, Gobi Manchurian, Bread Pakora, Pani Puri
- Beverages: Chai, Filter Coffee, Lassi, Lime Juice
- Sweets: Kesari Bath, Gulab Jamun

### Oota Canteen
- Meals: Veg Thali, Non-Veg Thali, Mini Meals, Chapati + Dal
- Rice: Veg Biryani, Chicken Biryani, Egg Fried Rice, Curd Rice
- Curries: Paneer Butter Masala, Dal Tadka, Mixed Veg
- Non-Veg: Chicken Curry, Egg Curry, Fish Fry
- Beverages: Buttermilk, Fresh Juice

---

## 📁 Project Structure

```
campusbite/
└── index.html       # Complete single-file app (HTML + CSS + JS)
```

This is intentionally a **single-file prototype** for easy sharing, demo, and GitHub Pages deployment.

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|-----------|
| UI | HTML5 + CSS3 + Vanilla JavaScript |
| Fonts | Google Fonts (Playfair Display + DM Sans) |
| Icons | Emoji (no icon library needed) |
| Hosting | Works directly / GitHub Pages |

---

## 🖥 How to Run

### Option 1 – Open locally
```bash
git clone https://github.com/yourusername/campusbite.git
cd campusbite
open index.html   # or double-click the file
```

### Option 2 – GitHub Pages
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch → `/root`
4. Your app will be live at `https://yourusername.github.io/campusbite`

---

## 📸 Screenshots

> Coming soon – add screenshots of the app here after running it.

---

## 🗺 How It Works

```
Student opens app
    ↓
Selects canteen (Darshni / Oota)
    ↓
Browses menu by category
    ↓
Adds items to cart
    ↓
Reviews cart with total + 5% GST
    ↓
Chooses payment method (UPI / Card / Cash)
    ↓
Order confirmed → Token generated
    ↓
Shows token at counter → Collects food 🎉
```

---

## 📌 Future Enhancements

- [ ] Firebase / Supabase backend for real orders
- [ ] Shop owner dashboard to manage orders
- [ ] Real-time order status tracking
- [ ] Student login with college email (SSO)
- [ ] Push notifications when food is ready
- [ ] Order history & reorder feature
- [ ] Ratings & reviews for food items

---

## 👨‍💻 Built For

Presentation prototype for campus food ordering system.  
Canteens: **Darshni** & **Oota**

---

## 📄 License

MIT License – free to use, modify, and distribute.
