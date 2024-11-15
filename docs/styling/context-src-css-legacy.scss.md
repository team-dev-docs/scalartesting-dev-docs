# legacy.scss

## Overview

The `legacy.scss` file is a crucial component of the open-source Docusaurus template. It contains various SCSS styles that define the appearance and behavior of different elements in the template. This file includes styles for cards, buttons, tables, and responsive design elements.

Key features of this file include:

1. Styling for different types of cards (e.g., magic cards, gradient hover cards)
2. Button styles with gradient effects
3. Table styling
4. Responsive design adjustments
5. Custom animations
6. Utility classes for extending width and height

## How can I customize this for my usecase

To customize the `legacy.scss` file for your specific use case, you can follow these steps:

1. **Color Scheme**: Modify the color variables (e.g., `$color-1`, `$color-2`, etc.) to match your brand's color scheme.

   ```scss
   $color-1: #your-color-here;
   $color-2: #your-color-here;
   // ... and so on
   ```

2. **Card Styles**: Adjust the card styles by modifying classes like `.magic-card`, `.gradient-hover-card-one`, etc. You can change properties such as `border-radius`, `padding`, or `box-shadow`.

   ```scss
   .gradient-hover-card-one {
     border-radius: 20px; // Change the border radius
     padding: 40px 20px; // Adjust padding
     // Add or modify other properties
   }
   ```

3. **Button Styles**: Customize button appearances by modifying classes like `.button`, `.border-button`, or `.gradient-button`.

   ```scss
   .gradient-button {
     background-image: linear-gradient(to right, #your-color-1, #your-color-2);
     // Modify other properties as needed
   }
   ```

4. **Responsive Design**: Adjust the media queries to fit your specific breakpoints and modify the styles for different screen sizes.

   ```scss
   @media (max-width: 768px) {
     // Your custom styles for mobile devices
   }

   @media (max-width: 1024px) {
     // Your custom styles for tablets
   }
   ```

5. **Custom Animations**: Modify existing animations or add new ones to suit your needs.

   ```scss
   @keyframes your-custom-animation {
     0% { /* start state */ }
     100% { /* end state */ }
   }
   ```

6. **Typography**: Adjust font sizes, line heights, and letter spacing to match your design preferences.

   ```scss
   .your-text-class {
     font-size: 16px;
     line-height: 1.5;
     letter-spacing: 0.5px;
   }
   ```

7. **Utility Classes**: Add or modify utility classes to extend functionality.

   ```scss
   .your-custom-utility-class {
     // Your custom styles
   }
   ```

Remember to test your changes thoroughly across different devices and browsers to ensure compatibility and responsiveness. If you're not familiar with SCSS, consider learning its basics to take full advantage of its features like variables, mixins, and nesting.
