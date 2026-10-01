# 🛍️ NovaStore — Responsive Store Landing Page Design

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap 5](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![Bootstrap Icons](https://img.shields.io/badge/Bootstrap_Icons-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![Responsive Design](https://img.shields.io/badge/Responsive-Design-success?style=for-the-badge)

> A modern, responsive, and visually engaging online store landing page developed with semantic HTML5, custom CSS3, Bootstrap 5, Bootstrap Icons, and responsive design principles.

---

## 📋 Table of Contents

- [Project Overview](#-project-overview)
- [Project Objective](#-project-objective)
- [Assignment Requirements](#-assignment-requirements)
- [Key Features](#-key-features)
- [Technologies Used](#-technologies-used)
- [Project Architecture](#-project-architecture)
- [Website Structure](#-website-structure)
- [Responsive Design](#-responsive-design)
- [UI/UX Design](#-uiux-design)
- [Accessibility](#-accessibility)
- [Code Quality](#-code-quality)
- [Screenshots](#-screenshots)
- [Installation](#-installation)
- [How to Run](#-how-to-run)
- [Testing](#-testing)
- [Known Limitations](#-known-limitations)
- [Future Improvements](#-future-improvements)
- [Learning Outcomes](#-learning-outcomes)
- [Author](#-author)
- [License](#-license)

---

# 📌 Project Overview

**NovaStore** is a responsive online store landing page created as a frontend web development project.

The objective of the project is to demonstrate the ability to design and implement a complete, modern, and responsive landing page using **HTML5 and CSS3**, while integrating **Bootstrap 5** as an additional frontend framework.

The interface is designed to provide a clean shopping experience across:

- Desktop computers
- Laptops
- Tablets
- Smartphones

The project combines a structured HTML5 architecture with custom CSS styling, Bootstrap's responsive grid system, Bootstrap Icons, responsive navigation, product cards, interactive hover effects, and multiple content sections.

---

# 🎯 Project Objective

The main objective of this project is to create a professional responsive store landing page that satisfies the following requirements:

- Build a complete HTML landing page.
- Create a structured header and navigation menu.
- Implement a visually appealing hero section.
- Create a product section containing at least four products.
- Add product images, names, descriptions, prices, and Shop Now actions.
- Create a responsive footer.
- Use CSS for custom visual styling.
- Implement responsive behavior using media queries.
- Ensure compatibility with desktop and mobile screen sizes.
- Integrate a CSS framework for additional responsiveness and styling.
- Maintain clean, organized, and commented source code.
- Document the design and development process professionally.

---

# ✅ Assignment Requirements

The project addresses the required assignment components as follows:

| Requirement | Implementation |
|---|---|
| HTML page structure | ✅ Implemented |
| Header | ✅ Implemented |
| Navigation menu | ✅ Implemented |
| Navigation links | ✅ Home, Products, About, Contact |
| Hero section | ✅ Implemented |
| Product section | ✅ Implemented |
| Minimum four product cards | ✅ Four products |
| Product images | ✅ Implemented |
| Product names | ✅ Implemented |
| Product descriptions | ✅ Implemented |
| Shop Now buttons | ✅ Implemented |
| Footer | ✅ Implemented |
| Custom CSS styling | ✅ Implemented |
| Responsive design | ✅ Implemented |
| CSS media queries | ✅ Implemented |
| Mobile-friendly layout | ✅ Implemented |
| CSS framework | ✅ Bootstrap 5 |
| Additional library components | ✅ Bootstrap Navbar, Grid and Utilities |
| Icons | ✅ Bootstrap Icons |
| Code comments | ✅ Included |
| Screenshots | ✅ Included |
| Design description | ✅ Documented |

---

# ✨ Key Features

## 1. Responsive Navigation

The navigation system is implemented using Bootstrap 5.

It includes:

- NovaStore brand/logo
- Home navigation link
- Products navigation link
- About navigation link
- Contact navigation link
- Shop Now call-to-action
- Responsive mobile navigation
- Bootstrap hamburger menu

The navigation uses:

```html
<nav class="navbar navbar-expand-lg navbar-dark fixed-top">
```

This allows the navigation to automatically adapt to different viewport sizes.

---

# 🏠 2. Hero Section

The hero section is the primary visual introduction to NovaStore.

It contains:

- New Collection badge
- Main marketing headline
- Supporting description
- Explore Products button
- Learn More button
- Product statistics
- Product showcase image
- Fast Delivery information card
- Secure Shopping information card

The section uses a two-column Bootstrap layout on larger screens and adapts to a single-column structure on smaller screens.

---

# 🚚 3. Service Features

The project contains a dedicated features section highlighting three major shopping benefits:

### Free Shipping

Provides information about delivery services.

### Secure Payment

Communicates the use of secure shopping and payment practices.

### 24/7 Support

Provides users with information about customer support availability.

Bootstrap Icons are used to visually represent each service.

---

# 🛍️ 4. Product Section

The main product section contains four professionally styled product cards.

### Product 1 — Premium Smartwatch

**Category:** Technology

The smartwatch product card includes:

- Product image
- New badge
- Wishlist button
- Product category
- Product name
- Product description
- Price
- Shop Now action

---

### Product 2 — Wireless Headphones

**Category:** Audio

The headphones card includes:

- Product image
- Sale badge
- Wishlist button
- Product information
- Product price
- Shop Now action

---

### Product 3 — Urban Sneakers

**Category:** Fashion

The sneakers card includes:

- Product image
- Popular badge
- Wishlist button
- Product information
- Product price
- Shop Now action

---

### Product 4 — Professional Camera

**Category:** Photography

The camera card includes:

- Product image
- Trending badge
- Wishlist button
- Product information
- Product price
- Shop Now action

---

# 🎨 5. Product Card Interactions

The product cards include several CSS-based interactive effects.

### Card Hover Effect

When the user moves the cursor over a product card, the card moves slightly upward.

```css
.product-card:hover {
    transform: translateY(-8px);
}
```

### Product Image Zoom

The product image smoothly enlarges when the card is hovered.

```css
.product-card:hover .product-image {
    transform: scale(1.08);
}
```

### Wishlist Button

The wishlist button changes appearance when hovered.

### Shop Now Interaction

The Shop Now link includes a subtle arrow movement to provide visual feedback.

These interactions improve the overall user experience without requiring JavaScript.

---

# ℹ️ 6. About Section

The About section introduces the NovaStore concept and explains the purpose of the platform.

It includes:

- Store description
- Supporting image
- Marketing content
- Contact call-to-action

The section uses Bootstrap's responsive grid combined with custom CSS.

---

# 📧 7. Newsletter Section

The project includes a newsletter subscription area.

Users can enter an email address through the form:

```html
<input
    type="email"
    id="email"
    placeholder="Enter your email address"
    required
>
```

The layout automatically changes on smaller screens to provide a mobile-friendly form.

> **Note:** The newsletter form is currently a frontend component only. No backend email-subscription service is connected.

---

# 🦶 8. Footer

The footer provides additional navigation and store information.

It contains:

### Brand Information

- NovaStore logo
- Store description

### Navigation

- Home
- Products
- About
- Contact

### Customer Service

- FAQ
- Shipping Information
- Returns & Refunds
- Privacy Policy

### Contact Information

- Email
- Telephone
- Location

### Social Media

- Facebook
- Instagram
- X/Twitter
- LinkedIn

The footer is fully responsive and reorganizes its columns on smaller devices.

---

# 🛠️ Technologies Used

## HTML5

HTML5 provides the semantic structure of the application.

The project uses semantic elements such as:

```html
<header>
<nav>
<main>
<section>
<article>
<footer>
```

This improves the organization, readability, accessibility, and maintainability of the page.

---

## CSS3

Custom CSS3 is used extensively to create the visual identity of NovaStore.

The stylesheet includes:

- CSS variables
- Flexbox
- Responsive layouts
- Media queries
- Gradients
- Shadows
- Transitions
- Hover effects
- Typography
- Spacing
- Borders
- Rounded corners
- Image transformations

The project defines reusable design variables inside `:root`.

For example:

```css
:root {
    --primary-color: #6366f1;
    --primary-dark: #4f46e5;
    --dark-color: #111827;
    --background-color: #f8fafc;
}
```

This makes the visual system easier to maintain and update.

---

## Bootstrap 5

Bootstrap 5 is integrated into the project as the responsive CSS framework.

The project uses Bootstrap for:

- Responsive navigation
- Grid system
- Containers
- Responsive columns
- Buttons
- Utility classes
- Responsive breakpoints
- Mobile navigation

Examples include:

```html
<div class="container">
```

and:

```html
<div class="row g-4">
```

and:

```html
<div class="col-sm-6 col-lg-3">
```

This allows the product layout to adapt automatically to different viewport sizes.

---

## Bootstrap Icons

Bootstrap Icons are used throughout the interface.

Examples include:

- Shopping bag
- Heart
- Truck
- Shield
- Headset
- Arrow
- Facebook
- Instagram
- LinkedIn
- Email
- Telephone
- Location

Example:

```html
<i class="bi bi-bag-heart-fill"></i>
```

---

## Google Fonts

The project uses the **Inter** font family from Google Fonts.

The font provides:

- Modern typography
- Good readability
- Multiple font weights
- Consistent visual hierarchy

---

# 📂 Project Architecture

The uploaded project follows a simple and maintainable frontend structure:

```text
Responsive-Store-Landing-Page-Design-main/
│
├── index.html
├── style.css
│
└── Screenshots/
    ├── About us.png
    ├── Contact us.png
    ├── Home page.png
    ├── Products .png
    ├── Using Mobile GalaxyA55.png
    ├── Using Mobile phone16.png
    └── Using iPad pro13.png
```

---

# 🧱 Website Structure

The page follows a clear hierarchical structure:

```text
NovaStore
│
├── Header
│   │
│   ├── Navigation
│   │
│   └── Hero Section
│
├── Features
│   ├── Free Shipping
│   ├── Secure Payment
│   └── 24/7 Support
│
├── Main Content
│   │
│   ├── Products
│   │   ├── Premium Smartwatch
│   │   ├── Wireless Headphones
│   │   ├── Urban Sneakers
│   │   └── Professional Camera
│   │
│   ├── About
│   │
│   └── Newsletter
│
└── Footer
    ├── Brand
    ├── Navigation
    ├── Customer Service
    ├── Contact
    └── Social Media
```

---

# 📱 Responsive Design

Responsive design is one of the main objectives of this project.

The implementation combines:

1. Bootstrap's responsive grid system.
2. Bootstrap's responsive navigation.
3. Custom CSS media queries.
4. Flexible layouts.
5. Responsive typography.
6. Mobile-specific component adjustments.

---

## Desktop Layout

On larger screens:

- The navigation is displayed horizontally.
- The hero section uses two columns.
- Product cards are displayed in a four-column grid.
- Features are displayed horizontally.
- Footer content is organized into multiple columns.

---

## Tablet Layout

On tablet-sized screens:

- Hero content adapts to the available width.
- Product cards automatically resize.
- Features reorganize as required.
- Newsletter content becomes more flexible.
- Navigation becomes more compact.

---

## Mobile Layout

On mobile devices:

- The navigation collapses into a hamburger menu.
- Hero content becomes vertically organized.
- Product cards adapt to the smaller viewport.
- CTA buttons become easier to use.
- Newsletter elements stack vertically.
- Footer content reorganizes into mobile-friendly sections.

---

# 📐 Custom Responsive Breakpoints

The project contains custom CSS media queries for different screen sizes.

### Tablet

```css
@media (max-width: 991.98px)
```

### Mobile

```css
@media (max-width: 767.98px)
```

### Small Mobile

```css
@media (max-width: 400px)
```

This combination with Bootstrap's responsive system allows the page to adapt to a wide range of devices.

---

# 🎨 UI/UX Design

The design follows modern e-commerce UI/UX principles.

## Visual Hierarchy

The interface uses:

- Large hero typography
- Clear section headings
- Product categories
- Strong CTA buttons
- Visual product cards
- Consistent spacing

This allows users to quickly identify important information.

---

## Color System

The primary color palette is based around indigo and dark navy tones.

```text
Primary:       #6366F1
Primary Dark:  #4F46E5
Dark:          #111827
Secondary:     #1F2937
Background:    #F8FAFC
White:         #FFFFFF
Border:        #E5E7EB
```

The color system creates a consistent visual identity throughout the page.

---

## Spacing

The design uses consistent spacing between:

- Sections
- Headings
- Paragraphs
- Product elements
- Buttons
- Cards

This improves readability and visual organization.

---

## Shadows and Cards

Subtle shadows are used to establish depth and visual hierarchy.

The project defines multiple reusable shadow levels:

```css
--shadow-small
--shadow-medium
--shadow-large
```

This avoids repeatedly defining similar shadow values throughout the stylesheet.

---

# ♿ Accessibility

Accessibility considerations were included in the implementation.

Examples include:

### Descriptive Image Alternatives

```html
<img
    src="..."
    alt="Premium Smartwatch"
>
```

### Accessible Buttons

Icon-only wishlist buttons contain descriptive ARIA labels:

```html
<button
    aria-label="Add smartwatch to wishlist"
>
```

### Form Accessibility

The newsletter form includes a label associated with the email input.

### Semantic Structure

The use of:

```html
<header>
<nav>
<main>
<section>
<article>
<footer>
```

provides a meaningful document structure.

---

# 🧹 Code Quality

The project follows several clean-code practices.

## Organized CSS

The stylesheet is divided into clearly labeled sections:

```text
1. Global Variables
2. Reset & Base Styles
3. Navigation
4. Hero Section
5. Hero Product Visual
6. Features
7. Section General Styles
8. Product Cards
9. About Section
10. Newsletter
11. Footer
12. Responsive Design
```

This makes the stylesheet easier to navigate and maintain.

---

## CSS Variables

Reusable values are stored in CSS custom properties.

Example:

```css
:root {
    --primary-color: #6366f1;
    --dark-color: #111827;
    --transition: all 0.3s ease;
}
```

This improves consistency and simplifies future modifications.

---

## Comments

Both HTML and CSS contain descriptive comments that identify major sections of the implementation.

This makes the code easier for another developer to understand.

---

# 📸 Screenshots

The project submission includes screenshots demonstrating the website on different sections and devices.

The `Screenshots` directory contains:

```text
Screenshots/
│
├── About us.png
├── Contact us.png
├── Home page.png
├── Products .png
├── Using Mobile GalaxyA55.png
├── Using Mobile phone16.png
└── Using iPad pro13.png
```

The screenshots demonstrate:

- Home page presentation
- Product section
- About section
- Contact/footer section
- Mobile Galaxy A55 viewport
- Mobile phone viewport
- iPad Pro viewport

The supplied screenshots have approximately **1920 × 1080** desktop capture dimensions, while the device screenshots demonstrate responsive behavior across mobile and tablet contexts.

---

# 🚀 Installation

This is a static frontend project, so no backend server or package manager is required.

## Step 1 — Extract the Project

Extract:

```text
Responsive-Store-Landing-Page-Design-main.zip
```

to your preferred working directory.

---

## Step 2 — Open the Project

Open the extracted folder using **Visual Studio Code**.

The main files are:

```text
index.html
style.css
```

---

## Step 3 — Run the Project

The recommended method is using the **Live Server** extension in Visual Studio Code.

### Using Live Server

1. Open `index.html`.
2. Right-click inside the file.
3. Select **Open with Live Server**.
4. The website will open automatically in your browser.

---

# 🌐 External Resources

The project loads several resources through external CDNs and hosted services.

### Bootstrap CSS

```text
https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css
```

### Bootstrap JavaScript

```text
https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js
```

### Bootstrap Icons

```text
https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css
```

### Google Fonts

The project uses the Inter font from Google Fonts.

### Product Images

Product imagery is loaded from hosted Unsplash image URLs.

> Because these resources are external, an internet connection is required for the complete visual presentation when running the project.

---

# 🧪 Testing

The website should be tested using different viewport sizes.

## Desktop Testing

Recommended viewport sizes:

```text
1920 × 1080
1440 × 900
1366 × 768
```

---

## Tablet Testing

Recommended viewport sizes:

```text
1024 × 768
768 × 1024
```

---

## Mobile Testing

Recommended viewport sizes:

```text
430 × 932
390 × 844
375 × 667
```

The project screenshots also demonstrate testing across:

- Galaxy A55
- iPhone/mobile viewport
- iPad Pro 13-inch

---

# 🔍 Browser Compatibility

The project is designed for modern browsers, including:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

The implementation relies on modern HTML5, CSS3, Bootstrap 5, and browser features supported by current versions of these browsers.

---

# ⚠️ Known Limitations

This project is currently a **frontend landing page** rather than a complete e-commerce application.

The following functionality is currently visual/frontend only:

- Shopping cart
- Authentication
- Payment processing
- Product database
- User accounts
- Order management
- Newsletter backend
- Product search
- Product filtering
- Wishlist persistence

For example, the **Shop Now** buttons currently navigate to the Contact section rather than processing a real purchase.

Similarly, the newsletter form provides the frontend interface but is not connected to a backend email service.

---

# 🔮 Future Improvements

The project can be extended into a complete e-commerce application.

Potential improvements include:

### Frontend

- Product details pages
- Product filtering
- Product search
- Shopping cart
- Persistent wishlist
- Product reviews
- Product ratings
- Dark mode
- Loading states
- Toast notifications
- Interactive checkout interface

### Backend

A backend could be implemented using technologies such as:

```text
Node.js
Express.js
MongoDB
Mongoose
```

Potential backend functionality:

- User authentication
- Product management
- Orders
- Inventory
- Customer accounts
- Wishlist storage
- Product reviews

### Advanced Architecture

The project could also be migrated to:

```text
React
TypeScript
Vite
Next.js
```

for a more scalable component-based architecture.

---

# 📚 Learning Outcomes

This project demonstrates practical knowledge of:

- HTML5
- Semantic HTML
- CSS3
- CSS variables
- Flexbox
- Responsive web design
- Media queries
- Bootstrap 5
- Bootstrap Grid
- Bootstrap Navbar
- Bootstrap utility classes
- Bootstrap Icons
- Google Fonts
- UI/UX design principles
- Accessibility fundamentals
- Hover effects
- CSS transitions
- CSS transforms
- Responsive typography
- Frontend project organization
- Clean and maintainable code

---


# 👨‍💻 Author

## Yassine Kaltoum

**Network & Software Engineer**

Areas of interest:

- Software Engineering
- Web Development
- Network Engineering
- Cybersecurity
- Cloud Computing
- Responsive Web Design

---

# 📄 License

This project was developed for **educational and portfolio purposes**.

The project demonstrates frontend development concepts including responsive design, semantic HTML5, custom CSS3, Bootstrap integration, UI/UX principles, and accessibility practices.

---

# ⭐ Conclusion

**NovaStore — Responsive Store Landing Page Design** demonstrates the implementation of a complete modern storefront interface using **HTML5, CSS3, Bootstrap 5, and Bootstrap Icons**.

The project combines a semantic document structure, responsive Bootstrap layouts, custom CSS styling, interactive visual effects, product presentation, accessibility considerations, and responsive testing across desktop, tablet, and mobile screen sizes.

The architecture remains intentionally lightweight and frontend-focused, making the project easy to understand, maintain, extend, and eventually integrate with a backend e-commerce system.
