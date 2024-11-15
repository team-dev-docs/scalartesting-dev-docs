# chatbot.scss

## Overview

The `chatbot.scss` file contains styling for a chat interface, likely used in a Docusaurus-based website. This file defines the appearance and layout of various chat components, including the chat box, messages, input fields, and toggle buttons. It also includes responsive design adjustments for different screen sizes and supports both light and dark themes.

Key features of this stylesheet include:

- Styling for a fixed-position chat box
- Message bubble designs for user and bot messages
- Loading animation for pending messages
- Responsive design for mobile and tablet devices
- Theme-specific styles for light and dark modes
- Fullscreen chat mode
- Styling for code blocks within chat messages

## How can I customize this for my usecase

To customize the chat interface for your specific needs, you can modify various aspects of the `chatbot.scss` file:

1. **Colors and Theme:**
   - Adjust the color scheme by modifying color values throughout the file.
   - Customize the `[data-theme="dark"]` and `[data-theme="light"]` selectors to fine-tune the appearance for different themes.

2. **Layout and Positioning:**
   - Change the `position`, `bottom`, `right`, `width`, and `height` properties of the `.chat-box` class to adjust the chat box's size and position.
   - Modify the `border-radius` values to change the roundness of various elements.

3. **Typography:**
   - Update `font-family`, `font-size`, `font-weight`, and other text-related properties to match your preferred typography.

4. **Responsive Design:**
   - Adjust the media queries at the bottom of the file to fine-tune the layout for different screen sizes.

5. **Chat Messages:**
   - Customize the `.user-message` and `.bot-message` classes to change the appearance of chat bubbles.
   - Modify the `.loading-dots` animation for a different loading indicator.

6. **Input and Buttons:**
   - Update the `.chat-box__input` and `.chat-box__button` classes to style the input field and send button.

7. **Special Features:**
   - Customize the `.full-screen` class to change how the chat box appears in fullscreen mode.
   - Modify the `.copy-button` class to adjust the appearance of the code copy button.

8. **Animations:**
   - Adjust the `transition` properties and `@keyframes` definitions to change animations and transitions.

Remember to test your changes across different devices and themes to ensure a consistent user experience. You may also want to consider adding new classes or modifying existing ones to introduce additional features or styling options specific to your project's needs.
