# custom.scss

## Overview

The `custom.scss` file is a central stylesheet for a Docusaurus-based project. It imports various SCSS modules and Tailwind CSS utilities to provide a comprehensive styling foundation for the entire site. This file acts as the main entry point for all custom styles and design preferences.

Key components imported in this file include:

1. Tailwind CSS base, components, and utilities
2. Custom design preferences and secondary colors
3. Component-specific styles (e.g., sidebar, navbar, footer)
4. Typography styles for headings, paragraphs, and prose
5. Styles for specific features like the searchbar, table of contents, and chatbot
6. Styles for different page types (e.g., landing page, blog, cards)

## How can I customize this for my usecase

To customize the `custom.scss` file for your specific needs:

1. **Tailwind CSS customization**: 
   - Modify the Tailwind configuration file to change default styles, add new utility classes, or extend existing ones.

2. **Design preferences**: 
   - Edit the `design-preferences.scss` and `secondaryColors.scss` files to adjust color schemes, fonts, and other global design elements.

3. **Component-specific styles**: 
   - Modify or create new SCSS files for individual components (e.g., `sidebar.scss`, `navbar.scss`) to customize their appearance.

4. **Typography**: 
   - Adjust `headings-and-paragraphs.scss` and `prose.scss` to fine-tune text styles across your site.

5. **Feature-specific styles**: 
   - Customize styles for specific features by modifying files like `searchbar.scss`, `table-of-contents.scss`, or `chatbot.scss`.

6. **Page-type styles**: 
   - Tailor the appearance of different page types by editing files such as `landingpage.scss`, `blog.scss`, or `cards.scss`.

7. **Add new imports**: 
   - Create and import new SCSS modules for additional custom styles or components specific to your project.

8. **Remove unused imports**: 
   - If certain features or components are not used in your project, you can remove their corresponding import statements to reduce the file size.

9. **Order of imports**: 
   - Adjust the order of imports if you need to override specific styles or ensure proper cascading of CSS rules.

Remember to rebuild your project after making changes to see the effects of your customizations.
