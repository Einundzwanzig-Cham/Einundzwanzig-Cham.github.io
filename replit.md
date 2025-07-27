# Bitcoin Meetup Website - Einundzwanzig Cham

## Overview

This is a static website for the Einundzwanzig Cham Bitcoin meetup group in Bavaria, Germany. The website serves as an informational landing page to promote Bitcoin meetups held on the 4th weekend of each month. It's built as a simple, responsive single-page application using vanilla HTML, CSS, and JavaScript without any frameworks or backend dependencies.

## User Preferences

Preferred communication style: Simple, everyday language.
Branding: Use official Einundzwanzig color scheme and typography from einundzwanzig.space/media/

## System Architecture

### Frontend Architecture
- **Single Page Application (SPA)**: Built with vanilla HTML, CSS, and JavaScript
- **Responsive Design**: Mobile-first approach using CSS Grid and Flexbox
- **No Build Process**: Direct HTML/CSS/JS files without bundlers or transpilation
- **Static Hosting Ready**: Can be deployed to any static hosting service

### Styling Architecture
- **Official Einundzwanzig Branding**: Uses authentic color scheme (#F7931A, #00B4CF, #A915FF, #151515) and Inconsolata typography from einundzwanzig.space/media/
- **CSS Custom Properties**: Uses CSS variables for consistent theming and color management
- **Component-Based CSS**: Organized CSS with clear component separation
- **Mobile-First Responsive**: Breakpoints designed for mobile-first experience
- **Modern CSS Features**: Utilizes CSS Grid, Flexbox, and modern selectors

## Key Components

### Navigation System
- **Fixed Header Navigation**: Sticky navigation bar with logo and menu items
- **Mobile Hamburger Menu**: Collapsible navigation for mobile devices
- **Smooth Scrolling**: JavaScript-powered smooth scrolling between sections
- **Active State Management**: Visual feedback for navigation interactions

### Content Sections
Based on the navigation structure, the website includes:
- About section (`#about`)
- Upcoming meetups (`#meetups`)
- Contact information (`#contact`)
- Bitcoin information (`#bitcoin`)
- Resources (`#resources`)

### Interactive Features
- **Mobile Menu Toggle**: JavaScript-controlled hamburger menu
- **Click Outside Handling**: Menu closes when clicking outside the navigation
- **Smooth Anchor Navigation**: Enhanced scrolling experience with offset calculations

## Data Flow

### Static Content Flow
1. HTML provides semantic structure and content
2. CSS handles all visual presentation and responsive behavior
3. JavaScript adds interactive behaviors (navigation, scrolling)
4. No data persistence or dynamic content loading

### User Interaction Flow
1. User clicks navigation links
2. JavaScript intercepts click events
3. Smooth scrolling animation to target section
4. Mobile menu closes automatically after selection

## External Dependencies

### Content Delivery Networks (CDNs)
- **Google Fonts**: Inter font family for typography
- **Font Awesome 6.5.1**: Icon library for UI elements
- **No JavaScript Frameworks**: Pure vanilla JavaScript implementation

### Asset Dependencies
- **Logo SVG**: Custom logo file (`logo.svg`)
- **Favicon**: SVG-based favicon for modern browsers

## Deployment Strategy

### Static Hosting Compatibility
- **Zero Configuration**: Ready for deployment to static hosts
- **No Server Requirements**: Pure client-side application
- **Compatible Platforms**: 
  - GitHub Pages
  - Netlify
  - Vercel
  - AWS S3 + CloudFront
  - Any web server serving static files

### Performance Considerations
- **Minimal Dependencies**: Only essential external resources loaded
- **Optimized Loading**: Preconnect hints for external font resources
- **Lightweight Bundle**: No build process means direct file serving

### SEO Optimization
- **Meta Tags**: Comprehensive meta tags for search engines
- **Open Graph**: Social media sharing optimization
- **Semantic HTML**: Proper heading structure and semantic elements
- **German Language**: Correctly specified language attribute

The architecture prioritizes simplicity, performance, and maintainability while providing a professional presentation for the Bitcoin meetup community in Cham, Bavaria.