# Velvet-Roast
A modern, responsive luxury café &amp; specialty coffee shop website crafted with pure HTML5 and CSS3—featuring zero-JS category filtering and a live cart drawer.
# ☕ Velvet Roast Café — Artisanal Coffee & Bakery Website

> **"Brewed with Love, Served with Passion."**  
> A modern, responsive, high-end café website crafted with **pure semantic HTML5 and modern CSS3**—featuring zero JavaScript dependencies, interactive pure-CSS category filtering, a functional CSS-only shopping cart drawer with quantity controls, smooth scroll animations, and an editorial coffee-house aesthetic.

---

## 📖 Table of Contents

1. [Project Overview](#-project-overview)
2. [Key Features](#-key-features)
3. [Pure-CSS Engineering Highlights](#-pure-css-engineering-highlights)
4. [Design System & Color Palette](#-design-system--color-palette)
5. [Website Sections Breakdown](#-website-sections-breakdown)
6. [Project Structure](#-project-structure)
7. [Getting Started](#-getting-started)
8. [Customization Guide](#-customization-guide)
9. [Responsive Breakpoints](#-responsive-breakpoints)
10. [Browser Support](#-browser-support)
11. [License](#-license)

---

## 🌟 Project Overview

**Velvet Roast Café** is a single-page storefront designed for specialty coffee shops, bakeries, and boutique roasteries. Built entirely without JavaScript frameworks or external CSS libraries, the project demonstrates how modern CSS state selectors (`:checked`, `:target`, `:has()`, CSS custom properties, and CSS Grid/Flexbox) can power rich interactive e-commerce and navigation experiences with instant load times and zero runtime overhead.

---

## ✨ Key Features

- **100% Pure HTML5 & CSS3 (Zero JavaScript):** Lightweight, fast-loading single-file architecture with zero external script dependencies.
- **Interactive Menu Category Filtering:** Seamless pure-CSS tab switching across **All Items**, **Hot Coffee**, **Cold Coffee**, **Tea & Refreshments**, **Desserts**, and **Snacks & Bakery**.
- **Functional Pure-CSS Shopping Cart Drawer:**
  - Live cart item badge counter in the sticky navigation bar.
  - Slide-over cart drawer with add/remove item toggles and quantity steppers (`1` to `5`).
  - Order summary preview and interactive checkout confirmation state.
- **Sticky Glassmorphism Navigation Bar:** Smooth anchor scrolling, active section indicators, highlighted **Order Now** CTA, and a pure-CSS mobile hamburger drawer.
- **Editorial Hero & Story Sections:** Full-bleed hero showcase with staggered CSS entrance animations and an "About Our Café" brand story highlighting single-origin beans and handcrafted pastries.
- **Customer Favorites & Testimonials:** Highlighted signature product cards (*Signature Cappuccino*, *Caramel Macchiato*, *Chocolate Lava Cake*, *Strawberry Cheesecake*) and 5-star customer review cards.
- **Opening Hours & Contact Hub:** Dedicated schedule card with live status badge, embedded location map, interactive HTML5-validated contact form, and newsletter subscription.
- **SEO & Accessibility Ready:** Semantic landmarks (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`), ARIA labels, focus-visible outlines, and optimized imagery.

---

## ⚙️ Pure-CSS Engineering Highlights

| Interactive Feature | Pure-CSS Mechanism Used |
| :--- | :--- |
| **Menu Category Filtering** | Hidden `<input type="radio">` controls paired with general sibling combinators (`~`) to filter `.menu-card` elements smoothly. |
| **Slide-Over Shopping Cart** | Hidden `<input type="checkbox" id="cart-toggle">` controlling drawer transform transitions and backdrop overlay visibility. |
| **Live Cart Item Counter** | CSS `counter-reset` and `counter-increment` dynamically counting checked item checkboxes across the menu grid. |
| **Quantity Controls** | Nested radio/checkbox states inside cart line items allowing users to adjust item quantities (`1–5`) without JS. |
| **Mobile Navigation Drawer** | Checkbox-driven full-height mobile menu with animated hamburger-to-close icon morphing. |
| **Back-to-Top & Smooth Scroll** | Native `scroll-behavior: smooth` paired with anchor links (`#top`). |

---

## 🎨 Design System & Color Palette

The visual identity blends warm cream backgrounds with rich espresso browns and brushed gold accents:

| Token | Hex Code | Role |
| :--- | :--- | :--- |
| `--bg-cream` | `#FAF6F0` | Primary page background |
| `--bg-beige` | `#F1E8DC` | Secondary alternating section background |
| `--surface-card` | `#FFFFFF` | Product cards, review cards, and form containers |
| `--coffee-brown` | `#4A2C2A` | Primary brand headings, icons, and borders |
| `--dark-chocolate` | `#231412` | High-contrast body text, hero overlay, and footer |
| `--accent-gold` | `#C8963E` | Primary CTAs, star ratings, badges, and hover accents |
| `--accent-gold-dark` | `#A97928` | Button hover states and active tags |

### Typography
- **Display & Headings:** `'Playfair Display', Georgia, serif` — Editorial elegance with classic high-contrast serifs.
- **Body & UI Controls:** `'Plus Jakarta Sans', -apple-system, sans-serif` — Clean, legible geometric sans-serif for menu descriptions, prices, and forms.

---

## 🗺️ Website Sections Breakdown

1. **Sticky Navigation Bar:** Brand emblem, 6 section links (`Home`, `About`, `Menu`, `Specials`, `Reviews`, `Contact`), live Cart button with badge, and highlighted `Order Now` button.
2. **Hero Section (`#home`):** Full-viewport cozy café background, *"Brewed with Love, Served with Passion."* headline, subtitle, and dual CTAs (`Explore Menu` & `Visit Us`).
3. **About Our Café (`#about`):** *"A Little Story About Our Café"* paired with café interior photography and three quality pillars (*Ethically Sourced Beans*, *Artisanal Roasts*, *Baked Fresh Daily*).
4. **Interactive Menu (`#menu`):** Filterable 15-item menu across 5 categories with high-res food photography, descriptions, pricing, and instant `Add to Cart` toggles.
5. **Customer Favorites (`#specials`):** Featured 4-card showcase highlighting *Signature Cappuccino*, *Caramel Macchiato*, *Chocolate Lava Cake*, and *Strawberry Cheesecake*.
6. **Customer Reviews (`#reviews`):** *"What Our Customers Say"* featuring verified customer avatars, 5-star ratings, and authentic café feedback.
7. **Opening Hours (`#hours`):** Clear weekday (`Mon–Fri: 8:00 AM – 10:00 PM`) and weekend (`Sat–Sun: 9:00 AM – 11:00 PM`) schedule with an *"Open Now • Fresh Brews Ready"* status indicator.
8. **Location & Contact (`#contact`):** Address details, phone/email links, social profiles, embedded Google Map, and a validated inquiry form (`Name`, `Email`, `Subject`, `Message`).
9. **Footer:** Brand summary, quick links, opening hours recap, newsletter signup form, social icons, and copyright notice.

---

## 📁 Project Structure

```text
velvet-roast-cafe/
├── index.html          # Complete single-file HTML5 + embedded CSS3 application
└── README.md           # Project documentation☕ Velvet Roast Café — Artisanal Coffee & Bakery Website"Brewed with Love, Served with Passion."A modern, responsive, high-end café and specialty roastery website built 100% with semantic HTML5 and modern CSS3—requiring zero JavaScript for interactive menu filtering, live shopping cart counting, and slide-over drawer navigation.✨ Key Features🎨 Aesthetic & Visual DesignWarm Specialty-Coffee Palette: Crafted with warm cream (#FAF7F2), soft beige (#F5EFE6), roasted coffee brown (#6F4E37), dark chocolate (#2C1E16), and subtle golden accents (#C89D54).Editorial Typography: Pairs Playfair Display for refined serif headings with Plus Jakarta Sans for clean, legible body copy.Smooth Motion & Micro-Interactions: Includes staggered hero entrance animations, card elevation hover states, smooth scrolling, and a pulsing live "Open Today" status indicator.⚡ Pure-CSS Interactivity (Zero JavaScript!)Interactive Menu Category Filtering: Switch seamlessly between All Items, Hot Coffee, Cold Coffee, Tea & Refreshments, Desserts, and Snacks & Bakery using pure CSS :checked sibling selectors.Live Pure-CSS Shopping Cart & Drawer:Add or remove any of the 15 menu items directly from the menu or the Customer Favorites showcase.Real-time item counter badge in the sticky navigation bar powered by CSS counter-reset and counter-increment.Slide-over order drawer featuring quantity selectors, item removal toggles, and instant pickup order confirmation.Responsive Mobile Navigation: Collapsible mobile menu drawer built with accessible label/checkbox state toggles.📄 Complete Sections IncludedSticky Glassmorphic Navbar — Brand identity, smooth anchor links, mobile menu toggle, and highlighted Order Now cart trigger.Hero Welcome Section — Full-bleed café photography, animated headline, dual CTAs (Explore Menu & Visit Us), and roastery highlights.About Our Café — Brand heritage story, café interior showcase, and three craftsmanship pillars (Fresh Ingredients, Premium Beans, Handcrafted Recipes).Artisanal Menu — 15 curated items across 5 filterable categories with photography, descriptions, pricing, and interactive Add to Cart buttons.Our Customer Favorites — Dark-chocolate luxury showcase highlighting the Signature Cappuccino, Caramel Macchiato, Chocolate Lava Cake, and Strawberry Cheesecake.Customer Reviews — Five-star guest testimonials with avatars and editorial styling.Opening Hours — Weekday and weekend schedules paired with an animated live open-status badge.Location & Contact — Address, phone, email, social links, embedded interactive map, and an HTML5-validated contact form with confirmation feedback.Footer & Coffee Club Newsletter — Quick links, café details, newsletter sign-up confirmation, and a smooth Back to Top button.🛠️ Tech StackHTML5: Semantic structure (<header>, <nav>, <main>, <section>, <article>, <aside>, <footer>), ARIA accessibility labels, and native form validation.CSS3: Custom properties (CSS Variables), CSS Grid & Flexbox, :checked and :target pseudo-class state machines, CSS Counters, @keyframes animations, and responsive media queries.Fonts & Icons: Google Fonts (Playfair Display & Plus Jakarta Sans) and crisp inline SVGs.📁 Project Structurevelvet-roast-cafe/
├── index.html      # Complete single-file application (HTML5 + embedded CSS3)
└── README.md       # Project documentation
🚀 Getting StartedBecause this project is built purely with HTML5 and CSS3 with zero build steps or external dependencies:Clone the repository:git clone https://github.com/your-username/velvet-roast-cafe.git
Navigate to the project folder:cd velvet-roast-cafe
Launch in your browser:
Double-click index.html or open it with any local development server (such as VS Code Live Server).📱 Responsive BreakpointsDevice TierViewport WidthLayout BehaviorDesktop> 1080px4-column favorites grid, 3-column menu & reviews, full horizontal navbarTablet641px – 920px2-column grids, stacked About/Hours/Contact sections, collapsible mobile navMobile≤ 640pxSingle-column mobile-first cards, full-width drawer & touch-friendly buttons🔧 CustomizationColors & Fonts: Update the :root CSS variables at the top of index.html to rebrand the entire palette or typography in seconds.Contact & Location: Replace the placeholder address, phone number, email, and map coordinates in the #contact and <footer> sections with your café's real details.📄 LicenseThis project is open-source and available under the MIT License.
