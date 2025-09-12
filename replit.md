# Overview

This is a static portfolio website showcasing CS180 (Computer Science 180) course projects for the Fall 2025 semester. The site serves as a digital portfolio to display academic work and project outcomes using a clean, professional presentation format. Built using the SnapFolio Bootstrap template, it provides an organized way to showcase multiple projects with detailed documentation and visual elements.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture

The site follows a traditional static website architecture with a modular file structure:

- **Template-based Design**: Built on the SnapFolio Bootstrap template, providing a professional portfolio layout
- **Multi-page Structure**: Main index page serves as a project gallery, with individual project pages under separate directories (project0/, project1/, etc.)
- **Responsive Design**: Bootstrap 5.3.8 framework ensures mobile-first responsive behavior across devices
- **Component-based Styling**: Separates concerns with dedicated CSS files for main styles, vendor libraries, and Bootstrap components

## CSS Architecture

- **CSS Variables**: Uses CSS custom properties for consistent theming (colors, fonts, spacing)
- **Dark Theme**: Implements a dark color scheme with customizable accent colors
- **Modular Stylesheets**: Separates Bootstrap framework styles from custom application styles
- **Vendor CSS Management**: Organizes third-party library styles in dedicated vendor directory

## JavaScript Architecture

- **Vanilla JavaScript**: Uses native JavaScript for core functionality without heavy frameworks
- **Event-driven Interactions**: Implements mobile navigation toggles, dropdown menus, and header interactions
- **Third-party Integrations**: Incorporates specialized libraries for enhanced functionality:
  - AOS (Animate On Scroll) for scroll-triggered animations
  - GLightbox for image/media lightboxes
  - Isotope for filterable grid layouts
  - Swiper for touch-enabled carousels

## File Organization

The project follows a clear separation of concerns:

- **Assets Directory**: Centralized location for all static resources
- **Project Directories**: Each project gets its own folder with dedicated index.html
- **Vendor Libraries**: Third-party dependencies isolated in vendor subdirectories
- **Font Management**: Google Fonts integration for typography consistency

# External Dependencies

## CSS Frameworks and Libraries

- **Bootstrap 5.3.8**: Primary CSS framework for responsive design and component styling
- **Bootstrap Icons**: Icon library for UI elements and visual indicators
- **AOS (Animate On Scroll)**: CSS animation library for scroll-triggered effects
- **GLightbox**: Lightweight lightbox library for image and media display
- **Swiper**: Touch-enabled carousel and slider functionality

## JavaScript Libraries

- **Isotope Layout**: Filterable and sortable grid layouts for project organization
- **ImagesLoaded**: JavaScript library for detecting when images have loaded
- **PureCounter**: Lightweight counter animation library
- **Typed.js**: Text typing animation effects
- **Waypoints**: Scroll position detection for triggering animations

## Font Resources

- **Google Fonts**: External font service providing Roboto and Ubuntu font families
- **Custom Font Loading**: Optimized font loading with preconnect directives

## Development Tools

- **PHP Email Form**: Contact form processing capability (template feature)
- **jQuery Bridget**: Utility for making jQuery plugins from vanilla JavaScript libraries

The architecture prioritizes performance through minified assets, CDN-style organization, and modular loading of dependencies. The template-based approach allows for easy expansion with additional projects while maintaining consistent styling and functionality.