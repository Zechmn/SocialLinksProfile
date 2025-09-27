# Social Links Profile

## Overview

This is a static social links profile webpage built as part of a Frontend Mentor challenge. The project displays a personal profile card for Jessica Randall, featuring her avatar, bio information, and social media links in a clean, modern design. The application is a simple HTML/CSS static site focused on responsive design and hover interactions.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Technology Stack**: Pure HTML5 and CSS3 with no JavaScript frameworks
- **Design Pattern**: Single-page static site with component-based CSS styling
- **Layout System**: Flexbox-based responsive design using mobile-first approach
- **Typography**: Google Fonts integration (Inter font family) with multiple weights (400, 600, 700)
- **Responsive Design**: Mobile-responsive layout supporting screens from 320px to desktop widths

### Styling Architecture
- **CSS Reset**: Universal box-sizing and margin/padding reset for consistent cross-browser rendering
- **Color System**: HSL-based color palette with defined primary colors (green accent, white text, multiple grey shades for backgrounds)
- **Component Structure**: Modular CSS classes for profile card, social links, and typography elements
- **Interactive Elements**: Hover and focus states for social media links

### File Structure
- **Entry Point**: `index.html` - Main webpage with semantic HTML structure
- **Styling**: `style.css` - Complete styling definitions and responsive design rules
- **Assets**: Avatar image and favicon stored in assets directory
- **Documentation**: Frontend Mentor challenge documentation and style guide

### Design Decisions
- **Accessibility**: Semantic HTML elements and proper alt text for images
- **Performance**: Minimal external dependencies (only Google Fonts)
- **Browser Compatibility**: Standard HTML5/CSS3 features for broad browser support
- **Maintainability**: Clean separation of concerns with external CSS file

## External Dependencies

### Third-Party Services
- **Google Fonts**: Inter font family loaded via CDN for typography
- **Font Preconnect**: DNS prefetching for Google Fonts domains to improve loading performance

### Assets
- **Images**: Local avatar image (JPEG format) and favicon (PNG format)
- **No Backend**: Completely static site with no server-side dependencies
- **No Database**: No data persistence or dynamic content requirements
- **No APIs**: All content is hardcoded in HTML with placeholder social media links
