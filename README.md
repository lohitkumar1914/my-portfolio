# README for Portfolio

Welcome to my portfolio! This repository contains the HTML, CSS, and JavaScript files for my personal portfolio website. Below is an overview of the structure and content of each file.

## Table of Contents
1. [Files](#files)
2. [HTML Structure](#html-structure)
3. [CSS Styling](#css-styling)
4. [JavaScript Functionality](#javascript-functionality)
5. [Responsive Design](#responsive-design)
6. [How to Use](#how-to-use)
7. [Credits](#credits)

## Files
- `index.html`: Main HTML file containing the structure of the portfolio.
- `style.css`: Primary CSS file for styling the portfolio.
- `mediaquire.css`: CSS file for media queries to ensure responsiveness.
- `scrpit.js`: JavaScript file for adding interactive functionality.

## HTML Structure
The `index.html` file provides the backbone of the portfolio, organizing content into various sections:
- Header with navigation menu
- Profile section
- About section
- Experience section
- Projects section
- Contact section
- Footer

Each section is encapsulated within `<section>` tags and styled using classes and IDs for targeted CSS styling.

## CSS Styling
### Primary Styles (`style.css`)
- **Font Import**: Uses Poppins from Google Fonts for a clean, modern look.
- **Global Styles**: Basic styles for body, paragraphs, and links.
- **Navigation**: Styles for the navigation bar, including desktop and mobile views.
- **Profile Section**: Flexbox layout to align profile picture and text.
- **Buttons**: Consistent styling for buttons with hover effects.

### Responsive Styles (`mediaquire.css`)
- **Breakpoints**: Defined for screen widths of 1400px, 1200px, 768px, and 600px.
- **Flexbox Adjustments**: Ensures content wraps appropriately on smaller screens.
- **Visibility Toggles**: Switches between desktop and mobile navigation.

## JavaScript Functionality
### `scrpit.js`
- **Toggle Menu**: Function to open and close the mobile navigation menu.
```javascript
function toggleMenu() {
    const menu = document.querySelector(".menu-links");
    const icon = document.querySelector(".hambuger-icon");
    menu.classList.toggle("open");
    icon.classList.toggle("open");
}
```

## Responsive Design
The portfolio is designed to be fully responsive, adapting to various screen sizes using media queries. The layout adjusts from a multi-column format on larger screens to a single-column format on smaller devices. Key elements like the navigation menu switch from a horizontal layout to a hamburger menu for ease of use on mobile devices.

## How to Use
1. **Clone the Repository**: `git clone [repository link]`
2. **Open `index.html`**: You can open this file in any web browser to view the portfolio.
3. **Modify Content**: Feel free to update the HTML, CSS, and JavaScript files to customize the portfolio for your needs.
4. **Deploy**: You can host the portfolio on any web server or deploy it using platforms like GitHub Pages, Netlify, or Vercel.

## Credits
- **Fonts**: [Google Fonts](https://fonts.google.com/)
- **Icons**: Ensure you have linked any icon libraries used (e.g., FontAwesome).
- **Images**: Mention the source of any images used, if applicable.

Thank you for visiting my portfolio! If you have any questions or feedback, feel free to reach out.

---

This README provides a comprehensive overview of the portfolio's structure and functionality, making it easy for anyone to understand and use.
