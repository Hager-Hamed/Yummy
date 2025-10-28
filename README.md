<div align="center">

# 🍴 Yummy - Your Go-To Recipe and Food Discovery Platform


## 📑 Table of Contents

- [🌐 Live Demo](#-live-demo)
- [🚀 Features](#-features)
- [🧑‍💻 Technologies Used](#-technologies-used)
- [📂 Project Structure](#-project-structure)
- [⚙️ Usage](#️-usage)
- [🔑 API Integration](#-api-integration)


---

## 🌐 Live Demo

Check out the live demo of **Yummy Platform** at 👉 [Yummy Live Demo](https://)

---

## 🚀 Features

- 🔍 **Recipe Search:** Advanced search functionality with real-time suggestions.
- 🍽️ **Category Exploration:** Browse recipes by meal categories (Breakfast, Lunch, Dinner, Desserts).
- 🌍 **Regional Cuisines:** Discover recipes from different countries and regions.
- 🥬 **Ingredient-Based Search:** Find recipes based on available ingredients.
- 🎨 **Theme Switcher:** Toggle between dark and light themes.
- 📱 **Responsive Design:** Optimized for desktop, tablet, and mobile devices.
- ⚡ **Real-Time Data:** Live recipe data from TheMealDB API.
- 🎭 **Smooth Animations:** Enhanced user experience with hover effects and transitions.
- 📧 **Contact Form:** Direct communication with the development team.
- 🚀 **Fast Loading:** Optimized performance for quick recipe discovery.

---

## 🧑‍💻 Technologies Used

- **HTML5:** Semantic structure and accessibility features.
- **CSS3:** Modern styling with Flexbox and Grid layouts.
- **JavaScript (ES6+):** Dynamic functionality and API interactions.
- **jQuery (v3.6+):** Simplified DOM manipulation and event handling.
- **Bootstrap (v5.3):** Responsive framework and components.
- **Font Awesome (v6.0):** Comprehensive icon library.
- **TheMealDB API:** Real-time recipe and meal data.
- **JSON:** Structured data format for API responses.

📦 **External Dependencies**

- [Bootstrap](https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css)
- [Font Awesome](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css)
- [jQuery](https://code.jquery.com/jquery-3.6.0.min.js)
- [TheMealDB API](https://www.themealdb.com/api.php)

---
## 📂 Project Structure

```
Yummy-Site/
├── assets/
│   └── imgs/                 # Local images and UI assets
├── css/
│   ├── style.css             # Main stylesheet with custom styles
│   ├── all.min.css           # Font Awesome library
│   └── bootstrap.min.css     # Bootstrap framework
├── js/
│   ├── main.js               # Core application logic
│   ├── jsconfig.json         # VS Code configuration for JS/jQuery
│   └── bootstrap.bundle.min.js # Bootstrap JS bundle
├── index.html                # Main HTML file
└── README.md                 # Project documentation
          # Project documentation
```

---

## ⚙️ Usage

- 🔍 **Search Recipes**: Use the search bar to find specific recipes or ingredients.
- 🍽️ **Browse Categories**: Click on category cards to explore different meal types.
- 🌍 **Explore Regions**: Discover international cuisines from the area section.
- 🥬 **Ingredient Search**: Enter ingredients you have to get recipe suggestions.
- 🎨 **Theme Toggle**: Switch between dark and light themes for comfortable browsing.
- 📧 **Contact Us**: Use the contact form for inquiries and feedback.

---
## 🔑 API Integration

The application integrates with **TheMealDB API** for comprehensive meal data:

**Base URL:** `https://www.themealdb.com/api/json/v1/1/`

**Key Endpoints Used:**

- **Search meals by name:** `search.php?s={meal_name}`
- **List all categories:** `categories.php`
- **List all areas:** `list.php?a=list`
- **List all ingredients:** `list.php?i=list`
- **Filter by category:** `filter.php?c={category_name}`
- **Filter by area:** `filter.php?a={area_name}`
- **Filter by ingredient:** `filter.php?i={ingredient_name}`
- **Lookup meal by ID:** `lookup.php?i={meal_id}`

---




</div>