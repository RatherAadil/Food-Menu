# 🍽️ Meals Menu Project

A responsive and interactive **Meals Menu** web application built using **HTML**, **CSS**, and **JavaScript**. This project dynamically displays a list of meals and allows users to **filter meals by category** using **dynamically generated filter buttons**.

---

## ✨ Features

- 🧾 Displays a list of meals with images, titles, and descriptions.
- 🧠 Dynamically generates filter buttons based on meal categories.
- ⚡ Real-time filtering of meals when a category is selected.
- 💻 Fully responsive layout for all screen sizes.
- 🎨 Clean and modern UI using plain HTML and CSS.

---

## 📁 Project Structure

meals
│
├── index.html       # Main HTML file
├── style.css        # Styling for the meals and layout
└── app.js        # JavaScript for dynamic filtering
---

## 🚀 How It Works

1. The `script.js` file contains an array of meal objects with properties like `id`, `title`, `category`, `img`, and `desc`.
2. When the page loads, all meals are rendered dynamically using DOM manipulation.
3. Unique categories are extracted from the meal data and used to create filter buttons.
4. Clicking a filter button updates the view to show only meals in that category.