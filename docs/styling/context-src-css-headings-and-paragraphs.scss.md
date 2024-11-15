# headings-and-paragraphs.scss

## Overview

This SCSS file defines styling for headings, paragraphs, and other text elements in a Docusaurus template. It includes styles for both light and dark themes, as well as responsive typography and consistent spacing.

Key features:
- Theme-specific styles for light and dark modes
- Consistent typography for headings (h1-h6) and paragraphs
- Responsive font sizes and weights
- Uniform spacing using a base margin and vertical margin mixin
- Styles for lists, images, and links

## How can I customize this for my usecase

1. **Modify theme colors:**
   - Adjust the color values in the `[data-theme="dark"]` and `[data-theme="light"]` sections to match your brand colors.

2. **Change font families:**
   - Replace the `font-family` declarations with your preferred fonts. You can use system fonts, web fonts, or custom fonts.

3. **Adjust typography:**
   - Modify the `font-size`, `font-weight`, `line-height`, and `letter-spacing` properties for headings and paragraphs to match your design requirements.

4. **Customize spacing:**
   - Change the `$base-margin` value to increase or decrease the overall spacing between elements.
   - Adjust the multipliers in the `vertical-margin` mixin calls to fine-tune spacing for specific heading levels.

5. **Modify link styles:**
   - Update the `a` and `a:hover` selectors to change link colors and hover effects.

6. **Add custom classes:**
   - Create new class selectors for specific elements or components in your documentation.

7. **Responsive design:**
   - Add media queries to adjust styles for different screen sizes.

8. **Extend existing styles:**
   - Use SCSS nesting and extend features to add more specific styles while maintaining the base design.

Example customization:

```scss
// Custom color variable
$brand-primary: #3498db;

[data-theme="light"] {
  h1, h2, h3, h4, h5, h6 {
    color: $brand-primary !important;
  }
}

// Custom heading style
h1 {
  font-size: 36px;
  text-transform: uppercase;
}

// Responsive font size
@media (max-width: 768px) {
  h1 {
    font-size: 28px;
  }
}
```

Remember to test your changes across different themes and screen sizes to ensure consistency and readability throughout your documentation.
