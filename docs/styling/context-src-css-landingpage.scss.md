# landingpage.scss

## Overview

The `landingpage.scss` file is a crucial component of the styling for the landing page in this Docusaurus template. It contains a variety of CSS styles that define the look and feel of the landing page, including layout, typography, color schemes, and responsive design elements.

Key features of this stylesheet include:

1. Responsive design for various screen sizes
2. Custom styling for headings, paragraphs, and other text elements
3. Glassmorphism effects for certain UI components
4. Dark and light theme support
5. Custom styles for draggable items and grid layouts
6. Specific styling for hero sections and contact forms

## How can I customize this for my usecase

To customize the `landingpage.scss` file for your specific needs, you can follow these steps:

1. **Color Scheme**: Modify the color variables to match your brand's color palette. Look for color definitions like `#cecef8`, `#a4fad1`, etc., and replace them with your preferred colors.

2. **Typography**: Adjust font sizes, weights, and families to align with your design preferences. For example:
   ```scss
   h1 {
     font-size: 4.88313rem;
     font-family: YourPreferredFont, sans-serif;
     font-weight: 700;
   }
   ```

3. **Layout**: Modify the layout properties such as padding, margins, and grid settings to fit your content structure. For instance:
   ```scss
   .content {
     padding-left: 5em;
     padding-right: 5em;
     max-width: 90%;
   }
   ```

4. **Responsive Design**: Adjust the media queries to ensure your landing page looks great on all devices. You can modify existing breakpoints or add new ones:
   ```scss
   @media (max-width: 992px) {
     // Your custom styles for tablets
   }
   ```

5. **Custom Components**: Add or modify styles for specific components you've created. For example:
   ```scss
   .my-custom-component {
     background-color: #f0f0f0;
     border-radius: 8px;
     padding: 1rem;
   }
   ```

6. **Theme Customization**: Modify the dark and light theme styles to match your preferences:
   ```scss
   [data-theme="dark"] {
     // Your custom dark theme styles
   }

   [data-theme="light"] {
     // Your custom light theme styles
   }
   ```

7. **Effects and Animations**: Customize or add new effects like the glassmorphism style:
   ```scss
   .glass-effect {
     backdrop-filter: blur(10px);
     background-color: rgba(255, 255, 255, 0.1);
   }
   ```

Remember to test your changes across different browsers and devices to ensure compatibility and responsiveness. You may also want to use CSS preprocessor features like variables and mixins to make your customizations more maintainable.
