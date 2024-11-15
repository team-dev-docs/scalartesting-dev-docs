# prose-table.scss

## Overview

The `prose-table.scss` file is a SCSS stylesheet that defines the styling for tables and other elements within the ProseMirror editor. This file is part of an open-source Docusaurus template and is responsible for the visual appearance of content created using the ProseMirror rich text editor.

Key features of this stylesheet include:

1. Table styling with fixed layout and border collapse
2. Cell styling for both regular and header cells
3. Highlighting for selected cells
4. Column resize handle styling
5. Basic typography adjustments for various elements (paragraphs, lists, code blocks, images, blockquotes, and horizontal rules)

## How can I customize this for my usecase

To customize the `prose-table.scss` file for your specific use case, you can modify various aspects of the styling. Here are some ways you can adapt the styles:

1. **Table appearance:**
   - Adjust the `border` property of `td` and `th` elements to change the border style, color, or width.
   - Modify the `padding` values to increase or decrease cell spacing.
   - Change the `background-color` of `th` elements to use a different color for table headers.

2. **Selected cell highlighting:**
   - Customize the `background` color and opacity of the `.selectedCell:after` pseudo-element to change the appearance of selected cells.

3. **Column resize handle:**
   - Modify the `width`, `background-color`, or `right` position of the `.column-resize-handle` to adjust its appearance or position.

4. **Typography:**
   - Change the `margin-top` value of `> * + *` to adjust the spacing between elements.
   - Modify the `padding` of `ul` and `ol` elements to adjust list indentation.

5. **Code blocks:**
   - Customize the `background-color` and `color` of `pre` elements to change the appearance of code blocks.
   - Adjust the `font-family` to use a different monospace font for code.

6. **Blockquotes:**
   - Modify the `border-left` property of `blockquote` elements to change the style of the left border.

7. **Horizontal rules:**
   - Adjust the `border-top` property of `hr` elements to change the appearance of horizontal rules.

To implement these customizations, open the `prose-table.scss` file and modify the relevant CSS properties. After making your changes, make sure to rebuild your Docusaurus project to apply the updated styles.

Remember to test your changes thoroughly to ensure they don't negatively impact the functionality or appearance of the ProseMirror editor in your Docusaurus template.
