# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is an ecommerce design collection repository containing static HTML templates organized by page type. The project is designed to showcase various ecommerce page designs for client presentation and will eventually contain hundreds of HTML files.

**Business Context**: This repository supports the broader WordPress/eCommerce automation business strategy, serving as a design showcase and client presentation tool. It complements the automated content generation pipeline and provides visual examples for client proposals.

## Architecture

The repository follows a category-based structure:

- `homepage/` - Homepage design variants (v1-minimal, v2-modern, v3-corporate, etc.)
- `product-pages/` - Product listing and detail page designs (single-product, category-grid, etc.)
- `checkout/` - Checkout flow pages (one-page, multi-step, etc.)
- `assets/` - Shared resources (css/, js/, images/)
- `index.html` - Main showcase file for client presentation

Each HTML file represents a standalone page design that can be viewed independently. Files are named descriptively to indicate their variant or purpose (e.g., `v1-minimal.html`, `single-product-v2.html`).

## Development Standards

### HTML Structure
- Use semantic HTML5 elements
- Include proper meta tags for SEO
- Ensure mobile-responsive design patterns
- Follow accessibility guidelines (WCAG 2.1)
- Use CDN links for external resources (Bootstrap, jQuery, etc.)

### CSS Guidelines
- Prefer external stylesheets in `/assets/css/`
- Use consistent naming conventions (BEM methodology preferred)
- Include responsive breakpoints: mobile (320px+), tablet (768px+), desktop (1024px+)
- Optimize for Core Web Vitals performance

### JavaScript Standards
- Place scripts in `/assets/js/` when reusable
- Use modern ES6+ syntax
- Ensure progressive enhancement
- Minimize dependencies

### Design Principles
- Clean, modern aesthetics suitable for ecommerce
- Focus on conversion optimization
- Industry-specific customization capabilities
- Professional presentation quality for client demos

## File Organization

### Naming Conventions
- Use descriptive names: `homepage-v1-minimal.html`
- Include version numbers for iterations
- Add industry/niche indicators when relevant: `homepage-fashion-v2.html`
- Keep names URL-friendly (lowercase, hyphens)

### Template Categories
1. **Homepage Variants**: Landing pages with different conversion focuses
2. **Product Pages**: Single product, category grids, search results
3. **Checkout Flow**: Cart, checkout steps, confirmation pages
4. **User Account**: Login, registration, dashboard, order history
5. **Content Pages**: About, contact, blog, FAQ
6. **Mobile-Specific**: Touch-optimized variants

## Integration Points

### WordPress Connection
- Templates designed for easy WordPress theme conversion
- Consider WooCommerce compatibility in ecommerce designs
- Structure allows for automated content population via existing script system

### Business Workflow Integration
- Templates serve as visual examples for client proposals
- Designs support the tiered service package strategy ($295-$4,995+ range)
- Connect to broader automation pipeline for rapid client delivery

### Client Presentation
- `index.html` serves as the main portfolio showcase
- Organized for easy navigation during client calls
- Mobile-responsive for tablet presentation scenarios

## Development Workflow

This is a static HTML collection with no build process. Files are meant to be:
1. Created/edited directly as standalone HTML documents
2. Organized into appropriate category directories
3. Committed to Git for version control
4. Deployed via GitHub Pages for client showcase

When adding new designs:
- Place files in the appropriate category directory
- Use descriptive naming conventions following existing patterns
- Ensure designs are self-contained or reference shared assets properly
- Test designs by opening HTML files directly in browsers
- Update `index.html` to include new templates in the showcase

## Quality Standards

### Performance Requirements
- Page load time under 3 seconds
- Optimize images (WebP format preferred)
- Minimize HTTP requests
- Use efficient CSS/JS loading

### Cross-Browser Compatibility
- Test in Chrome, Firefox, Safari, Edge
- Ensure IE11 graceful degradation if required
- Mobile browser optimization (iOS Safari, Chrome Mobile)

### Code Quality
- Validate HTML5 compliance
- Follow consistent indentation (2 spaces)
- Comment complex CSS/JS sections
- Use meaningful class and ID names

## Git Workflow

Standard Git workflow applies. The repository uses `master` as the main branch and is intended for GitHub Pages deployment for client presentation.

**Commit Guidelines**:
- Use descriptive commit messages
- Group related changes in single commits
- Tag major design releases
- Maintain clean commit history

## Business Context Integration

This repository directly supports:
- Client proposal presentations and visual examples
- Rapid prototype development for custom client needs
- Portfolio building for Upwork and other platforms
- Template library for automated content generation systems
- Design reference for WordPress theme customization projects

The templates here bridge the gap between automated backend systems and professional client presentation, supporting the overall business goal of premium positioning in the WordPress automation market.