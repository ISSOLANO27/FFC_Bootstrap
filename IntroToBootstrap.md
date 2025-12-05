# Bootstrap

[Introduction](#introduction)

[Exploring Bootstrap](#exploring-bootstrap)

[Bootstrap navigation bar](#bootstrap-navigation-bar)

[Bootstrap Responsive Containers](#bootstrap-responsive-containers)

[Bootstrap Jumbotron](#bootstrap-jumbotron)

[Margins and Padding](#margins-and-padding)

[images](#images)

[Bootstrap Colors](#bootstrap-colors)

[Styling Button](#styling-button)

[Custom Styles](#custom-styles)

[Using JQuery](#using-jquery)

[Styling Tables with Bootstrap](#styling-tables-with-bootstrap)


<br>
<br>
<br>
<br>
<br>



# Exploring Bootstrap

[Back Home](#bootstrap) | [Back](#introduction) | [Forward](#bootstrap-navigation-bar)


Bootstrap is a **popular, mobile-first, front-end, responsive design web framework**. A **web framework** is a development tool built from **HTML**, **CSS**, and **JavaScript**. It provides a **standardized foundation** for building websites and greatly simplifies development by offering **predefined style sheets**, **responsive layout systems**, and **script files** designed to handle common UI patterns.

The Bootstrap homepage, shown in **Figure 12–4**, is available here:

👉 **[https://getbootstrap.com](https://getbootstrap.com)**
Source: getbootstrap.com

As of the publication date referenced in your text, **Bootstrap 4** is the most current version. To begin using Bootstrap, developers must either **download** its CSS/JS assets or **link the framework through the Bootstrap CDN**.

A **CDN (Content Delivery Network)** is a **global network of distributed servers** that delivers files from the server **geographically closest to the user**, improving speed and reducing latency. When a page links to a CDN, assets like style sheets and scripts load **significantly faster**, regardless of the user’s location.

To connect your webpage to the Bootstrap CDN, the chapter provides the standard `<link>` element. This link loads the **minified** version of Bootstrap’s CSS file (**bootstrap.min.css**). Because CDN URLs occasionally update, you should always verify the most current version here:

👉 **[https://www.bootstrapcdn.com](https://www.bootstrapcdn.com)**

If you prefer a readable version of Bootstrap’s stylesheet, you can view the **non-minified** source shown in **Figure 12–5** at:

👉 **[https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.css](https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.css)**
Source: stackpath.bootstrapcdn.com

---

## 🎨 Understanding the Non-Minified Bootstrap CSS (Expanded with Key Terms)

When viewing the non-minified Bootstrap file, you are looking at the **complete design system** Bootstrap uses to style every element and component it supports. It contains:

* **Hundreds of style rules** for HTML elements
* **Structural layout definitions**
* **Grid system configuration**
* **Component-level classes** (buttons, navbars, cards, modals, alerts, forms, tables)
* **Spacing utilities** (`m-`, `p-`, `mt-`, `px-`, etc.)
* **Color and background utilities**
* **Typography utilities** (`lead`, `font-weight-bold`, `text-muted`)
* **Flexbox utilities**
* **Responsive helpers**
* **Media queries** that determine when layout changes occur

This file is generated from Bootstrap’s original **Sass source**, which includes **variables**, **mixins**, **nested rules**, and **maps** that define the entire design language.

Once your webpage links to Bootstrap (via local files or CDN), **all of these style rules automatically apply** to your HTML. You activate them by assigning **class attributes** to elements.

Examples:

```html
<p class="text-white">White text</p>
<img src="photo.jpg" class="rounded">
<div class="bg-primary text-light p-3">Styled block</div>
```

Each of these classes corresponds to a predefined rule in the Bootstrap stylesheet.

For a complete listing of Bootstrap 4 class names, the text references:

👉 **[https://www.w3schools.com/bootstrap4/bootstrap_ref_all_classes.asp](https://www.w3schools.com/bootstrap4/bootstrap_ref_all_classes.asp)**

---

## 🖥️ BTW — Internet Explorer and Bootstrap 4

Bootstrap 4 is **not supported** by **Internet Explorer 9** or earlier.
These browsers lack support for many of the modern CSS features (flexbox, viewport units, transitions) that Bootstrap 4 depends on.

This is why modern frameworks generally consider IE9 “legacy” or “unsupported.”

---

## 🌐 Bootstrap Starter Template

Bootstrap provides an official **Starter Template**, shown in **Figure 12–6**, located at:

👉 **[https://getbootstrap.com/docs/4.3/getting-started/introduction/](https://getbootstrap.com/docs/4.3/getting-started/introduction/)**
Source: getbootstrap.com

The starter template includes:

* Basic **HTML5 document structure**
* Required **meta viewport** tag for responsive scaling
* `<link>` to Bootstrap’s CSS
* Three `<script>` elements above `</body>` linking to:

  * **jQuery**
  * **Popper.js**
  * **Bootstrap’s JavaScript**

These scripts unlock Bootstrap’s interactive components.

### Why these scripts matter:

* **jQuery** enables event handling and DOM manipulation
* **Popper.js** manages element positioning (especially **dropdowns**, **tooltips**, **popovers**)
* **Bootstrap’s JS** activates components like the **hamburger menu**, **collapse**, **modals**, **carousels**, and **dropdowns**

Without these dependencies, Bootstrap’s dynamic features will not function.

---

## 📱 Consider This — Expanded: How Many Media Queries Does Bootstrap Use?

Bootstrap 4.3 is built around **four primary responsive breakpoints**:

| Breakpoint | Min Width | Device Category |
| ---------- | --------- | --------------- |
| **sm**     | 576px     | Large phones    |
| **md**     | 768px     | Tablets         |
| **lg**     | 992px     | Laptops         |
| **xl**     | 1200px    | Desktops        |

Bootstrap uses these breakpoints across its **grid system**, **spacing utilities**, **typography scaling**, and **component structure**.

### Why these specific breakpoints?

Bootstrap’s breakpoints reflect:

* **Common device dimensions worldwide**
* **Stability** across browser rendering engines
* **Predictable layout behavior**
* **Years of real-world responsive design testing**

These breakpoints represent the "sweet spots" where layouts tend to fail or require reorganization.

### Why you should match Bootstrap’s breakpoints

When writing your own media queries, using the same breakpoints ensures:

* Layout consistency
* Predictable stacking behavior
* Harmony between your custom CSS and Bootstrap’s grid
* Easier debugging

For example:

```css
@media (min-width: 576px) { … }
@media (min-width: 768px) { … }
@media (min-width: 992px) { … }
@media (min-width: 1200px) { … }
```

By aligning your custom rules with Bootstrap’s, you avoid conflicting behaviors or unexpected layout shifts.

---

# Final Transition

Next, you will begin working with your first Bootstrap webpage using the Bootstrap Starter Template. Understanding the concepts above ensures you’re not just using Bootstrap — you’re understanding its **architecture**, **responsive system**, and **design philosophy**, which will make every chapter that follows significantly easier.

[Back Home](#bootstrap)


<br>
<br>
<br>
<br>
<br>



<br>
<br>
<br>
<br>
<br>



<br>
<br>
<br>
<br>
<br>



<br>
<br>
<br>
<br>
<br>



<br>
<br>
<br>
<br>
<br>



<br>
<br>
<br>
<br>
<br>



<br>
<br>
<br>
<br>
<br>



<br>
<br>
<br>
<br>
<br>


<br>
<br>
<br>
<br>
<br>