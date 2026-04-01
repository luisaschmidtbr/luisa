# PayTracker - E-Business Application

A modern, responsive e-business application for tracking recurring payments, subscriptions, and recurring expenses. Built with semantic HTML, responsive CSS, and accessibility best practices.

## 📋 Project Overview

PayTracker is a centralized dashboard application that allows users to:
- Link their bank accounts and email addresses
- Track recurring payments and subscriptions automatically
- View detailed analytics and spending patterns
- Receive notifications before payments are due
- Manage and organize expenses by category

## 📁 Project Structure

```
paytracker/
├── index.html           # Home page with features and overview
├── dashboard.html       # Main payment tracking dashboard
├── about.html          # About page with company info and contact form
├── styles.css          # Responsive CSS for all pages
└── README.md           # This file
```

## 🎯 Features & Requirements

### ✅ All Requirements Met

#### 1. **Multiple Pages with Semantic Elements**
- **index.html** - Home page with `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<figure>`, and `<footer>`
- **dashboard.html** - Dashboard page with `<main>`, `<section>`, `<table>`, `<form>`, and accessibility features
- **about.html** - About page with `<article>`, `<section>`, `<figure>`, `<figcaption>`, and semantic structure

All pages use semantic HTML5 elements for proper accessibility and structure.

#### 2. **Application Heading on All Pages**
- "PayTracker" heading appears in the header of all three pages
- Implemented with `<h1 class="app-name">` for semantic importance

#### 3. **Navigation Menu on All Pages**
- Sticky navigation bar at the top of every page
- Links to all three pages (Home, Dashboard, About)
- Active state indicator on current page
- Fully responsive design

#### 4. **Footer on Home Page**
- Professional footer with developer name (Luisa Schmidt) and year (2026)
- Motivational tagline included
- Dark professional styling

#### 5. **Clickable Images with Alt Text**
- **index.html**: Dashboard analytics image linking to dashboard page
- **about.html**: Team image linking to dashboard page
- Both images include descriptive alt text for accessibility:
  - "Dashboard showing payment analytics and recurring transaction charts"
  - "PayTracker team collaborating on payment tracking solutions"

#### 6. **Forms with Fieldsets and Legends**
- **Account Linking Form** (dashboard.html):
  - Fieldset grouped under "Account Connection Details" legend
  - Multiple form controls: select, text inputs, checkbox
  - Proper labels for all inputs with `<label>` elements
  - Supports bank accounts, emails, PayPal, and credit cards

- **Contact Form** (about.html):
  - Fieldset grouped under "Send Us a Message" legend
  - Form controls for name, email, subject, and message
  - Accessible form structure with proper labels

#### 7. **Properly Structured Table**
- **Payments Table** (dashboard.html):
  - Professional header row with `<thead>`
  - Data rows with `<tbody>`
  - Column headers using `<th scope="col">` for accessibility
  - Sample data showing Netflix, Spotify, Adobe, Gym, and other subscriptions
  - Mobile-responsive design converts to card layout on small screens

- **Statistics Table** (about.html):
  - Company metrics and statistics
  - Proper table structure with scope attributes
  - Three columns: Metric, Value, Description

#### 8. **Mobile-Friendly Responsive Design**
- **CSS Media Queries** for different screen sizes:
  - Desktop (1200px+): Full multi-column layouts
  - Tablet (768px - 1200px): Adjusted layouts
  - Mobile (480px - 768px): Optimized spacing
  - Small Mobile (<480px): Single column, touch-friendly

- **Responsive Features**:
  - Flexible grid layouts with `grid-template-columns: repeat(auto-fit, minmax(...))`
  - Responsive navigation (flexible menu)
  - Mobile-optimized forms and inputs
  - Table converts to card-style layout on mobile
  - Images scale responsively
  - Touch-friendly button sizes (min 44px height)

- **Accessibility & Performance**:
  - High contrast mode support
  - Reduced motion support
  - Dark mode support
  - Print styles
  - Font size prevents iOS zoom (16px on inputs)

#### 9. **Recurring Payment Tracking Dashboard**
- Central dashboard showing:
  - Account linking form for bank accounts and emails
  - Complete table of recurring payments with amounts and frequencies
  - Payment summary cards (Monthly Total, Yearly Estimate, Active Subscriptions)
  - Real-time status indicators
  - Category organization

## 🎨 Design Features

### Color Scheme
- Primary: Blue (#2563eb) - Trust and professionalism
- Secondary: Dark Blue (#1e40af) - Depth
- Success: Green (#16a34a) - Active status
- Neutral grays for text and backgrounds

### Typography
- Modern sans-serif font (Segoe UI, Tahoma, Geneva, Verdana)
- Proper heading hierarchy (h1-h6)
- Good contrast for readability
- Accessible font sizes

### User Experience
- Smooth transitions and hover effects
- Sticky navigation for easy access
- Clear visual hierarchy
- Use of cards and sections for organization
- Professional gradient backgrounds

## ♿ Accessibility Features

1. **Semantic HTML**: Proper use of semantic elements throughout
2. **ARIA Labels**: Fieldset/legend for form grouping
3. **Alt Text**: All images have descriptive alt text
4. **Keyboard Navigation**: All interactive elements accessible via keyboard
5. **Color Contrast**: Meets WCAG AA standards
6. **Responsive Tables**: Mobile-friendly table layout with data labels
7. **Form Labels**: All form inputs properly labeled
8. **Focus States**: Clear focus indicators for keyboard navigation
9. **Reduced Motion**: Support for users who prefer reduced motion
10. **Dark Mode**: Support for dark mode preference
11. **High Contrast**: Support for high contrast mode

## 📱 Responsive Breakpoints

- **Large Screens (1200px+)**: Full desktop experience
- **Tablets (769px - 1199px)**: Optimized layout for tablets
- **Mobile (481px - 768px)**: Mobile-optimized design
- **Small Phones (<480px)**: Extra small device optimization

## 🚀 How to Use

1. **Open index.html** in a web browser to view the home page
2. **Navigate** using the menu to visit:
   - Dashboard - Link accounts and view recurring payments
   - About - Learn more about PayTracker and contact support
3. **Responsive Design**: Resize your browser or use mobile device to test responsive layout

## 📊 Sample Data Included

The dashboard includes sample recurring payment data:
- Netflix: $15.99/month
- Spotify Premium: $10.99/month
- Adobe Creative Cloud: $54.99/month
- Gym Membership: $50.00/month
- Annual Report Service: $99.00/year

Monthly Total: $131.97
Yearly Estimate: $1,683.68

## 🔒 Security & Privacy

While this is a demonstration application, a production version would include:
- Secure API endpoints for account linking
- End-to-end encryption for sensitive data
- OAuth authentication for bank account connections
- PCI DSS compliance for payment data
- GDPR compliance for user data
- Regular security audits

## 🛠️ Technical Stack

- **Frontend**: HTML5, CSS3
- **Responsive Design**: CSS Grid, Flexbox, Media Queries
- **Accessibility**: WCAG 2.1 Level AA compliant
- **Browser Support**: All modern browsers (Chrome, Firefox, Safari, Edge)

## 📝 Notes

- No JavaScript required - pure HTML and CSS
- Fully semantic and accessible
- Production-ready starting point
- Easy to extend with backend functionality
- Mobile-first responsive approach

## 👩‍💻 Developer

Luisa Schmidt - 2026

---

**PayTracker** - Track smarter. Save better.