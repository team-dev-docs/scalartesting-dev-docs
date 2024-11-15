# footer.scss

## Overview

The `footer.scss` file is a crucial component of the Docusaurus template, responsible for styling the footer section of the website. It contains SCSS code that defines the appearance and layout of various footer elements, including social media icons, pagination navigation, and copyright information.

Key features of this stylesheet include:

1. Theme-specific styling for dark and light modes
2. Custom styling for pagination navigation links
3. Social media icon implementations (GitHub, Instagram, Discord, LinkedIn)
4. Footer layout and alignment adjustments
5. Responsive design considerations

## How can I customize this for my usecase

To customize the footer styles for your specific needs, you can modify the `footer.scss` file in the following ways:

1. **Adjust theme-specific styles:**
   Modify the styles within `[data-theme="dark"]` and `[data-theme="light"]` selectors to change the appearance of the footer in different color modes.

   ```scss
   [data-theme="dark"] .footer--dark {
     // Your custom dark mode styles
   }

   [data-theme="light"] .footer--dark {
     // Your custom light mode styles
   }
   ```

2. **Customize pagination navigation:**
   Modify the `.pagination-nav__link` and related classes to change the appearance of the "Previous" and "Next" navigation buttons.

   ```scss
   .pagination-nav__link {
     // Your custom styles for navigation links
   }
   ```

3. **Update social media icons:**
   Add or remove social media icons by modifying the respective classes (e.g., `.github`, `.instagram`, `.discord`, `.linkedin`). You can also change the icon sizes or add new icons:

   ```scss
   .new-social-icon {
     width: 24px;
     height: 24px;
     background-image: url("/path/to/your/icon.svg");
     // Other necessary styles
   }
   ```

4. **Adjust footer layout:**
   Modify the `.footer`, `.container-fluid`, and `.row.footer__links` classes to change the overall layout and spacing of the footer elements:

   ```scss
   .footer {
     // Your custom footer styles
   }

   .container-fluid {
     // Adjust max-width or other properties
   }

   .row.footer__links {
     // Modify the layout of footer links
   }
   ```

5. **Customize typography:**
   Update font styles for various footer elements, such as the copyright text:

   ```scss
   .footer__copyright {
     font-family: YourPreferredFont, sans-serif;
     font-size: 12px;
     // Other typography styles
   }
   ```

6. **Add responsive styles:**
   Implement media queries to ensure the footer looks good on different screen sizes:

   ```scss
   @media (max-width: 768px) {
     .footer {
       // Styles for smaller screens
     }
   }
   ```

Remember to test your changes across different browsers and devices to ensure consistency and proper functionality. If you're using CSS modules or a different styling approach in your Docusaurus setup, you may need to adjust the selectors or import statements accordingly.
