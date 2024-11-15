# custom-templates.scss

## Overview

The `custom-templates.scss` file is part of an open-source Docusaurus template. It contains custom SCSS styles that define various visual elements and layouts used throughout the template. These styles are designed to enhance the appearance and functionality of the template, providing a range of customizable components such as cards, grids, and responsive designs.

Key features of this stylesheet include:

1. Responsive grid layouts
2. Custom card designs with hover effects
3. Glassmorphism effects
4. Gradient animations
5. Media queries for different screen sizes
6. Syntax highlighting for code blocks
7. Custom table styles

## How can I customize this for my use case

To customize the `custom-templates.scss` file for your specific needs, you can follow these steps:

1. **Color Scheme**: 
   - Look for color variables (e.g., `$color-1`, `$color-2`, etc.) and modify them to match your desired color scheme.
   - Update gradient colors in various classes like `.gradient-hover-card-one`, `.gradient-hover-card-two`, etc.

2. **Card Styles**:
   - Modify classes like `.general-card`, `.glass-card-one`, `.gradient-hover-card-one`, etc., to change the appearance of different card types.
   - Adjust padding, border-radius, and box-shadow properties to alter the card design.

3. **Grid Layouts**:
   - Customize the `.draggable-grid` and `.draggable-logo-grid` classes to change the layout of grid elements.
   - Modify `flex` properties and `gap` values to adjust spacing and sizing.

4. **Responsive Design**:
   - Edit the media queries (`@media (max-width: 768px)` and `@media (max-width: 1024px)`) to adjust the responsive behavior for different screen sizes.
   - Modify properties like `flex`, `height`, and `padding` within these media queries to fine-tune the mobile and tablet layouts.

5. **Typography**:
   - Adjust font sizes, line heights, and letter spacing in various classes to match your typography preferences.

6. **Animations**:
   - Modify the `@keyframes rotation` and `@keyframes rotate` rules to change animation behaviors.
   - Adjust animation properties in classes like `.gradient-hover-card-one:hover::before` to alter hover effects.

7. **Code Highlighting**:
   - Customize the colors in the `.ProseMirror pre` section to change the appearance of syntax highlighting in code blocks.

8. **Custom Components**:
   - Add new classes or modify existing ones like `.callout`, `.background-landing`, or `.radial-card-content` to create or adjust custom components.

Remember to test your changes thoroughly across different devices and browsers to ensure compatibility and desired appearance. You may also want to use CSS preprocessing tools to take full advantage of SCSS features like variables and mixins for more efficient customization.
