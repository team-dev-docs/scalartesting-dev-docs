# secondaryColors.scss

## Overview

The `secondaryColors.scss` file is a SASS stylesheet that defines a set of secondary color variables for use in your Docusaurus template. It provides a comprehensive color palette with various shades and tints for four main colors:

1. A pink/magenta color (color-2)
2. A blue color (color-3)
3. A brown/terra cotta color (color-4)
4. Another blue color (color-5, identical to color-3)

Each main color has 12 variations, ranging from lighter tints to darker shades. These are numbered from 1 (lightest) to 12 (darkest), with the main color typically being the 5th or 6th variation.

## How can I customize this for my usecase

To customize the `secondaryColors.scss` file for your specific needs:

1. **Modify existing colors**: You can adjust the RGB values of the main colors (color-2, color-3, color-4, color-5) to match your brand or design preferences.

   ```scss
   $color-2: rgba(199, 21, 133, 1); // Change these values
   $color-3: rgba(30, 144, 255, 1);
   $color-4: rgba(160, 79, 49, 1);
   $color-5: rgba(30, 144, 255, 1);
   ```

2. **Adjust color variations**: You can fine-tune the tints and shades for each main color by modifying the hex values of their variations.

   ```scss
   $color-2-1: #fe58b5; // Lightest tint
   $color-2-2: #ef48a7;
   // ...
   $color-2-12: #5d002f; // Darkest shade
   ```

3. **Add new color sets**: If you need additional color palettes, you can add new color sets following the same pattern:

   ```scss
   $color-6: rgba(R, G, B, 1);
   $color-6-1: #hexvalue;
   $color-6-2: #hexvalue;
   // ... and so on
   ```

4. **Remove unused colors**: If you don't need all four color sets, you can remove the unused ones to keep your stylesheet lean.

5. **Rename variables**: You might want to give more meaningful names to the color variables based on their purpose in your design:

   ```scss
   $primary-pink: rgba(199, 21, 133, 1);
   $primary-pink-light: #fe58b5;
   $primary-pink-dark: #5d002f;
   ```

Remember to update any references to these color variables in your other SCSS or CSS files after making changes. This will ensure consistency throughout your Docusaurus template.
