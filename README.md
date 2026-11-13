# Responsive Laundry Services Web App with CSS Hamburger Menu

A responsive laundry service landing page featuring a pure CSS mobile hamburger menu, built using Flexbox, CSS Variables, Media Queries, and pseudo-classes—with zero JavaScript required.

## 📋 Features & Requirements
- **Pure CSS Hamburger Menu:** Uses a hidden checkbox, `<label>`, and the `:checked` pseudo-class with the general sibling combinator (`~`) to toggle a mobile dropdown menu and animate the icon into an `X`.
- **Responsive Navigation Bar:** Built with Flexbox. Displays full navigation links on desktop, scales text on tablets, and switches to a compact bar with a hamburger menu on mobile screens.
- **Adaptive Hero Section:** Uses `flex-direction` changes and media queries to stack content and imagery cleanly on mobile devices without horizontal scrolling.
- **CSS Variables:** Centralizes theme colors and styling values under `:root` for easy maintenance.

## 🛠️ Technologies Used
- HTML5
- CSS3 (Flexbox, Media Queries, CSS Variables, `:checked` & `:nth-child` Pseudo-classes)

## 📂 File Structure
```text
├── index.html   # Main HTML structure with checkbox toggle
├── style.css    # Responsive styles, animations, and media queries
└── README.md    # Project documentation
