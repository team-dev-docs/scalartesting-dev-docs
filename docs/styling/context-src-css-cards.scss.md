# cards.scss

## Overview

The `cards.scss` file is part of an open-source Docusaurus template. It contains SCSS styles that implement a glassmorphism effect for cards, specifically for the dark theme. This effect creates a semi-transparent, frosted glass appearance that can enhance the visual appeal of card components in your Docusaurus site.

The file uses the `[data-theme="dark"]` selector to apply these styles only when the dark theme is active. The glassmorphism effect is achieved through a combination of backdrop filters, background colors, and border properties.

## How can I customize this for my usecase

To customize the glassmorphism card effect for your specific use case, you can modify the following properties within the `.card` class:

1. **Blur and saturation**: Adjust the `backdrop-filter` and `-webkit-backdrop-filter` values to change the blur intensity and saturation. For example:

   ```scss
   backdrop-filter: blur(10px) saturate(180%);
   -webkit-backdrop-filter: blur(10px) saturate(180%);
   ```

2. **Background color**: Modify the `background-color` to change the card's base color and opacity:

   ```scss
   background-color: rgba(17, 25, 40, 0.75);
   ```

3. **Border radius**: Adjust the `border-radius` to change the card's corner roundness:

   ```scss
   border-radius: 16px;
   ```

4. **Border color and opacity**: Modify the `border` property to change the card's border appearance:

   ```scss
   border: 1px solid rgba(255, 255, 255, 0.2);
   ```

5. **Light theme support**: To add glassmorphism effects for the light theme, you can create a new selector outside the `[data-theme="dark"]` block:

   ```scss
   [data-theme="light"] {
     .card {
       // Light theme glassmorphism styles
     }
   }
   ```

Remember to test your changes in different browsers, as some may not fully support backdrop filters. You may need to provide fallback styles for better cross-browser compatibility.
