# searchbar.scss

## Overview

The `searchbar.scss` file is a crucial component of the Docusaurus template's styling, specifically focusing on the search bar functionality and its responsive design. This SCSS file contains styles that control the appearance and behavior of the search bar across different screen sizes and themes (light and dark mode).

Key features of this file include:

1. Centering and positioning of the search bar
2. Responsive design for various screen sizes (mobile, tablet, desktop)
3. Customization of the search button appearance
4. Theme-specific styling for light and dark modes
5. Z-index management for proper layering of UI elements

## How can I customize this for my usecase

To customize the `searchbar.scss` file for your specific needs, you can make the following adjustments:

1. **Search Bar Positioning**: 
   Modify the `.centerSearchBar` class to change the position and layout of the search bar. Adjust the `top`, `right`, `bottom`, and `left` properties as needed.

   ```scss
   .centerSearchBar {
     // Modify these values to change the position
     top: 10px;
     right: 20px;
     // ...
   }
   ```

2. **Responsive Breakpoints**: 
   Adjust the media query breakpoints to match your desired responsive behavior. Current breakpoints are set at 600px, 967px, and 996px.

   ```scss
   @media (max-width: 768px) {
     // Add your custom styles for tablets
   }
   ```

3. **Search Button Styling**: 
   Customize the appearance of the search button by modifying the `.navbar .aa-DetachedSearchButton` class. You can change the border color, background, and dimensions.

   ```scss
   .navbar .aa-DetachedSearchButton {
     border: 2px solid your-color !important;
     background: your-background-color !important;
     // ...
   }
   ```

4. **Theme-Specific Colors**: 
   Adjust the colors for light and dark themes by modifying the `[data-theme='light']` selectors. You can change text colors, background colors, and other theme-specific properties.

   ```scss
   [data-theme='light'] .navbar-sidebar__back {
     color: your-light-theme-color !important;
   }
   ```

5. **Z-index Adjustments**: 
   If you're having issues with element stacking, you can modify the z-index values to ensure proper layering of UI components.

   ```scss
   .navbar-sidebar {
     z-index: your-desired-value !important;
   }
   ```

6. **Mobile-Specific Styles**: 
   Customize the mobile view by modifying the styles within the smaller screen size media queries (e.g., `@media (max-width: 600px)`).

Remember to test your changes across different screen sizes and both light and dark themes to ensure a consistent user experience. After making modifications, rebuild your Docusaurus project to see the changes take effect.
