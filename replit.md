# Atom Conferences

## Overview

Atom Conferences is a static website for a professional conference organization that connects professionals, lecturers, and students across all disciplines. The site serves as an informational platform showcasing upcoming meetings, policies, and contact information for conference attendees and organizers.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
The application follows a traditional multi-page static website architecture built with vanilla HTML, CSS, and JavaScript. Each page represents a distinct section of the conference website:

- **Static HTML Pages**: Seven main pages (index, meetings, contact, FAQ, privacy policy, terms and conditions, cancellation policy) with consistent navigation structure
- **Responsive Design**: Mobile-first approach with hamburger menu navigation for smaller screens
- **Component-Based CSS**: Modular styling approach using CSS classes for reusable components
- **Progressive Enhancement**: JavaScript functionality layered on top of functional HTML structure

### Frontend Components
- **Navigation System**: Responsive navbar with mobile hamburger menu toggle
- **Interactive Elements**: FAQ accordion functionality, contact forms, newsletter signup
- **Content Filtering**: Meeting and category filters for content organization
- **Smooth Scrolling**: Enhanced user experience with smooth page transitions

### Styling Framework
- **CSS Architecture**: Custom CSS with Inter font family from Google Fonts
- **Responsive Breakpoints**: Mobile-first design with progressive enhancement
- **Color Scheme**: Clean, professional design with consistent typography hierarchy
- **Layout System**: Flexbox and CSS Grid for responsive layouts

### JavaScript Functionality
- **Modular Structure**: Functions organized by component (mobile menu, FAQ, forms, filters)
- **Event Handling**: DOM content loaded initialization with scroll and click event management
- **Form Management**: Contact form and newsletter subscription handling
- **User Interface**: Interactive elements like accordions and navigation toggles

## External Dependencies

### Frontend Libraries
- **Google Fonts**: Inter font family for consistent typography across the site
- **No Framework Dependencies**: Pure vanilla JavaScript and CSS implementation

### Browser APIs
- **DOM Manipulation**: Standard JavaScript DOM APIs for interactive functionality
- **Event Listeners**: Browser event handling for user interactions
- **Smooth Scrolling**: CSS and JavaScript scroll behavior implementation

### Development Tools
- **Static Hosting Ready**: No build process required, can be deployed to any static hosting service
- **SEO Optimized**: Meta descriptions and semantic HTML structure for search engine optimization