# Portfolio Project

## Introduction
Welcome to the Personal Portfolio Project for José. This repository hosts a responsive, single-page portfolio website designed to showcase professional skills, experience, education, and software projects. The site is built with a focus on clean, modern aesthetics and a smooth user experience.

## Project Overview
- **Type**: Static Personal Website
- **Core Technologies**: HTML5, CSS3
- **Objective**: To provide a professional online presence for a Web Developer and UX/UI Designer.

## Way of Working
This section outlines the standards and workflows for contributing to and maintaining this project.

### 1. Project Structure
The project is organized to keep concerns separated:
- **`index.html`**: The main markup file containing the structure of the single-page application.
- **`css/`**: Contains modular CSS files. Each section of the page (Hero, Education, Projects, etc.) has its own dedicated stylesheet for easier maintenance.
- **`assets/`**: Stores all static images and icons used throughout the site.

### 2. Development Guidelines

#### CSS Architecture
We follow a modular CSS approach to ensure maintainability:
- **Global Styles**: Defined in `css/base.css`. This includes CSS variables (custom properties) for colors and fonts, as well as global reset rules.
- **Section Styles**: Styles specific to a page section (e.g., `#hero`, `#skills`) are located in their respective files (e.g., `hero.css`, `skills-exp.css`).  
- **Variables**: Always use the defined CSS variables in `base.css` (e.g., `var(--blue-color)`, `var(--font-family)`) to maintain visual consistency across the site.

#### Code Style
- **Semantic HTML**: Use semantic HTML5 elements (`<section>`, `<nav>`, `<h1>`-`<h6>`) to improve accessibility and SEO.
- **Accessibility**: Ensure all images have descriptive `alt` attributes.
- **Responsiveness**: Use flexible units and media queries to ensure the site looks good on all device sizes.

### 3. Workflow
- **Edits**: To edit a specific section, locate its corresponding HTML in `index.html` and its styles in the `css/` directory.
- **New Features**: When adding a new section, create a new CSS file for it and link it in the `<head>` of `index.html` to keep the codebase clean.
- **Testing**: Open `index.html` directly in your browser to test changes. Ensure to check the layout on different screen sizes.
