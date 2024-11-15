# shadcn.scss

## Overview

The `shadcn.scss` file is a crucial component of the Docusaurus template, combining Tailwind CSS utility classes with custom CSS variables for theming. It defines the color scheme and styling for both light and dark modes, ensuring a consistent and customizable appearance across the documentation site.

Key features of this file include:

1. Tailwind CSS directives
2. CSS custom properties (variables) for theming
3. Dark mode support
4. Base styles for HTML elements
5. Custom styles for Markdown content and Docusaurus-specific elements

## How can I customize this for my usecase

To customize the `shadcn.scss` file for your specific needs, you can follow these steps:

1. **Adjust color scheme**: Modify the CSS custom properties in the `:root` and `.dark` selectors to change the color palette for light and dark modes. For example:

   ```scss
   :root {
     --primary: 210 50% 20%; // Change primary color
     --accent: 150 60% 50%; // Change accent color
   }
   ```

2. **Customize typography**: Add or modify typography-related CSS variables to change font styles, sizes, or weights.

3. **Modify component styles**: Adjust the existing styles or add new ones for specific components or elements. For instance:

   ```scss
   .markdown {
     h1 {
       @apply text-3xl font-bold mb-4;
     }
   }
   ```

4. **Add custom classes**: Create new utility classes or component styles to use throughout your documentation:

   ```scss
   .custom-button {
     @apply bg-primary text-white px-4 py-2 rounded-md;
   }
   ```

5. **Override Docusaurus defaults**: If you need to change specific Docusaurus styling, target the appropriate selectors and apply your custom styles:

   ```scss
   #__docusaurus_skipToContent_fallback {
     // Your custom styles here
   }
   ```

6. **Extend Tailwind configuration**: If you need additional Tailwind utilities, you can extend the Tailwind configuration in your `tailwind.config.js` file and use the new classes in this SCSS file.

Remember to test your changes in both light and dark modes to ensure consistency across your documentation site. After making changes, rebuild your Docusaurus site to see the updates take effect.
