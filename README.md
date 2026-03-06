> ## Documentation Index
> Fetch the complete documentation index at: https://mazinguerzz-proyecto-pagina-web.mintlify.app/llms.txt
> Use this file to discover all available pages before exploring further.

# Introduction

> Welcome to Coffee Express - A modern coffee shop website with interactive features and beautiful design

# Welcome to Coffee Express

Coffee Express is a modern, fully-featured coffee shop website built with HTML, CSS, and vanilla JavaScript. Designed for a café in Madrid, this project showcases best practices in web development with a focus on user experience, animations, and responsive design.

<Note>
  This documentation covers the complete website structure, components, styling system, and JavaScript functionality.
</Note>

## Key Features

<CardGroup cols={2}>
  <Card title="Interactive Carousel" icon="images" href="/components/carousel">
    Navigate through coffee images with smooth transitions and arrow controls
  </Card>

  <Card title="Animated Hero Sections" icon="wand-magic-sparkles" href="/styling/animations">
    Eye-catching hero sections with Typed.js effects and SVG wave dividers
  </Card>

  <Card title="Coffee Menu Gallery" icon="mug-hot" href="/pages/coffee-menu">
    Showcase hot and cold beverages with an interactive image gallery
  </Card>

  <Card title="Contact Form" icon="envelope" href="/pages/contact">
    Collect customer inquiries with form validation and user feedback
  </Card>

  <Card title="Customer Reviews" icon="star" href="/pages/home">
    Display testimonials with profile images and animated cards
  </Card>

  <Card title="Responsive Navigation" icon="bars" href="/components/navigation">
    Sticky navigation menu with smooth scrolling to page sections
  </Card>
</CardGroup>

## Project Overview

Coffee Express demonstrates modern web development techniques including:

* **Responsive Design**: Mobile-first approach with flexible layouts
* **CSS Custom Properties**: Centralized theming with CSS variables for colors and fonts
* **Animation Integration**: Smooth entrance animations using Animate.css library
* **Interactive JavaScript**: Carousel controls, form validation, and image interactions
* **SVG Graphics**: Custom wave dividers for visual interest
* **Third-party Libraries**: Integration of Typed.js for dynamic text effects

## Website Structure

The website consists of four main pages:

1. **Home** (`index.html`) - Landing page with hero section, image carousel, and customer reviews
2. **About Us** (`About-US.html`) - Company story and employee profile carousel
3. **Coffee Menu** (`OurCoffees.html`) - Gallery of hot and cold coffee beverages
4. **Contact** (`Contactanos.html`) - Contact form for customer inquiries

Each page features consistent navigation, footer, and branding elements.

## Technology Stack

<Accordion title="HTML5">
  Semantic markup with proper document structure, meta tags, and accessibility attributes
</Accordion>

<Accordion title="CSS3">
  Modern CSS features including:

  * CSS Custom Properties (variables)
  * Flexbox and Grid layouts
  * Smooth animations and transitions
  * Responsive design with media queries
</Accordion>

<Accordion title="Vanilla JavaScript">
  Client-side functionality:

  * Image carousel navigation
  * Form validation
  * Interactive image click handlers
  * DOM manipulation
</Accordion>

<Accordion title="External Libraries">
  * **Typed.js**: Typing animation effects
  * **Animate.css**: Pre-built CSS animations
  * Custom fonts from Google Fonts (Caveat, Poppins)
</Accordion>

## Quick Start

<Steps>
  <Step title="Clone the repository">
    Get the project files from GitHub

```bash
git clone https://github.com/MazinguerZZ/Proyecto-Pagina-Web.git
```
  </Step>
  
  <Step title="Navigate to the project directory">
    Vamos a la ruta del proyecto

```bash
cd Proyecto-Pagina-Web/"Proyecto Interfaz"
```
  </Step>

  <Step title="Open in browser">
    Open 'index.html' in your web browser to view the site

```bash
# Using a simple HTTP server (recommended)
python -m http.server 8000
# Then visit http://localhost:8000
```
  </Step>
</Steps>

## Documentation Guide

This documentation is organized into five sections:

* **Getting Started**: Setup instructions and quickstart guide
* **Pages**: Detailed breakdown of each website page and its features
* **Components**: Reusable UI components like navigation, carousel, and footer
* **Styling**: CSS architecture, color system, and animations
* **JavaScript**: Interactive functionality and client-side logic

<Card title="Ready to get started?" icon="rocket" href="/quickstart">
  Jump into the quickstart guide to set up the project
</Card>
