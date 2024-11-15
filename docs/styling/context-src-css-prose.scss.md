# prose.scss

## Overview

The `prose.scss` file is a crucial part of the styling for the ProseMirror editor in this Docusaurus template. It defines the appearance and layout of various elements within the editor, including tables, code blocks, images, and more. The file also includes responsive design elements for mobile devices.

Key features of this stylesheet include:

1. Table styling with cell selection and column resizing
2. Code and pre-formatted text appearance
3. Image sizing and responsive behavior
4. Blockquote and horizontal rule styling
5. Column layout for content blocks
6. Draggable item styling
7. Responsive design adjustments for mobile devices

## How can I customize this for my usecase

To customize the `prose.scss` file for your specific needs, you can modify various aspects of the stylesheet:

1. **Table styling**: Adjust the border colors, cell padding, or background colors in the `.ProseMirror table` section.

2. **Typography**: Modify the margins, padding, or font styles for elements like paragraphs, lists, and headings.

3. **Code blocks**: Change the background color, font family, or text color for inline code and code blocks in the `code` and `pre` sections.

4. **Images**: Adjust the `max-width` and `height` properties in the `img` selector to control image sizing.

5. **Blockquotes**: Customize the appearance of blockquotes by modifying the `padding-left` and `border-left` properties.

6. **Column layout**: Adjust the `gap`, `padding`, or `border` properties in the `.ProseMirror .column-block` and `.ProseMirror .column` sections to change the appearance of column layouts.

7. **Draggable items**: Modify the styling of draggable items by adjusting properties in the `.draggable-item` section.

8. **Responsive design**: Customize the mobile layout by modifying the media queries at the bottom of the file. You can adjust breakpoints, change the layout, or modify font sizes for smaller screens.

9. **Custom elements**: Add new selectors and styles for any custom elements or plugins you may add to the ProseMirror editor.

To implement your changes, simply edit the `prose.scss` file and adjust the CSS properties as needed. Remember to rebuild your project after making changes to see the updates in your Docusaurus site.
