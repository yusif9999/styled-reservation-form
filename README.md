# 📝 Styled Reservation Form

A table reservation page for **Corner Coffee**, a small neighborhood café, built with **HTML** and **CSS** only.

The main goal of this project was to practice **styling form elements with CSS**, especially using **attribute selectors**. Along the way, it also covers a dropdown navigation menu, a styled table and a hero section with a background image.

🔗 **Live Demo:** [yusif9999.github.io/styled-reservation-form](https://yusif9999.github.io/styled-reservation-form/)

## ✨ Features

- **Navigation bar** with a hover dropdown menu (Coffees, Desserts, Drinks)
- **Hero section** with a background image and a dark overlay
- **Opening hours table** with zebra-striped rows, row hover effect and a highlighted closed day
- **Reservation form** with:
  - Name, phone, email, date and time inputs
  - Number of people (select box)
  - Table preference (radio buttons)
  - A note field (textarea)
  - Required fields marked with `*` and a colored left border
  - Custom focus styles and an animated submit button
- **Footer** with address, phone number and social media icons

## 🧠 What I Practiced

| Topic | Where it's used |
|---|---|
| Attribute selectors | `input[required]` to highlight required fields |
| Form styling | Inputs, select, textarea, radio buttons, button |
| Pseudo-classes | `:hover`, `:focus`, `:nth-child()`, `:first-child`, `:last-child` |
| Pseudo-elements | `::after` for the hero overlay, `::placeholder` |
| Dropdown menu | `li:hover > .dropdown` |
| Positioning | `position: relative` / `absolute` for the dropdown and overlay |
| Tables | `border-collapse`, striped rows, hover rows |
| Backgrounds | `background-size: cover`, `rgba()` overlay |
| Icons | Font Awesome |
| CSS nesting | Nested rules for cleaner, grouped styles |

## 🛠️ Built With

- HTML5
- CSS3
- [Font Awesome](https://fontawesome.com/) (icons)

## 📁 Project Structure

```
styled-reservation-form/
├── img/
│   └── bgImage.jpg
├── index.html
├── style.css
└── README.md
```

## 🚀 How to Run

No installation is needed.

1. Clone the repository:
   ```bash
   git clone https://github.com/yusif9999/styled-reservation-form.git
   ```
2. Go into the project folder:
   ```bash
   cd styled-reservation-form
   ```
3. Open `index.html` in your browser.

> An internet connection is needed for the Font Awesome icons to load.

## 📝 Note

This is a front-end practice project. The form is not connected to a backend, so no data is sent when it is submitted.

## 👤 Author

**yusif9999** – [GitHub Profile](https://github.com/yusif9999)