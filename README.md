

# 📘 Forward Fitness Club — Responsive Website (HTML5, CSS3, Bootstrap 4, jQuery)

This repository contains a complete, fully responsive multi-page fitness website built as part of a web development learning project.
The goal of the project was to demonstrate mastery of **semantic HTML**, **responsive design**, **Bootstrap components**, **media queries**, **custom CSS**, and **jQuery DOM manipulation**.

The website includes hero images, a mobile-friendly navigation bar, Bootstrap grid layouts, styled tables, responsive images, and a functional contact form layout.

---

## 🚀 What This Project Covers

This repo showcases a wide range of front-end development concepts, including:

### **✔ Responsive Design Fundamentals**

* Mobile-first development
* Viewport meta configuration
* Responsive images (`img-fluid`, `rounded`, `float-right`)
* Media-query-driven layout changes

### **✔ Bootstrap 4 Components & Utilities**

* Navigation bar with hamburger menu (`navbar-expand-sm`)
* Jumbotron & hero sections (`jumbotron-fluid`)
* Bootstrap grid system (rows + 12-column layout)
* Margin & padding utilities (`my-5`, `px-3`, `mx-auto`)
* Typography utilities (`display-1`, `lead`, `font-weight-light`)
* Buttons & button groups (`btn`, `btn-lg`, outline buttons)
* Table styling (`table`, `thead-dark`, `table-hover`, `table-striped`)

### **✔ Custom CSS Enhancement**

* Hero background images using:

  * **Linear gradients**
  * **Background positioning**
  * **Full-screen scaling**
* Precise content alignment with Flexbox
* Additional typography and layout styling in `styles.css`

### **✔ jQuery DOM Manipulation**

Includes a lightweight script (`scripts/script.js`) that:

* Sets hero section height equal to viewport height using:

  ```javascript
  $('.hero').height($(window).height());
  ```
* Ensures full-screen hero image scaling across devices

### **✔ Semantic, Well-Organized HTML5**

All pages use:

* `<header>`, `<nav>`, `<main>`, `<footer>`
* Landmark roles for accessibility
* Alt text for all images
* Clear class naming and page structure

---

## 📂 Pages Included in This Project

### **🏠 `index.html` — Home Page**

* Large hero image with gradient overlay
* Three-column Bootstrap grid featuring:

  * Group Fitness
  * Nutrition Planning
  * Personal Training

### **ℹ️ `about.html` — About Us**

* Jumbotron page header
* Multi-row Bootstrap grid layout describing:

  * Weight training
  * Cardio equipment
  * Personal training services

### **📅 `classes.html` — Fitness Class Schedule**

* Mobile friendly list layout
* Tablet & desktop Bootstrap table featuring:

  * Striped rows
  * Hover interactions
  * Dark table header (`thead-dark`)

### **🥗 `nutrition.html` — Nutrition Guidance**

* Three-column layout with images and headings:

  * Food for Thought
  * Nutrition Guide
  * Meal of the Week (Herb Roasted Chicken recipe)

### **📞 `contact.html` — Contact & Free Trial**

* Click-to-call button on mobile
* Embedded Google Maps location
* A clean Bootstrap-styled form with:

  * Required fields
  * Form groups & inline checkboxes
  * Custom select element

### **🎨 `css/styles.css`**

Contains:

* Hero styling
* Typography spacing
* Layout adjustments
* Custom responsive classes

### **🧩 `scripts/script.js`**

Contains:

* jQuery document ready event
* Hero height calculation script

---

## 🔧 Technologies Used

| Technology            | Usage                                      |
| --------------------- | ------------------------------------------ |
| **HTML5**             | Semantic markup, layout structure          |
| **CSS3**              | Custom styling, responsive layout          |
| **Bootstrap 4.3.1**   | Grid system, components, utilities         |
| **jQuery 3.3.1**      | DOM manipulation & dynamic layout handling |
| **Google Maps Embed** | Location display on contact page           |

---

## 📌 Key Learning Outcomes Demonstrated

Anyone reviewing this repo will see your mastery of:

* Building a complete multi-page responsive site
* Applying Bootstrap grids and components effectively
* Combining custom CSS with framework utilities
* Structuring semantic HTML for accessibility and maintainability
* Enhancing UI using jQuery for dynamic behavior
* Integrating external resources (icons, favicons, maps, CDNs)

This project is a **strong portfolio-quality example** for front-end development and demonstrates both breadth and depth of skill.

---

## 📁 How to Run This Project

1. Clone or download the repository
2. Ensure the `images/`, `css/`, and `scripts/` folders stay intact
3. Open any `.html` file directly in your browser
4. For best results, open DevTools → Toggle Device Toolbar to view mobile responsiveness

---

## 🎯 Future Enhancements (If You Want to Expand)

* Add form validation with JavaScript
* Create a dedicated blog or news page
* Add animations using CSS transitions or jQuery effects
* Convert to Bootstrap 5 and update components
* Deploy using GitHub Pages for public viewing

