# navbar.scss

## Overview

The `navbar.scss` file is a crucial component of the open-source Docusaurus template, responsible for styling the navigation bar. It provides custom styles for both light and dark themes, implements a fixed-top navbar, and includes responsive design elements.

Key features of this file include:

1. Theme-specific styles for light and dark modes
2. Sticky positioning for the navbar
3. Blur effect for the navbar background
4. Custom styling for theme toggle buttons
5. Responsive design adjustments

## How can I customize this for my usecase

To customize the `navbar.scss` file for your specific needs, consider the following approaches:

1. **Adjust color schemes:**
   Modify the background colors and text colors for both light and dark themes to match your brand identity.

   ```scss
   [data-theme="dark"] .navbar--fixed-top {
     background-color: rgb(8 28 69 / 30%);
     color: white;
   }

   [data-theme="light"] .navbar--fixed-top {
     background-color: rgba(255, 255, 255, 0.34);
     color: black;
   }
   ```

2. **Customize navbar height:**
   Change the height of the navbar by modifying the `height` property.

   ```scss
   .navbar--fixed-top {
     height: 4.375rem; // Adjust this value as needed
   }
   ```

3. **Modify blur effect:**
   Adjust the blur intensity and saturation of the navbar background.

   ```scss
   .navbar--fixed-top {
     backdrop-filter: blur(16px) saturate(180%);
     -webkit-backdrop-filter: blur(16px) saturate(180%);
   }
   ```

4. **Update theme toggle buttons:**
   Replace the SVG images for the theme toggle buttons with your own custom icons.

   ```scss
   [data-theme="dark"] .navbar__items--right {
     [class^="toggle"] {
       .clean-btn {
         background-image: url("path/to/your/dark-theme-icon.svg") !important;
       }
     }
   }

   .navbar__items--right {
     [class^="toggle"] {
       .clean-btn {
         background-image: url("path/to/your/light-theme-icon.svg");
       }
     }
   }
   ```

5. **Adjust responsive breakpoints:**
   Modify the media queries to better suit your design needs.

   ```scss
   @media (min-width: 1400px) {
     .navbar {
       padding-left: 2em;
       padding-right: 2em;
     }
   }

   @media (max-width: 767px) {
     .navbar__title {
       display: none !important;
     }
   }
   ```

6. **Customize logo dimensions:**
   Adjust the minimum width and height of the navbar logo.

   ```scss
   .navbar__logo {
     min-width: 1.84588rem;
     min-height: 1.6875rem;
   }
   ```

Remember to test your changes across different screen sizes and themes to ensure a consistent user experience. You may also need to update corresponding HTML and JavaScript files if you make significant changes to the navbar structure or functionality.
