# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a responsive personal portfolio website for Yevhenii Rodin, Software Architect and Tech Lead. The site is built as a static website optimized for GitHub Pages deployment, showcasing professional experience, skills, and accomplishments.

## Architecture

### Tech Stack
- **Frontend**: HTML5, CSS3, Vanilla JavaScript (ES6+)
- **Styling**: Modern CSS with Flexbox/Grid, custom properties
- **Icons**: Font Awesome 6.4.0
- **Fonts**: Google Fonts (Inter family)
- **Deployment**: GitHub Pages with Jekyll support

### File Structure
- `index.html` - Main HTML structure with semantic markup
- `styles.css` - All styling including responsive design and animations
- `script.js` - Interactive features and UI enhancements
- `_config.yml` - Jekyll configuration for GitHub Pages
- `yevhenii_rodin_resume.pdf` - Resume document

## Key Features

### Responsive Design
- Mobile-first approach with breakpoints at 768px and 480px
- Flexible grid layouts and responsive navigation
- Touch-friendly interactions for mobile devices

### Interactive Elements
- Mobile hamburger navigation menu
- Smooth scrolling between sections
- Animated statistics counters
- Typing animation for hero text
- Parallax effects and scroll-based animations
- Back-to-top button and scroll progress indicator

### Performance Optimizations
- Debounced scroll event handlers
- Intersection Observer API for animations
- Optimized CSS with reduced reflows
- Efficient JavaScript event management

## Development Guidelines

### Making Content Updates
1. **Personal Information**: Update contact details in both HTML and _config.yml
2. **Work Experience**: Modify timeline items in the experience section
3. **Skills**: Update skill categories and items in the skills grid
4. **Resume**: Replace PDF file and update download link

### Styling Changes
- Use CSS custom properties for consistent theming
- Maintain the gradient color scheme (#667eea to #764ba2)
- Preserve responsive breakpoints and mobile-first approach
- Keep animations smooth with proper easing functions

### JavaScript Modifications
- Follow ES6+ standards for new code
- Maintain debounced scroll handlers for performance
- Use modern APIs (Intersection Observer, etc.)
- Ensure mobile compatibility for all interactions

## Deployment

### GitHub Pages Setup
1. Enable GitHub Pages in repository settings
2. Set source to main branch
3. Jekyll will automatically process _config.yml
4. Site will be available at username.github.io/repository-name

### Local Development
- Open index.html directly in browser for basic testing
- Use Live Server extension in VS Code for development
- No build process required - pure static files

## Browser Compatibility

- Modern browsers: Chrome, Firefox, Safari, Edge
- Mobile browsers: iOS Safari, Chrome Mobile
- Graceful degradation for older browsers
- CSS Grid/Flexbox with fallbacks where needed

## SEO Considerations

- Semantic HTML structure throughout
- Meta tags for social media sharing
- Structured data in _config.yml
- Fast loading times and accessibility compliance