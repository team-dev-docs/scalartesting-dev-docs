# sidebar.scss

## Overview

The `sidebar.scss` file is a crucial component of the Docusaurus template's styling system. It primarily focuses on customizing the appearance and behavior of the sidebar, navigation menu, and related elements. This file uses SCSS (Sassy CSS) to define styles for various classes and elements, ensuring a consistent and visually appealing sidebar across the documentation site.

Key features of this file include:

1. Styling for active menu links
2. Custom font settings for menu items
3. Dark theme adaptations
4. Customization of dropdown carets
5. Removal of default borders
6. Mobile-specific adjustments
7. Breadcrumb styling

## How can I customize this for my usecase

To customize the `sidebar.scss` file for your specific needs, you can make the following adjustments:

1. **Colors**: Replace color values (e.g., `#313032`, `#A2A1A5`, `#0D0D0D`) with your preferred color scheme. You can also modify the `$color-1` variable in the `design-preferences.scss` file to change the primary color used throughout the sidebar.

2. **Fonts**: Adjust the font family, size, weight, and other properties to match your desired typography. For example:
   ```scss
   .menu__link {
     font-family: YourPreferredFont, sans-serif;
     font-size: 16px;
     font-weight: 400;
   }
   ```

3. **Active link styles**: Modify the appearance of active menu items by changing the `menu__link--active` class properties. You can adjust the background, color, and border-radius to suit your design.

4. **Dark theme**: Customize the dark theme colors by modifying the styles under the `[data-theme="dark"]` selectors.

5. **Dropdown carets**: Replace the SVG content in the `background` property of `.menu__link--sublist-caret:after, .menu__caret:before` to change the dropdown icon.

6. **Breadcrumbs**: Adjust the breadcrumb styles, including colors, font weights, and visibility of specific items.

7. **Mobile menu**: Customize the mobile menu appearance by modifying the styles for `.navbar-sidebar__back` and `.navbar-toggle`.

8. **Scrollbar**: If you want to display the scrollbar for the table of contents, remove or modify the `.theme-doc-toc-desktop::-webkit-scrollbar-track` rule.

Remember to test your changes across different screen sizes and both light and dark themes to ensure a consistent user experience. If you need to make more extensive changes, consider creating additional SCSS files and importing them into your main stylesheet.
