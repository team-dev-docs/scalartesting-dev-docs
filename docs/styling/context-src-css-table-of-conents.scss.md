# Table of Contents (table-of-contents.scss)

## Overview

This SCSS file contains custom styles for the Table of Contents component in a Docusaurus theme. It modifies the appearance and behavior of both the mobile and desktop versions of the table of contents, enhancing the user experience and visual appeal.

Key features include:

1. Removal of default background styles for collapsible buttons
2. Custom styling for the "On This Page" header in the desktop version
3. Consistent font styling for table of contents links
4. Custom hover and active states for links
5. (Commented out) Styles for adding visual indicators to active links and applying backdrop filters

## How can I customize this for my usecase

To customize this file for your specific needs, you can modify various aspects of the styles:

1. **Collapsible Button Styles**: 
   If you want to change the appearance of the collapsible buttons, modify the `.tocCollapsibleButton_node_modules-\@docusaurus-theme-classic-lib-theme-TOCCollapsible-CollapseButton-styles-module::after` and `.theme-doc-toc-mobile .tocCollapsibleButton_TO0P:after` selectors.

2. **"On This Page" Header**:
   To change the text, font, or styling of the "On This Page" header, edit the `.theme-doc-toc-desktop::before` selector. You can modify the `content`, `font-family`, `font-size`, `font-weight`, and other properties.

3. **Link Styles**:
   Customize the appearance of the table of contents links by modifying the `.table-of-contents__link` selector. You can change the `color`, `font-family`, `font-size`, and other properties.

4. **Hover and Active States**:
   Adjust the styles for hover and active states by editing the `.table-of-contents__link:hover`, `.table-of-contents__link--active`, and related selectors. You can change colors, add underlines, or apply other effects.

5. **Visual Indicators for Active Links**:
   Uncomment and modify the `.table-of-contents__link--active::before` selector to add a visual indicator (like a border) for the currently active link.

6. **Backdrop Filters**:
   If you want to apply backdrop filters to create a frosted glass effect, uncomment and customize the `[data-theme="light"] .table-of-contents` and `[data-theme="dark"] .table-of-contents` selectors. Adjust the `backdrop-filter`, `background-color`, and other properties as needed.

Remember to test your changes in both light and dark themes to ensure consistency and readability across different color schemes.
