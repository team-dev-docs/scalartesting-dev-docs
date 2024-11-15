# custom.css

## Overview

This file, `custom.css`, is a crucial part of the Docusaurus template's styling system. It imports the core Tailwind CSS modules, which provide a utility-first CSS framework. This approach allows for rapid UI development with pre-defined classes.

The file consists of three main imports:

1. `@import 'tailwindcss/base';`
2. `@import 'tailwindcss/components';`
3. `@import 'tailwindcss/utilities';`

These imports bring in the base styles, component styles, and utility classes from Tailwind CSS, respectively.

## How can I customize this for my usecase

To customize the `custom.css` file for your specific needs, you can:

1. **Add custom CSS rules**: You can add your own CSS rules below the Tailwind imports. These will override or complement the Tailwind styles.

   ```css
   @import 'tailwindcss/base';
   @import 'tailwindcss/components';
   @import 'tailwindcss/utilities';

   /* Your custom CSS here */
   .my-custom-class {
     color: #ff0000;
   }
   ```

2. **Extend Tailwind's configuration**: In your `tailwind.config.js` file, you can extend or override Tailwind's default theme, add new utility classes, or configure plugins.

   ```js
   module.exports = {
     theme: {
       extend: {
         colors: {
           'custom-blue': '#1da1f2',
         },
       },
     },
     // ... other configurations
   };
   ```

3. **Use Tailwind's @apply directive**: You can use Tailwind's utility classes within your custom CSS using the `@apply` directive.

   ```css
   .btn-primary {
     @apply py-2 px-4 bg-blue-500 text-white font-semibold rounded-lg shadow-md hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-400 focus:ring-opacity-75;
   }
   ```

4. **Import additional CSS files**: If you have other CSS files for specific components or pages, you can import them in this file.

   ```css
   @import 'tailwindcss/base';
   @import 'tailwindcss/components';
   @import 'tailwindcss/utilities';

   @import './my-component-styles.css';
   @import './my-page-styles.css';
   ```

Remember to rebuild your project after making changes to see the effects of your customizations.
