

## 📌 Project Overview
**GoRide** is a high-fidelity frontend portfolio project modeling a high-growth urban ride-hailing startup. It enables riders to explore city transit options (Bike Taxi, Auto Rickshaw, City Sedan, SUV XL), examine upfront transparent fares, test interactive route booking workflows, review safety measures, and browse company information.

---

## 🚀 Key Features

- **Pure HTML5 & CSS3**: 100% framework-free. No Bootstrap, Tailwind, React, or JavaScript.
- **5 Multi-Page Navigation**:
  - `index.html`: High-converting homepage with quick booking form, fleet showcase, how-it-works progression, trust statistics, safety feature breakdown, and rider testimonials.
  - `booking.html`: Full ride reservation interface with pickup/drop locations, date/time pickers, passenger selection, vehicle cards, fare breakdown, and sticky summary panel.
  - `rides.html`: Complete vehicle catalog with technical specs, seating capacity, luggage allowance, and sample fare structures.
  - `about.html`: Startup narrative, core values, mission, vision, and sustainability commitment.
  - `contact.html`: Accessible inquiry form, 24/7 support channels, and semantic HTML5 `<details>` FAQ accordion.
- **Pure CSS Responsive Mobile Menu**: Checkbox hack navigation drawer that animates cleanly without a single line of JavaScript.
- **Modern Responsive Design**: Fluid typography with `clamp()`, flexible layouts with **CSS Flexbox** and **CSS Grid**, and media queries targeting mobile (320px–480px), tablet (481px–768px), laptop (769px–1024px), and desktop (1025px+).
- **Accessible & Semantic**: ARIA attributes, semantic landmarks (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`), visible focus states, and high-contrast color ratios.
- **High-Performance Vector Assets**: Handcrafted inline and external SVGs for crisp rendering on high-DPI (Retina/4K) displays.

---

## 📂 Project Directory Structure

```text
goride/
├── index.html              # Homepage with Hero, Quick Booking, Fleet & Testimonials
├── booking.html            # Dedicated Ride Reservation & Fare Summary Page
├── rides.html              # Vehicle Fleet Categories & Technical Specs
├── about.html              # Company Mission, Vision & Safety Charter
├── contact.html            # Support Inquiry Form & Pure CSS FAQ Accordion
├── README.md               # Complete Project & Interview Documentation
├── css/
│   └── style.css           # Master stylesheet (CSS Variables, Flexbox, Grid, Queries)
└── assets/
    └── images/
        ├── logo.svg        # GoRide Brand Emblem & Wordmark
        ├── bike.svg        # Vector illustration of Bike Taxi
        ├── auto.svg        # Vector illustration of Auto Rickshaw
        ├── sedan.svg       # Vector illustration of City Sedan
        ├── suv.svg         # Vector illustration of SUV XL
        └── safety-shield.svg # Vector graphic for Safety Shield
```

---

## 🛠️ Technologies & Concepts Demonstrated

| Concept | Implementation in GoRide |
| :--- | :--- |
| **CSS Variables** | Unified design tokens for brand emerald (`#05D374`), dark obsidian (`#0B0F19`), surface layers, spacing tokens, and elevation shadows. |
| **CSS Grid** | Multi-column layouts: Hero section (1.15fr / 0.85fr), auto-fitting vehicle cards (`repeat(auto-fit, minmax(260px, 1fr))`), 4-step timeline, and footer. |
| **CSS Flexbox** | Navigation bar alignment, button icon spacing, stats strip alignment, driver profile cards, and form input groups. |
| **Pure CSS States** | Checkbox hack for mobile drawer (`#nav-toggle:checked ~ .nav-menu`), radio pill selectors for vehicle category choice, and `<details>` accordion toggle. |
| **Transitions & Hover** | Micro-interactions with `cubic-bezier(0.4, 0, 0.2, 1)`, card lifts (`transform: translateY(-8px)`), button glow, and link underlines. |
| **Responsive Media Queries** | 4-tier responsive breakpoints preventing horizontal overflow across 320px to 4K screens. |

---

## 💻 Instructions to Run Locally

1. **Direct Browser Execution**:
   - Double-click `index.html` to open it in any modern browser (Chrome, Edge, Firefox, Safari).
2. **VS Code Live Server**:
   - Open the `goride` folder in VS Code.
   - Right-click `index.html` and click **"Open with Live Server"**.
3. **Local Python Server** (Optional):
   ```bash
   cd goride
   python -m http.server 8000
   ```
   Open `http://localhost:8000` in your web browser.

---

## 🧪 Responsive Testing Checklist

- [x] **Mobile (320px–480px)**:
  - Hamburger menu opens full-screen drawer smoothly without layout shift.
  - Quick booking inputs and buttons span 100% width with touch-friendly targets (min 44px height).
  - No horizontal scrolling (`overflow-x: hidden`).
- [x] **Tablet (481px–768px)**:
  - 2-column card wrapping for fleet and statistics.
  - Sticky summary on booking page stacks cleanly below the form.
- [x] **Laptop / Desktop (1024px+)**:
  - Full desktop header with horizontal navigation and action CTA.
  - Two-column hero with live driver route simulation card.
  - 4-column feature and how-it-works grids.


---

## ⚖️ Project Limitations & Prototype Notice
GoRide is a frontend portfolio project designed to showcase frontend architecture, typography, and responsive styling. Backend integration, real-time geolocation tracking, live payment processing, and dynamic database queries are static demonstrations.
