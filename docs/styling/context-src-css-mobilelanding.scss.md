# mobilelanding.scss

## Overview

The `mobilelanding.scss` file is a crucial part of the responsive design for the Dev-Docs landing page. It contains styles specifically tailored for mobile devices with a maximum width of 767px. This file adjusts various elements of the landing page to ensure optimal display and functionality on smaller screens.

Key features of this stylesheet include:

1. Responsive layout adjustments for the main content area
2. Mobile-specific styling for headings, buttons, and grid layouts
3. Custom styles for hero sections and integration grids
4. Font size and spacing modifications for better readability on small screens
5. Hiding certain elements that may not be suitable for mobile view

## How can I customize this for my usecase

To customize the `mobilelanding.scss` file for your specific needs, consider the following approaches:

1. **Adjust breakpoints**: The current breakpoint is set to 767px. You can modify this value to target different screen sizes:

   ```scss
   @media (max-width: 767px) {
     // Your styles here
   }
   ```

2. **Customize typography**: Modify font sizes, weights, and styles to match your brand:

   ```scss
   h1 {
     font-size: 2.5rem;
     font-weight: 700;
     font-family: 'Your-Preferred-Font', sans-serif;
   }
   ```

3. **Modify color scheme**: Replace color values with your own brand colors:

   ```scss
   .main-btn {
     border: 2px solid #your-color;
     background: #your-background-color;
   }
   ```

4. **Adjust layout and spacing**: Modify padding, margins, and flex properties to fit your design:

   ```scss
   .dev-docs-landing {
     min-height: 320ch;
     display: flex;
     justify-content: flex-start;
     align-items: flex-start;
   }
   ```

5. **Customize hero sections**: Modify background images, colors, and content layout for each hero section:

   ```scss
   .second-hero {
     background-image: url("/path/to/your/image.png");
     background-position: top left;
     background-repeat: no-repeat;
   }
   ```

6. **Adjust or remove specific components**: You can modify or remove styles for components that don't fit your needs, such as the integration grid or draggable elements.

Remember to test your changes across various mobile devices and screen sizes to ensure a consistent user experience. You may also want to use CSS variables for colors and sizes to make global changes easier to manage.
